Food Delivery Platform

1. Problem Statement

Develop a Java-based Food Delivery Platform that allows users to manage restaurants, food items, customers, and orders. The system supports food availability checking, order creation, payment processing, order cancellation, refund calculation, order completion, and restaurant rating management.

2. Objectives

- Add and manage restaurants.
- Add food items with prices and stock availability.
- Register customers.
- Create food orders and calculate the total bill.
- Process payments and update food stock.
- Complete and cancel orders.
- Calculate cancellation fees and refunds.
- Allow customers to review completed orders with ratings from 1 to 5.
- Display food availability and restaurant ratings.

3. Technologies Used

- Programming Language: Java
- IDE: Eclipse
- Concepts: Object-Oriented Programming, Classes, Objects, Constructors, Encapsulation, ArrayList, Conditional Statements, Loops, and Switch Statements.
- Data Handling: Java Collections Framework and Scanner for console input.

4. Project Structure

- Restaurant – Stores restaurant details and manages customer ratings and average ratings.
- FoodItem – Stores food item details, including name, price, stock, and associated restaurant.
- Customer – Stores customer information.
- Order – Manages order details, including order ID, food item, customer, quantity, payment status, completion status, and cancellation status.
- Payment – Handles payment processing, checks food availability, and updates stock.
- Cancellation – Manages order cancellation, cancellation fees, refunds, and stock restoration.
- Review – Allows customers to rate restaurants after completing their orders.
- FoodDeliveryPlatform.java – Main application class that provides a menu-driven interface for managing the platform.

5. How to Compile and Run

Using Eclipse IDE

1. Open Eclipse IDE.
2. Create a Java project.
3. Create a Java class named "FoodDeliveryPlatform".
4. Copy the project code into the class file.
5. Run "FoodDeliveryPlatform.java" as a Java Application.

Note: All classes are included in the same Java file. Save the file as "FoodDeliveryPlatform.java".

Using Command Line

Compile the program:

javac FoodDeliveryPlatform.java

Run the program:

java FoodDeliveryPlatform

6. Expected Outcome

The application allows users to manage a food delivery service through a menu-driven Java console interface. Users can add restaurants and food items, register customers, create orders, process payments, complete or cancel orders, calculate cancellation fees and refunds, and submit restaurant ratings.

The system also updates food stock after successful payments and cancellations and displays food availability and restaurant ratings.

7. Data Storage

The application stores restaurant, food item, customer, and order records using "ArrayList".

All data is maintained in memory during program execution. The records are reset when the application is restarted because the system does not use a database or permanent file storage.

8. Student Details

- Name: Neelakandan M
- Roll Number:

9. GitHub Repository

Add your GitHub repository link here.