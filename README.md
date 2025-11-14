RideEasy – Transparent Meter-Based Ride-Hailing Platform






RideEasy is a commission-free ride-hailing platform designed specifically for rickshaw drivers and college students.
It promotes transparency by using a meter-based fare system rather than high commissions or surge pricing. This ensures affordability for riders and fair income for drivers.

🚀 Project Overview

RideEasy solves the unfair pricing and commission problems in existing ride-hailing apps by:

Eliminating commission cuts

Using real-time meter-based fare calculation

Connecting riders and rickshaw drivers directly

Providing an easy-to-use mobile app for students and daily commuters

Offering a secure backend for authentication, ride matching, and payments

This project focuses on scalability, transparency, and community-driven mobility.

🧰 Tech Stack
Frontend (Mobile App)

Flutter

Provider / Bloc (state management)

Google Maps API (if used)

Firebase Authentication (optional)

Backend

Spring Boot

Spring Web

Spring Data JPA

Spring Security (if applied)

MySQL / PostgreSQL

Kafka (if used for live location events)

Tools

Postman

Git & GitHub

Docker (optional)

🔥 Key Features
✔ User Authentication

Login / Signup for riders and drivers

Secure token-based authentication

✔ Real-Time Ride Booking

Riders request rides

Drivers receive nearby ride requests

Transparent meter-based fare generation

✔ Live Location Tracking

GPS tracking for both rider & driver

Map-based UI

✔ Fare Calculation (No Commission)

Automatically calculated fare from meter logic

No hidden charges

No platform commission

✔ Driver Console

Accept/Decline ride requests

Track earnings transparently

Start/Stop ride meter

✔ Admin Panel (Optional)

Manage users

View ride logs

System analytics

📂 Project Structure
RideEasy/
│── frontend/
│     └── lib/
│          ├── screens/
│          ├── widgets/
│          ├── services/
│          ├── models/
│          └── main.dart
│
│── backend/
│     └── src/main/java/com/rideeasy/
│          ├── controller/
│          ├── service/
│          ├── repository/
│          ├── model/
│          ├── dto/
│          └── config/
│
│── docs/
│     ├── architecture.png
│     ├── API-specifications.md
│     └── SRS.pdf
│
│── README.md

▶️ How to Run the Backend (Spring Boot)
1️⃣ Clone the repo
git clone https://github.com/<your-username>/RideEasy.git
cd RideEasy/backend

2️⃣ Configure database

Update credentials in application.properties.

3️⃣ Run the server
mvn spring-boot:run

▶️ How to Run the Mobile App (Flutter)
cd RideEasy/frontend
flutter pub get
flutter run

📊 System Architecture

Flutter app communicates with

Spring Boot backend, which interacts with

Database for storing rides, drivers, and users

Optional Kafka events for high-scale real-time updates

🎯 Project Goals

RideEasy is built to:

Support local rickshaw drivers

Provide pocket-friendly rides for students

Replace commission-heavy ride apps

Promote a transparent and trustworthy mobility ecosystem

📌 Future Enhancements

Wallet & UPI payments

Driver-level rating system

Ride history & analytics

Real-time chat

SOS safety button

College campus ride-sharing mode

⭐ Support

If you like the vision behind RideEasy, please star ⭐ the repo!
