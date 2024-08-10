Automated Bus Scheduling and Route Management System
Overview
The Automated Bus Scheduling and Route Management System is designed to optimize the scheduling and route planning for public bus transportation, specifically for the Delhi Transport Corporation (DTC). The system leverages algorithms, data analytics, and Geographic Information System (GIS) technologies to automate various aspects of bus scheduling and route management, improving operational efficiency and service reliability.

Key Features
Linked Duty Scheduling: Assign a specific crew to a bus for the entire shift, ensuring consistency and accountability.
Unlinked Duty Scheduling: Allow crews to hand over buses after completing their trips, managing rest periods and reassignments.
Route Management: Map existing routes, draw new routes, and highlight overlaps to optimize the bus network.
Real-Time Monitoring: Track and manage crew assignments and bus schedules in real-time.
Reports and Analytics: Generate detailed reports to aid in decision-making and improve service coverage.
Technologies Used
Spring Boot: Backend framework for building robust and scalable applications.
MySQL: Database management system to handle scheduling, route, and crew data.
GIS Tools: For visualizing and optimizing bus routes.
Algorithms: Used for scheduling and route optimization to reduce congestion and enhance efficiency.
Architecture Diagram

Prerequisites
Java 11+
MySQL 8.0+
Maven 3.6+
GIS Software (e.g., QGIS, Google Maps API)
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/automated-bus-scheduling-system.git
cd automated-bus-scheduling-system
Set Up the Database

Create a new MySQL database:
sql
Copy code
CREATE DATABASE bus_scheduling_db;
Update the application.properties file with your MySQL credentials:
properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/bus_scheduling_db
spring.datasource.username=your_username
spring.datasource.password=your_password
Build and Run the Application

Use Maven to build and run the application:
bash
Copy code
mvn clean install
mvn spring-boot:run
Usage
Accessing the System: Once the application is running, you can access it via http://localhost:8080.
Managing Schedules: Use the interface to create and manage both linked and unlinked duty schedules.
Route Management: Visualize existing routes and plan new routes using the integrated GIS tools.
Monitoring: Real-time monitoring of crew assignments and bus schedules is available from the dashboard.
Flow Diagrams
Linked Duty Scheduling
Unlinked Duty Scheduling
Route Management
Contributing
We welcome contributions to this project! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or support, please contact:

Mukesh Prabhakar - mukesh.mmp1234@gmail.com
