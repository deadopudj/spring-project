# spring-project

Stakeholder:

I own several pretty nice accommodations on Adriatic coast. They are well equipped and I am ready for renting this summer. How can I advertise them and also track the reservations? 

Accommodation Reservation System

# Week One Assignment

## General assignments: "Prepare advertisements!"
  Implement Accommodation resource RESTful API over HTTP.

- Path to this resource should be: /api/accomodation
- 4 HTTP methods should be implemented. (e.g. GET, POST, PUT and DELETE)


### JPA assignments
- Model Accommodation as JPA Entity. Attributes:
    - title (String, max 100 characters)
    - subtitle (String, max 200 characters)
    - description (String)
    - type - one of the accomodation types (Room, Apartment, Mobile home)
    - categorization (Integer 1-5 - mandatory)
    - personCount (Integer, min 1)
    - imageUrl
    - freeCancelation (boolean, default true)
    - price (decimal, mandatory)
- Implement equals and hashCode methods for Apartment JPA Entity
- Implement toString method for Apartment JPA Entity

### Spring Framework assignments
- Use Spring Data JPA Repository for Apartment JPA Entity persistence
- Use Context to fetch Spring Bean
- Use Dependancy Injection
- Use Qualifiers
- Use Multiple Profiles
- Use @PostConstruct in ApartmentReservationSystemApplication class to initialize data for Apartment

------------

#### Covered lectures
1. Introduction to Spring Framework 5: Beginner to Guru  
    - Spring Framework 5 - Course Introduction
2. Building a Spring Boot Web App  
    - Introduction 
    - Open Project in IntelliJ 
    - JPA Entities 
    - Equality in Hibernate
    - Spring Data Repositories 
    - Initializing Data with Spring
    - H2 Database Console
    - Assignment - Add Publisher Entity 
    - Introduction to Spring MVC 
    - Configuring Spring MVC Controllers 
    - Assignment - Display List of Authors 
3. Dependency Injection with Spring 
    - SOLID Principles of OOP
    - Create Spring DI Example Project 
    - The Spring Context
    - Basics of DI
    - Dependency Injection without Spring
    - Dependency Injection using Spring Framework 
    - Using Qualifiers
    - Primary Beans
    - Spring Profiles 
    - Default Profile 
    - Spring Bean Life Cycle 
    - Dependency Injection Assignment
    - Spring Bean Life Cycle Demo
    - Single Responsibility Principle
    - Open Closed Principle
    - Interface Segregation Principle
    - Dependency Inversion Principle
