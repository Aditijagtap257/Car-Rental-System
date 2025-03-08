Car Rental System

Introduction

The Car Rental System is a Java-based console application that enables users to rent and return cars. This project follows Object-Oriented Programming (OOP) principles to create a structured and modular system.

Features

Add and manage cars in the system.

Rent a car for a specified number of days.

Return a rented car.

Calculate rental price based on the rental period.

Simple console-based menu for interaction.

Technologies Used

Programming Language: Java

Concepts Used: Object-Oriented Programming (OOP) - Classes, Objects, Encapsulation, and Inheritance.

Classes Overview

1. Car

Represents a car in the system.

Stores details like car ID, brand, model, rental price per day, and availability status.

Methods:

calculatePrice(int rentalDays): Computes the total rental cost.

rent(): Marks the car as rented.

returnCar(): Marks the car as available.

2. Customer

Represents a customer who rents a car.

Attributes: customerId, name.

3. Rental

Manages the rental details.

Stores the rented car, customer, and rental duration.

4. CarRentalSystem

Manages cars, customers, and rentals.

Provides a menu-driven interface for renting and returning cars.

5. Main

Entry point of the application.

Initializes the CarRentalSystem and preloads cars
