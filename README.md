
# API Gateway for Booking Pilot Microservice Backend Project

This project consists of several microservices that form the backend of a flight booking system. The API Gateway acts as a single entry point for clients to interact with the system, routing requests to the appropriate microservices. Below are the different microservices involved in this project:

## Microservices

### 1. Flight Booking Service
This service handles all functionalities related to booking flights. Users can book, modify, and cancel flight reservations.

- **Repository:** [Flight Booking Service](https://github.com/Abhigupta13/AirTicketBookingService-Airline)

### 2. Flight Search Service
This service allows users to search for available flights based on various criteria such as destination, date, and price.

- **Repository:** [Flight Search Service](https://github.com/Abhigupta13/FlightsAndSearchService-Airline)

### 3. Authentication Service
This service manages user authentication and authorization. It handles user login, registration, and verification processes.

- **Repository:** [Authentication Service](https://github.com/Abhigupta13/AuthService-Airline)

### 4. Reminder Service
This service sends reminders and notifications to users about their flight schedules, upcoming bookings, and other important information.

- **Repository:** [Reminder Service](https://github.com/Abhigupta13/ReminderService-Airline)

## Additional Information

### API Gateway
The API Gateway serves as the single entry point for all client requests. It routes incoming requests to the appropriate microservices, handles authentication and authorization, and can perform other functions like load balancing, rate limiting, and logging.

### Architecture
The microservices architecture ensures that each service is independently deployable, scalable, and maintainable. Each service communicates with others through well-defined APIs, typically using HTTP/REST or messaging queues.

### Technology Stack
- **Backend:** NodeJs, ExpressJs ,
- **Database:** MySQL
- **Authentication:** JWT (JSON Web Tokens)
- **Others:** MVC architecture 

### Getting Started
To start the project, follow the instructions provided in each microservice's repository. Clone the repositories and follow the setup instructions.


