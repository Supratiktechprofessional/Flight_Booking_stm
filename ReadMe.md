# Flight Booking API Application

SpringBoot Application that demonstrates REST API Development using Spring MVC, Spring Data JPA using Java 8 features

## Features

This application has two primary REST end-points that provide flight-booking information. 

1. GET /bookings?uid={passenger-id}
2. GET /bookings/{booking-id}

Besides these two primary end-points, there are few other end-points to support the consumer apps(mobile/web). They are:
1. GET /airports
2. GET /airports/{iata-code}
3. GET /flights
4. GET /flights/{flight-id}
5. GET /passengers
6. GET /passengers/{passenger-id}

## Technologies used

1. Java (Programming Language)
2. Spring Boot (Application Platform)
3. Spring Data JPA (Data persistence)
4. H2 (Database)
5. JUnit, with Spring Testing (Unit & Integration Testing)

## Getting Started

The source code can be checked out to your local and then build and run the application either from your IDE after importing to it as a maven project, or just from a command line. Follow these steps for the command-line option:  

### Prerequisites
1. Java 8
2. Maven 3
3. Git

