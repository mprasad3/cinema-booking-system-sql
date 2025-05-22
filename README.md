# 🎬 Cinema Booking System (SQL Project)

A full-featured relational database project for managing a cinema booking system, designed using **MySQL**. This project includes normalized schema design, sample data insertion, and powerful SQL queries covering basic to advanced concepts.

---

## 📌 Project Objective

To develop a well-structured, normalized SQL database that handles:
- Film management
- Room and seat allocation
- Show screenings
- Customer bookings
- Seat reservations

This project showcases strong SQL fundamentals, data modeling, and relational integrity using foreign keys and constraints.

---

## 🛠️ Tech Stack

- **Database**: MySQL
- **Design Tools**: workbench model creator (for ER Diagram)
- **Query Language**: SQL (DDL, DML, DQL)
---

## 🧱 Database Schema

The database consists of 7 tables:

| Table Name      | Description                                 |
|------------------|---------------------------------------------|
| `films`          | Stores film names and lengths               |
| `rooms`          | Cinema rooms with seat capacities           |
| `screenings`     | Links films to rooms and show timings       |
| `seats`          | Seat arrangements by room                   |
| `customers`      | Customer information                        |
| `bookings`       | Booking records per customer per screening  |
| `reserved_seat`  | Booked seats for each booking               |


