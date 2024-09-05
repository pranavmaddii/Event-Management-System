# Event Management System

An event management system built using Java Spring Boot, featuring three key modules: Admin, Event Manager, and Customer. The system provides a smooth and efficient workflow from event creation to booking, ensuring seamless user experience for both event managers and customers.

## Features
- **Admin Module**: Approve or reject event managers before they can add events.
- **Event Manager Module**: Create and manage events with details like name, date, location, and capacity, subject to admin approval.
- **Customer Module**: Browse and book events, with real-time availability checks to prevent overbooking.

## Technology Stack
- **Backend**: Java Spring Boot
- **Database**: MySQL
- **Frontend**: HTML/CSS/JavaScript (or your choice of frontend framework)

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo-url/event-management-system.git
    ```
2. Navigate to the project directory and run the application:
    ```bash
    cd event-management-system
    ./mvnw spring-boot:run
    ```
3. Ensure MySQL is running and update the `application.properties` file with your database credentials.

## Usage
1. **Admin**: Log in to approve event managers.
2. **Event Manager**: Log in to create events after approval.
3. **Customer**: Browse available events and book your spot.

## Contributing
Feel free to contribute by creating a pull request or opening an issue.

## Credits
Developed by Pranav.
