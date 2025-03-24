# J520-SRIMATHI-R-HEXAWARE-SQL-ASSIGNMENT
##Ticket Booking System - MySQL
A relational database for managing event ticket bookings, including venues, events, customers, and bookings.

###Database Schema
Venue (venue_id, venue_name, address)

Event (event_id, event_name, event_date, event_time, venue_id, total_seats, available_seats, ticket_price, event_type)

Customer (customer_id, customer_name, email, phone_number)

Booking (booking_id, customer_id, event_id, num_tickets, total_cost, booking_date)

###Key Features
✔️ Event and Venue Management
✔️ Ticket Booking with Seat Availability
✔️ Customer Data Storage
✔️ Revenue Calculation

###Setup Instructions
Create database:
CREATE DATABASE TicketBookingSystem;
USE TicketBookingSystem;
Create Tables (Venue, Event, Customer, Booking)
Insert Sample Data
Run Queries for Reports & Analysis

###Sample Query
-- Retrieve Events with Available Tickets
SELECT * FROM Event WHERE available_seats > 0;
##Author: Srimathi
##License: MIT
