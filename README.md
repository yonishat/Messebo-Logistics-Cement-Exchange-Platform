# Messebo-Logistics-Cement-Exchange-Platform-
## 📌 Project Overview
Messebo Logistics is a comprehensive mobile application designed to digitize the tracking, trading, and dispatching of cement commodities from the factory to the destination.

The platform replaces manual logistical tracking with an automated, role-based system that manages inventory, coordinates internal factory queues, and facilitates a live peer-to-peer marketplace for customers and independent truck drivers.

## 🛠 Tech Stack
Frontend: React Native, Expo, TypeScript, Axios, React Context API.

Backend: Python, FastAPI, SQLAlchemy ORM.

Database: PostgreSQL / SQLite.

Security: JWT (JSON Web Tokens) Authentication, Role-Based Access Control.

## 🚀 Core Features & Role-Based Dashboards
The application provides distinct, secure interfaces based on the user's role:

1. Office Administration 

Digital Intake: Secure registration of new G.D. numbers to specific customers.

Automated Batch Dispatching: An algorithm that matches waiting internal fleet trucks with available coupons.

Lane 2 Vetting: A 30-minute SLA interface to approve or reject independent drivers who accept external routes.

Global Tracking: A comprehensive "God View" to monitor the status and assigned truck of every commodity in the system.

2. Customer Portal (The Exchange)

Live Inventory: Customers can track their owned commodities and view their exact position in the factory loading queue.

P2P Marketplace: Users can list full truckloads or split containers for sale to other verified users.

Trade Center: A secure bidding system to make, accept, or reject offers, with automated routing finalization upon purchase.

3. Driver Operations (The Fleet)

Dynamic Factory Lineup: A live queue system for internal drivers, complete with "Drop Back" and "Emergency Abort" functionalities.

Independent Load Board: A public job board where independent drivers can claim Lane 2 routes.

Active Routing: Real-time status updates allowing drivers to mark loads as "In Transit" and "Delivered."
