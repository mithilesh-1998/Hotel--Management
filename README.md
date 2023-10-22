# Hotel--Management

## Framework and Language Used
- Framework: Spring Boot
- Language: Java

## Data Flow
The data flow in the project follows the typical MVC (Model-View-Controller) pattern:

1. Controller: Handles incoming HTTP requests, validates inputs, and coordinates the flow of data.
2. Service: Contains the business logic of the application and interacts with the repository.
3. Repository: Provides the interface to interact with the underlying database.
4. Database: Stores the Room entities and their related data.

## Database Design
The project uses an H2 Database, an in-memory database, for simplicity. A table OYO is created to store the  Room entities,.

The `Room` entity has the following attributes:
- roomId: Integer
- roomNumber: Integer
- lastName: String
- roomType: enum
- roomAvailable: boolean
- roomPrice : double


 ## Project Summary
The RoomApp Application project is a spring boot based application that provides APIs for managing Rooms.

The application allows you to perform the following operations on Room:
- Add a new Room.
- Add a multipule rooms at a single time.
- Get list of all rooms.
- Get a room by Id.
- Get a room by price.
- Get a room on price available.
- Get a room by type.
- Delete  a room by Id .

The project leverages Spring Boot's built-in validation annotations to enforce data constraints on various fields.
