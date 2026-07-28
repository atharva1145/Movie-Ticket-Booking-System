# 🎬 Movie Ticket Booking System

A clean, object-oriented Java command-line application that simulates a real-world movie ticket booking process. The system allows users to browse movies, check seat availability, book tickets, and manage bookings while demonstrating core Java programming concepts and object-oriented design.

Developed and maintained by **[@atharva1145](https://github.com/atharva1145)**.

---

## 🚀 Features

- **Movie Management**: Display available movies and show details.
- **Seat Availability**: View available seats before booking.
- **Ticket Booking**: Reserve seats through an interactive menu-driven interface.
- **Booking Confirmation**: Generate booking confirmation after successful reservation.
- **Role-Based Access**: Separate Admin and Customer functionalities.
- **Input Validation**: Email validation and seat availability checks.
- **Duplicate Booking Prevention**: Prevent multiple bookings for the same seat.
- **Interactive CLI Interface**: Easy-to-use console-based application.

---

## 🛠️ Technology Stack

- **Language:** Java (JDK 8 or higher)
- **Architecture:** Object-Oriented Programming (OOP)
- **Concepts:** Encapsulation, Inheritance, Polymorphism, Abstraction
- **Libraries:** Java Collections Framework, Scanner Class

---

## 📁 Project Structure

```
Movie Ticket Booking System/
├── Movie_Ticket_Booking_System.java
├── User.java
├── Admin.java
├── Customer.java
├── Movie.java
├── Theater.java
├── Seat.java
├── Show.java
├── Booking.java
├── BookingService.java
├── README.md
└── .gitignore
```

---

## 🏗️ System Components

| Class | Responsibility |
|-------|----------------|
| `User` | Base class for all users |
| `Admin` | Handles administrative operations |
| `Customer` | Manages customer activities |
| `Movie` | Stores movie information |
| `Theater` | Manages theater details |
| `Seat` | Handles seat allocation |
| `Show` | Maintains show schedules and seat availability |
| `Booking` | Stores booking details |
| `BookingService` | Implements booking operations |
| `Movie_Ticket_Booking_System` | Application entry point |

---

## 🎯 Object-Oriented Concepts

### Encapsulation
- Private data members with getters and setters.

### Inheritance
- `Admin` and `Customer` extend the `User` class.

### Polymorphism
- Method overriding for role-specific behavior.

### Abstraction
- Booking logic separated into dedicated service classes.

---

## ⚙️ Prerequisites

- Java Development Kit (JDK 8 or higher)
- Command Prompt, PowerShell, or Terminal

---

## ▶️ Building & Running

### Compile

```bash
javac *.java
```

### Execute

```bash
java Movie_Ticket_Booking_System
```

---

## 💡 Example Usage

```text
===== MOVIE TICKET BOOKING SYSTEM =====

1. View Movies
2. Book Ticket
3. Exit

Enter your choice: 1

Available Movies:
1. Avengers
2. Interstellar
3. Inception

Enter your choice: 2

Enter your name: Atharva
Enter your email: atharva1145@gmail.com

Available Seats:
A1
A2
A3
A4
A5

Enter seat number: A1

Seat booked successfully!
Booking Confirmed.
```

---

## ✅ Validations

- Email format validation
- Seat availability verification
- Duplicate booking prevention
- Invalid seat selection handling
- Invalid input validation

---

## 🚀 Future Enhancements

- Database integration (MySQL)
- Graphical User Interface (Java Swing / JavaFX)
- Multiple theaters and movie shows
- Payment gateway simulation
- Ticket cancellation and refund
- User authentication and authorization

---

## 👤 Author

**Atharva**

- GitHub: **[@atharva1145](https://github.com/atharva1145)**

---

## 📄 License

This project is intended for educational and learning purposes.
