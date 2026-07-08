# 🎬 Movie Ticket Reservation System

A Java-based desktop application developed as a **Semester 3 Object-Oriented Programming (OOP)** group project. The system enables users to browse movies, manage theaters, reserve seats, and book movie tickets using **file-based storage** instead of a database.

---

## 📖 Project Overview

The Movie Ticket Reservation System is designed to simplify the movie ticket booking process while demonstrating the practical application of Object-Oriented Programming concepts and Data Structures.

Unlike traditional booking systems that rely on databases, this project stores all application data using **text files**, making it suitable for learning file handling, data structures, and software design principles.

---

## ✨ Features

### 👤 User Management
- User registration
- User login
- Profile management
- File-based user data storage

### 🎥 Movie Management
- Add new movies
- Update movie details
- Delete movies
- Search movies
- Sort movie list using **Insertion Sort**

### 🏢 Theater Management
- Add theaters
- Update theater information
- Remove theaters
- View available theaters

### 🎫 Ticket Booking
- Browse available movies
- Select theater
- Seat selection
- Seat availability checking
- Booking confirmation
- Booking history

### 🪑 Queue-Based Booking
- Queue implementation for booking requests
- Handles booking order efficiently
- Demonstrates Queue Data Structure implementation

### 📂 File Handling
- Store user information
- Store movie details
- Store theater information
- Store booking records
- Read and write data using text files

---

## 🛠 Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Java File Handling
- Data Structures
- IntelliJ IDEA

---

## 📚 Object-Oriented Programming Concepts

This project demonstrates:

- Classes & Objects
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Exception Handling

---

## 📊 Data Structures Used

| Data Structure | Purpose |
|---------------|---------|
| Queue | Manage booking requests |
| ArrayList | Store collections of users, movies, and theaters |
| Insertion Sort | Sort movies alphabetically |

---

## 📁 Project Structure

```
MovieTicketReservationSystem/
│
├── src/
│   ├── model/
│   ├── service/
│   ├── util/
│   ├── controller/
│   ├── filehandler/
│   └── Main.java
│
├── data/
│   ├── users.txt
│   ├── movies.txt
│   ├── theaters.txt
│   └── bookings.txt
│
├── README.md
└── .gitignore
```

---

## 🚀 Getting Started

### Prerequisites

- Java JDK 17 or later
- IntelliJ IDEA (Recommended)

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/Movie-Ticket-Reservation-System.git
```

2. Open the project in IntelliJ IDEA.

3. Ensure the required data files exist inside the `data` folder.

4. Run the `Main.java` file.

---

## 💾 Data Storage

This project does **not** use a database.

Instead, all application data is stored using **plain text files**, including:

- Users
- Movies
- Theaters
- Bookings

This approach was implemented to strengthen understanding of:

- File I/O
- Data persistence
- Serialization concepts
- Manual CRUD operations

---

## 🎯 Learning Outcomes

Through this project, we gained experience in:

- Object-Oriented Programming
- Java File Handling
- Data Structures and Algorithms
- Team Collaboration
- Software Design
- CRUD Operations
- Exception Handling
- Problem Solving

---

## 👥 Team Project

This project was developed as part of the **Semester 3 Object-Oriented Programming module** at the university.

Each team member contributed to different system modules including:

- User Management
- Movie Management
- Theater Management
- Booking System
- File Handling
- Testing

---

## 📸 Screenshots

> Add screenshots of:
>
> - Login Screen
> - Dashboard
> - Movie List
> - Theater Management
> - Booking Screen
> - Booking Confirmation

---

## 🔮 Future Improvements

- Database integration (MySQL)
- Online payment gateway
- Email ticket confirmation
- QR code tickets
- Admin dashboard
- Search and filter enhancements
- Responsive GUI improvements

---

## 📄 License

This project was developed for educational purposes as part of a university assignment.

---

### ⭐ If you found this project useful, consider giving it a star!
