# 🎬 Movie and Show Booking System

A simple **Java-based Movie and Show Booking System** that allows users to view available movies, select show timings, choose ticket types, check seat availability, calculate ticket prices, and confirm bookings through a console-based interface.

## 📌 Features

* 🎥 View available movies
* 🕐 Select show timings
* 🎟️ Choose ticket type:

  * Adult
  * Child
  * Senior
* 💺 Check available seats before booking
* 💰 Automatically calculate total ticket price
* ✅ Confirm or cancel bookings
* 🔄 Book multiple tickets in a single session
* 📊 Automatically update remaining seats after successful booking
* ❌ Handles invalid movie and ticket-type selections

## 🛠️ Technologies Used

* **Java**
* **Object-Oriented Programming (OOP)**
* `Scanner` for user input
* Classes and Objects
* Constructors
* Methods
* Conditional Statements
* Loops

## 🎞️ Available Movies

| Movie         | Available Seats | Adult | Child | Senior |
| ------------- | --------------: | ----: | ----: | -----: |
| Good Bad Ugly |              50 |   300 |   150 |    200 |
| Dragon        |              30 |   400 |   200 |    250 |
| Kanguva       |              20 |   350 |   175 |    220 |

## 🕐 Show Timings

Each movie provides the following show timings:

* 2:00 PM
* 5:00 PM
* 8:00 PM

## 🧱 Project Structure

```text
MovieAndShowBookingSystem/
│
├── MovieAndShowBookingSystem.java
└── README.md
```

### `Movie` Class

The `Movie` class stores movie-related information:

* Movie name
* Available seats
* Adult ticket price
* Child ticket price
* Senior ticket price

It also provides methods to:

```text
calculateTotalPrice()
updateAvailableSeats()
checkAvailableSeats()
```

### `MovieAndShowBookingSystem` Class

This is the main class of the application. It:

1. Displays available movies
2. Takes movie selection from the user
3. Displays show timings
4. Takes ticket type
5. Accepts the number of tickets
6. Checks seat availability
7. Calculates the total price
8. Confirms the booking
9. Updates remaining seats
10. Allows the user to make another booking

## ▶️ How to Run

### 1. Install Java

Make sure Java JDK is installed on your system.

Check the installation:

```bash
java -version
```

### 2. Compile the Program

Open a terminal in the project directory and run:

```bash
javac MovieAndShowBookingSystem.java
```

### 3. Run the Program

```bash
java MovieAndShowBookingSystem
```

## 💻 Sample Execution

```text
Welcome to the Movie Booking System!

Available Movies:
1. Good Bad Ugly
2. Dragon
3. Kanguva

Enter movie number (1, 2, or 3): 1

Available Show Timings for Good Bad Ugly:
1. 2:00 PM
2. 5:00 PM
3. 8:00 PM

Select the show timing (1, 2, or 3): 2

You selected: Good Bad Ugly
Show Time: 5:00 PM
Available Seats: 50

Select the ticket type:
1. Adult ($300.0)
2. Child ($150.0)
3. Senior ($200.0)

Enter ticket type (1, 2, or 3): 1

Enter number of tickets to book: 2

Total price for 2 adult tickets: $600.0

Do you want to confirm the booking? (yes/no): yes

Booking confirmed!
Remaining seats: 48
```

## 🧠 OOP Concepts Demonstrated

This project demonstrates several fundamental Java concepts:

### Class and Objects

The `Movie` class represents movie information, while `movie1`, `movie2`, and `movie3` are objects created from it.

### Constructor

The constructor initializes movie details such as name, seats, and ticket prices.

### Encapsulation

Movie-related data and operations are grouped inside the `Movie` class.

### Methods

Separate methods are used for:

* Price calculation
* Seat availability checking
* Seat updates

### Conditional Statements

`if-else` statements are used for movie, ticket type, and booking selections.

### Looping

A `while` loop allows users to continue making bookings until they choose to stop.

## 🔮 Future Improvements

The project can be extended with:

* 👤 Customer name and contact details
* 💳 Online payment simulation
* 🪑 Individual seat selection
* 🎫 Booking ID generation
* 📅 Date selection
* 🎭 Multiple screens/theatres
* 💾 Database integration
* 🖥️ GUI using JavaFX or Swing
* 🌐 Web-based movie booking interface
* 📧 Booking confirmation
* 🧾 Digital ticket generation

## 🎯 Learning Objective

The main objective of this project is to demonstrate the practical implementation of **Java Object-Oriented Programming concepts** by developing a simple real-world movie booking application.

## 👨‍💻 Author

**Vishvaharan C**

B.Tech – Artificial Intelligence & Data Science

---

⭐ If you found this project useful, consider giving the repository a star!
