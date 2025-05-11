1. Project Title:

Clinic Booking System


---

2. Project Description:

This project is a relational database designed to manage patient appointments, doctor availability, and medical records in a clinic. It handles doctor registration, patient data, booking of appointments, and maintains diagnosis records.


---

3. ERD (Entity Relationship Diagram):

Entities:

patients

doctors

appointments

specialties

diagnoses

prescriptions



Relationships:

One doctor can have many appointments (1-M)

One patient can have many appointments (1-M)

One doctor can belong to one specialty (M-1)

One appointment can have one diagnosis (1-1)

One diagnosis can have many prescriptions (1-M)




# Clinic Booking System

## Description
A MySQL-based database system that manages doctor-patient interactions, appointments, and diagnoses in a clinic environment.

## Features
- Register doctors and specialties
- Register patients
- Book appointments
- Log diagnoses and prescriptions

## Setup Instructions
1. Clone the repository.
2. Open the `.sql` file in your MySQL workbench or command-line tool.
3. Run the script to create the database and all tables.

## Entity-Relationship Diagram

## Author
Olaniyi Hamidah Olaitan
