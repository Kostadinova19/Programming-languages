class Car {
    private String type;
    private int no_seats;
    private String fuel;
    private String body_color;

    Car() {
        type = "";
        no_seats = 0;
        fuel = "";
        body_color = "";
    }

    Car(String type, int seats, String fuel, String body_color) {
        this.type = type;
        this.no_seats = seats;
        this.fuel = fuel;
        this.body_color = body_color;
    }

    public String getType() {
        return type;
    }

    public void setType(String type) {
        this.type = type;
    }

    public int getNoSeats() {
        return no_seats;
    }

    public void setNoSeats(int seats) {
        this.no_seats = seats;
    }

    public String getFuel() {
        return fuel;
    }

    public void setFuel(String fuel) {
        this.fuel = fuel;
    }

    public String getBodyColor() {
        return body_color;
    }

    public void setBodyColor(String body_color) {
        this.body_color = body_color;
    }
}
public class Vehicle {
    public static void main(String[] args) {
        Car car1 = new Car("Your favorite car", 4, "Gasoline", "Red");
        Car car2 = new Car();

        // Invoke get methods for car1
        System.out.println("Car 1 Type: " + car1.getType());
        System.out.println("Car 1 Number of Seats: " + car1.getNoSeats());
        System.out.println("Car 1 Fuel Type: " + car1.getFuel());
        System.out.println("Car 1 Body Color: " + car1.getBodyColor());

        // Assign values to the attributes of car2 using set methods
        car2.setType("Second Car");
        car2.setNoSeats(5);
        car2.setFuel("Diesel");
        car2.setBodyColor("Blue");

        // Invoke get methods for car2
        System.out.println("\nCar 2 Type: " + car2.getType());
        System.out.println("Car 2 Number of Seats: " + car2.getNoSeats());
        System.out.println("Car 2 Fuel Type: " + car2.getFuel());
        System.out.println("Car 2 Body Color: " + car2.getBodyColor());

        // Compare the number of passengers (seats) for both cars
        if (car1.getNoSeats() > car2.getNoSeats()) {
            System.out.println("\nCar 1 has more passenger seats.");
        } else if (car2.getNoSeats() > car1.getNoSeats()) {
            System.out.println("\nCar 2 has more passenger seats.");
        } else {
            System.out.println("\nBoth cars have the same number of passenger seats.");
        }
    }
}
