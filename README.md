# Ride-Sharing-API-in-SpringBoot

This project is a microservices-based ride-sharing application implemented using Spring Boot. The application is divided into four main microservices: Admin, Driver, Passenger, and Trip. Each microservice is responsible for specific operations related to ride-sharing.

## 1. Admin Microservice

The Admin microservice provides the following operations:

- **View All Users:** Admin can see the list of all users.
- **Search User by ID:** Admin can search for a specific user using their ID.
- **Search Users by User Type:** Admin can search for users based on their type (e.g., Admin, Passenger, Driver).
- **Delete Users:** Admin can delete users from the system.

## 2. Driver Microservice

The Driver microservice provides the following operations:

- **Check Active Trip:** Drivers can view the active trips assigned to them.
- **Take a Trip:** Drivers can accept a trip request.
- **End Trip:** Drivers can mark a trip as completed.

## 3. Passenger Microservice

The Passenger microservice provides the following operations:

- **Request a Car:** Passengers can request a ride.
- **Deny Trip:** Passengers can cancel a trip request.
- **Check Active Trips:** Passengers can view their current active trips.
- **Rate Driver:** Passengers can rate their driver after a trip.

## 4. Trip Microservice

The Trip microservice provides the following operations:

- **Generate Trip Bill:** The trip controller can generate the bill for a completed trip.
- **Check All Active Trips:** The trip controller can view all ongoing trips.
- **Login Permission:** The trip controller can manage user login permissions.

---

Each of these microservices interacts with others to provide a seamless ride-sharing experience. The application is designed with scalability and maintainability in mind, leveraging the power of Spring Boot and microservices architecture.
