# Automated Bus Scheduling and Route Management System

## Overview

The Automated Bus Scheduling and Route Management System is a comprehensive software solution developed using Spring Boot, designed to improve the efficiency and reliability of the Delhi Transport Corporation (DTC). The system automates bus scheduling and route management by leveraging algorithms, data analytics, and Geographic Information System (GIS) technologies.

## Features

### 1. **Linked Duty Scheduling**
- **Crew-Bus Assignment:** Assign a specific crew to a bus for the entire duration of their shift, ensuring continuity and familiarity.
- **Crew Management:** Tools to manage and monitor crew assignments, improving accountability and service quality.

### 2. **Unlinked Duty Scheduling**
- **Bus Handover:** Allows crews to hand over buses to other crew members after completing their trips, optimizing resource utilization.
- **Rest Period Management:** Automatically manages and assigns rest periods for crew members before reassigning them to new duties.

### 3. **Route Management**
- **Route Mapping:** Visual representation of all existing routes within the bus network.
- **New Route Creation:** Tools to draw and propose new routes, with automatic highlighting of overlaps with existing routes.
- **Route Optimization:** Algorithms to reduce congestion, improve service coverage, and optimize resource utilization.

## Installation

### Prerequisites
- **Java 17** or later
- **Maven 3.6.3** or later
- **MySQL** or any other relational database

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/automated-bus-scheduling.git
   cd automated-bus-scheduling
