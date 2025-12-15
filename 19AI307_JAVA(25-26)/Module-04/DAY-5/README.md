# Ex.No:4(D) DESIGN PATTERN  ---- BEHAVIOUR PATTERN

    }

    int calculateFare(int distance) {
        return distance * pricePerKm;
    }
}

class AutoRide extends Ride {
    AutoRide() {
        super("AutoRide", 8, 10);
    }
}

class BikeRide extends Ride {
    BikeRide() {
        super("BikeRide", 15, 15);
    }
}

class CabRide extends Ride {
    CabRide() {
        super("CabRide", -1, 20); 
    }
}

public class ZoomCarGoV3 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int distance = sc.nextInt();
        int budget = sc.nextInt();

        List<Ride> rides = new ArrayList<>();
        rides.add(new AutoRide());
        rides.add(new BikeRide());
        rides.add(new CabRide());

        Ride bestRide = null;
        int minFare = Integer.MAX_VALUE;

        for (Ride ride : rides) {
            if (ride.isAvailable(distance, budget)) {
                int fare = ride.calculateFare(distance);
                if (fare < minFare) {
                    minFare = fare;
                    bestRide = ride;
                }
            }
        }

        if (bestRide != null) {
            System.out.println(bestRide.name + " booked for " + distance + " km. Fare: ₹" + minFare + ".");
        } else {
            System.out.println("No rides available for your distance and budget.");
        }

        sc.close();
    }
}
```






## OUTPUT:

<img width="961" height="288" alt="image" src="https://github.com/user-attachments/assets/82a0f720-1396-4eb7-b186-6059c4bd2e46" />


## RESULT:

Thus, the program to build a ride-selection system that filters rides based on distance and budget, then automatically books the cheapest valid option is executed successfully.


