# Parking Lot Management System

## Overview
This application manages a parking lot, allowing users to view, reserve, and pay for parking spaces in real-time. The system tracks availability, handles reservations, and offers an admin dashboard for managers.

## Requirements
- Java Development Kit (JDK) version 11 or above
- MySQL Database (or your specified database)
- Database connector (included in the `lib` folder)

## Installation
1. Install the Java Development Kit (JDK) if not already installed.
2. Set up a MySQL database and create tables using the provided SQL script in the `database` folder (if provided).

## Configuration
1. Open `config/config.properties` and add your database credentials:
   ```properties
   db.url=jdbc:mysql://localhost:3306/parking_lot
   db.user=yourUsername
   db.password=yourPassword
