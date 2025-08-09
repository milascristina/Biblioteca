# Library Loan Management Application

## Overview
This is a JavaFX-based library management application that allows users to view available books, select the ones they wish to borrow, and manage their loan list. The interface provides options to add or remove books from the borrowing list and finalize the loan process.

## Features
- **View Available Books:** Displays a list of books with their title and author.
- **Borrow Books:** Each book has a dedicated "Împrumută" button to add it to the loan list.
- **Loan List Management:** View all selected books in a separate window with the option to remove any book before finalizing.
- **Finalize Loan:** Once the selection is complete, the user can confirm the borrowing process.
- **Return to Book List:** Easily navigate back to the available books list to add more items.
- **Responsive UI:** Clean and organized JavaFX design for intuitive navigation.

## Technologies & Architecture
- **Programming Language:** Java
- **GUI Framework:** JavaFX
- **Architecture:** Layered architecture with the following layers:
  - **Domain Layer:** Defines the `Book` entity with attributes such as title and author.
  - **Repository Layer:** Manages the storage and retrieval of book data.
  - **Service Layer:** Implements business logic for borrowing and returning books.
  - **UI Layer:** Handles JavaFX views and user interactions.
- **Design Pattern:** Model-View-Controller (MVC) for separation of concerns.

## Installation & Setup
1. Ensure you have **Java 17+** installed.
2. Import the project into an IDE such as IntelliJ IDEA or Eclipse.
3. Run the application from the main class (e.g., `Main.java`).

## Usage
1. Launch the application.
2. Browse the list of available books.
3. Click **Împrumută** to add a book to your loan list.
4. Click **Vizualizează Cărți pentru Împrumut** to review your selection.
5. Remove books from the loan list if needed.
6. Click **Finalizează Împrumutul** to complete the process.

## Screenshots
<img width="372" height="657" alt="Screenshot 2025-08-09 184059" src="https://github.com/user-attachments/assets/a83cd1ce-1f6c-43c1-a73d-5db62ec52156" />
<img width="375" height="662" alt="Screenshot 2025-08-09 184121" src="https://github.com/user-attachments/assets/006dd0b5-1bd3-4f80-81e7-a2a15062bf09" />
<img width="372" height="670" alt="Screenshot 2025-08-09 184300" src="https://github.com/user-attachments/assets/b7c14ac0-fff4-4653-bf1a-2ffa7ab17cc6" />
<img width="370" height="659" alt="Screenshot 2025-08-09 184314" src="https://github.com/user-attachments/assets/7f5e47f5-aa47-43ef-93bc-d0e7300db449" />
