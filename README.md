Airline Reservation System
Requirements

Java 15 or higher is required to run the .jar file of this project.

IntelliJ IDEA or any other preferred Java IDE.

Overview

This is a Java-based airline reservation system built using Object-Oriented Programming (OOP) principles.
The system supports customer and admin roles, allowing flight booking, cancellation, and management.
OOP concepts such as inheritance, encapsulation, association, and composition are applied throughout the implementation.

Features
1. Customer Registration

Users must register to use the system.

Login credentials are required for future access.

2. Customer Login

After logging in, customers can:

Book Flights: Enter the flight number and the number of tickets to reserve a flight.

Update Profile Data: Modify personal information including name, email, phone number, address, and age.

Delete Account: Permanently remove an account and associated data.

View Random Flight Schedule: See scheduled flights for the current session. The number of flights can be adjusted in the Flight class's flightScheduler() method.

Cancel Flights: Cancel booked tickets and return them to the available flight pool.

View Registered Flights: List flights the customer has booked, including their current status.

3. Admin Registration & Login

Admins have full control over the reservation system, including:

Performing CRUD operations.

Managing flight schedules.

Managing customer accounts.

Deleting flights.

Viewing all passengers.

Viewing all flights booked by a specific passenger.

Viewing all passengers registered on a specific flight.

How to Run

Install Java 15 or higher.

Open the project in IntelliJ IDEA or your preferred IDE.

Compile and run the program, or execute the .jar file if available.
