# OOP-practice

# Problem: Create a class hierarchy to represent different types of vehicles. The hierarchy should include a base class called "Vehicle" and two derived classes called "Car" and "Motorcycle". Additionally, implement an array of objects to store instances of these classes.

## The "Vehicle" class should have the following features:

Instance variables:

## manufacturer (a string) to store the manufacturer of the vehicle.
year (an integer) to store the manufacturing year of the vehicle.
Methods:

## Vehicle(String manufacturer, int year): Initializes the manufacturer and year instance variables with the given values.
void displayDetails(): Displays the manufacturer and year of the vehicle.
The "Car" class should inherit from the "Vehicle" class and have the following additional features:

## Instance variables:

## numDoors (an integer) to store the number of doors in the car.
Methods:

## Car(String manufacturer, int year, int numDoors): Initializes the manufacturer, year, and numDoors instance variables with the given values.
void displayDetails(): Overrides the base class method to display the manufacturer, year, and number of doors of the car.
The "Motorcycle" class should also inherit from the "Vehicle" class and have the following additional features:

## Instance variables:

## hasSidecar (a boolean) to indicate whether the motorcycle has a sidecar or not.
Methods:

## Motorcycle(String manufacturer, int year, boolean hasSidecar): Initializes the manufacturer, year, and hasSidecar instance variables with the given values.
## void displayDetails(): Overrides the base class method to display the manufacturer, year, and whether the motorcycle has a sidecar or not.
## Write the code for the classes described above and demonstrate the usage of an array to store instances of the "Vehicle", "Car", and "Motorcycle" classes.
