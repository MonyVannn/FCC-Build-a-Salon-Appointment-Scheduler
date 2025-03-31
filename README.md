# Salon Appointment Scheduler

## Overview
This project is an interactive Bash program that utilizes PostgreSQL to manage customer appointments for a salon. It was developed as part of the freeCodeCamp "Build a Salon Appointment Scheduler" certification project.

## Features
- Customers can select a service from a list.
- New customers are prompted to enter their name and phone number for registration.
- Existing customers can book appointments using their phone number.
- The system stores and retrieves customer data from a PostgreSQL database.
- Appointments are saved and managed within the database.

## Technologies Used
- **Bash**: The core scripting language used for interaction.
- **PostgreSQL**: Database management system to store customer and appointment data.
- **Gitpod**: Virtual development environment used for project implementation.

## Usage
- The script will prompt you to choose a service.
- If you're a new customer, you'll be asked to enter your details.
- Once a service and time are selected, the appointment is saved.
- The system confirms the scheduled appointment.

## Database Schema
The database consists of the following tables:
- `customers`: Stores customer information (ID, name, phone number).
- `services`: Lists available salon services.
- `appointments`: Records customer appointments with service details.

## Files in the Repository
- **`salon.sh`**: The main script handling user interactions and database operations.
- **`salon.sql`**: The PostgreSQL script to set up the database schema.

## How to Submit
After completing the project, submit the repository URL containing the required files (`salon.sh` and `salon.sql`).

