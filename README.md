FRONTEND  - MIDDLE-END - BACKEND

- We need an intermediate layer between the client side and the microservices
- Using this middle end, when client sends request we will be able to make decision that which microservice
  should actually respond to this request
- We can do message validation, response transformation, rate limiting
- We try to prepare an API Gateway that acts as this middle end.

### Different Microservices
- Flight Booking Service 
`https://github.com/Abhigupta13/AirTicketBookingService-Airline` 
- Flight Search Service
`https://github.com/Abhigupta13/FlightsAndSearchService-Airline`
- Authentication Service 
`https://github.com/Abhigupta13/AuthService-Airline`
- Reminder Service 
`https://github.com/Abhigupta13/ReminderService-Airline`