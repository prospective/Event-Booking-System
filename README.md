# Event-Booking-System
This challenge involves designing and implementing a RESTful API for an Event Booking System. This system will enable users to create events, book tickets for events, and manage bookings. Each event should have details such as name, description, location, date, time, and the total number of tickets available.

## Requirements

### API Endpoints:

- **Create a new event**: Include details such as name, description, location, date, time, and ticket capacity.
- **Update an existing event's details**: Modify any aspect of an event after its creation.
- **Retrieve all events**: List all available events.
- **Book tickets for an event**: Allow users to book tickets, specifying their name and the number of tickets.
- **Cancel a booking**: Provide the option to cancel previously made bookings.

### Data Model:

- Design a comprehensive data model to support both events and bookings. This model should clearly define the relationships between events and their bookings, ensuring data integrity and consistency.

### Persistence:

- Opt for a relational database or an in-memory database for data storage. Implement data access layers for efficient and streamlined database operations.

### Business Logic:

- Implement checks to ensure bookings do not exceed the total ticket capacity for any event.
- Design logic to manage cancellations and booking updates, including the necessary adjustments to the available ticket count.

### Testing:

- Develop unit tests targeting your business logic to verify its accuracy and reliability.
- Create integration tests for your API endpoints, ensuring they function correctly under various scenarios and inputs.

### Documentation:

- Document all API endpoints. This documentation should provide clear usage instructions, including details on request formats, response structures, and query parameters.

### Security (Optional):

- Implement security measures for your API endpoints. Options include basic authentication or JWT-based authentication to ensure that access is controlled and secure.

### Docker (Optional):

- Provide Docker support by including a Dockerfile and any necessary configuration files.


## Challenge solution review
Please develop an application which fullfills the described requirements. Push your code to your github profile (*PRIVATE Repository*) and invite following users to the repo.

* [borisstock](https://github.com/borisstock)
* [m1l3](https://github.com/m1l3)
* [ehinterberger](https://github.com/ehinterberger)
* [peterstaub81](https://github.com/peterstaub81)
* [StarHack](https://github.com/StarHack)
* [minderjan](https://github.com/minderjan)
