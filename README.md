# J520-SRIMATHI-R-HEXAWARE-SQL-ASSIGNMENT
## Ticket Booking System 
This is a simple Ticket Booking System for managing events and bookings. Users can create events (like movies, concerts, and sports), display events, book tickets for events, cancel bookings, and search for bookings by their ID. The system handles events, customers, and bookings through a console-based menu system.

### Features
Create Event: Create events of different types such as movies, concerts, and sports.

Display All Events: View all available events with their details.

Book Tickets: Book tickets for a specific event.

Cancel Booking: Cancel an existing booking using the booking ID.

Show Booking by ID: Display details of a booking using its ID.

### Technologies Used
Java: Core language for implementing the Ticket Booking System.

Object-Oriented Programming: Following OOP principles such as inheritance, abstraction, and polymorphism.

Custom Exception Handling: Exception handling for invalid booking IDs and other errors.

Scanner for Input: User input is taken via Scanner for interaction.

## Database: MySQL
### Database Schema
Venue (venue_id, venue_name, address)

Event (event_id, event_name, event_date, event_time, venue_id, total_seats, available_seats, ticket_price, event_type)

Customer (customer_id, customer_name, email, phone_number)

Booking (booking_id, customer_id, event_id, num_tickets, total_cost, booking_date)

### Key Features
✔️ Event and Venue Management
✔️ Ticket Booking with Seat Availability
✔️ Customer Data Storage
✔️ Revenue Calculation

### Setup Instructions
Create database:
CREATE DATABASE TicketBookingSystem;
USE TicketBookingSystem;
Create Tables (Venue, Event, Customer, Booking)
Insert Sample Data
Run Queries for Reports & Analysis

### Sample Query
-- Retrieve Events with Available Tickets
SELECT * FROM Event WHERE available_seats > 0;
## Author: Srimathi
## License: MIT
