# DotnetGroup14BloodDonationSystemProject

Project Overview


The Blood Donation Management System is a web based application designed to manage blood donors, hospitals, blood requests, and donations efficiently.

The system provides secure access through role based authentication and enables real time tracking of blood availability, ensuring effective coordination between donors and recipients.



Demo Credentials




Admin	admin@blooddonation.com	Admin123!


Manager	manager@blooddonation.com	Manager123!


Client	client@blooddonation.com	Client123!


System Features


Authentication & Authorization
Secure login and registration using ASP.NET Identity
Role-based access control:
Admin
Manager
Client
Restrictions applied on:
Pages
Buttons (Edit/Delete)
URLs
User actions


Donor Management
Create, view, update, and delete donors
Store donor details including blood type and contact information
Export donor data to Excel


Donation Management
Record donations
Approve or reject donation requests
Automatically update blood inventory
Export donation records


Blood Request Management
Create blood requests
Approve or reject requests
Track request status (Pending, Approved, Completed)
Export request data


Hospital Management
Manage hospital records
Link hospitals to blood requests


Blood Inventory
Automatically updated after donation approval
Tracks available blood units by type


Reporting & Analytics
Visual reports using charts:
Bar charts
Line charts
Doughnut charts
Filter reports by:
Date
Blood type
Export reports to Excel



 Notifications
Toast notifications for:
Successful operations
Errors and failures


Database
SQLite
Automatically created on first run
Includes seeded data, such as:
Blood types
Sample donors
Sample hospitals
Demo users/accounts for each role



Project Structure 
MVC Views & Controllers for each functional module (Donors, Donations, Requests, Hospitals, Reports)
Identity Auth for login and role enforcement
Data Layer configured for SQLite and seeded on startup

MVC Views & Controllers for each functional module (Donors, Donations, Requests, Hospitals, Reports)Identity Auth for login and role enforcement
Data Layer configured for SQLite and seeded on startup
