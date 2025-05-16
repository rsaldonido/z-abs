# Technical Specifications Document

## Title Page
- **Project Name**: Dream Airlines Booking System
- **Version**: 1.0.0
- **Authors**: 
  - **Saldonido, Randolf**  
  - **Sahirani, Kenon**  
  - **Tolentino, Jared Adrielle**  
  - **Diwata, Emmanuel**  

## Table of Contents
1. [Introduction](#1-introduction)
2. [Overall Description](#2-overall-description)
3. [Visual Mockup Reference](#3-visual-mockup-reference)
4. [Features](#4-features)
5. [Functional Requirements](#7-functional-requirements)
6. [Non-Functional Requirements](#8-non-functional-requirements)
7. [Data Requirements](#9-data-requirements)
8. [External Interface Requirements](#10-external-interface-requirements)
9. [Glossary](#11-glossary)
10. [Appendices](#12-appendices)

## 1. Introduction
Welcome to the Dream Airlines Booking System—a modern, mobile-responsive Single Page Application (SPA) designed to streamline flight bookings, enhance user experience, and integrate seamlessly with airline operations.

- **Scope**:
  **Included**: Flight search, booking management, user authentication, payment processing, and admin controls.
  **Excluded**: In-flight services (e.g., meal selection), loyalty programs, or third-party hotel/car rentals.

- **Definitions, Acronyms, and Abbreviations**:
  **SPA**: Single Page Application
  **ERD**: Entity-Relationship Diagram
  **API**: Application Programming Interface

- **References**: Cebu Pacific, Philippine Airlines, Singapore Airlines for UI / UX inspiration.

## 2. Overall Description
- **Product Perspective**: Standalone web application with future API integration for airline partners.
- **Product Functions**: Real-time flight search, multi-step booking, secure payments, and email/SMS notifications.
- **User Classes and Characteristics**:
  1. **Customers**: Book flights, view itineraries.
  2. **Employees**: Manage flights, view itineraries and analytics.
  3. **Admins**: Manage flights, users, and analytics.
- **Operating Environment**:
  **Frontend**: HTML and CSS
  **Backend**: Node.js/Express
  **Database**: MongoDB
- **Assumptions and Dependencies**: TBA.

## 3. Visual Mockup Reference
- **Link or Screenshot**: TBA.

## 4. Features
- **1**. **User Authentication**: Login/logout with JWT.
- **2**: **Flight Search**: Filters (date, destination, price).
- **3**: **Dynamic Booking**: Seat selection, passenger details.
- **4**: **Admin Dashboard**: CRUD operations for flights/users.
- **5**: **Payment Gateway**: TBA

## 7. Functional Requirements
### Use Cases
- **Use Case 1**: Flight Booking
  - **Title**: Book a Flight
  - **Actors**: Traveler
  - **Preconditions**: User is logged in
  - **Main Flow**: Search → Select → Pay → Receive e-ticket.

## 8. Non-Functional Requirements
- **Performance**: 2 seconds response time for search queries.
- **Security**: TBA.
- **Usability**: Responsive, mobile-first design.
- **Reliability**: 98% uptime.
- **Supportability**: Specify maintenance and support requirements.

## 9. Data Requirements
- **Data Models**: TBA.
- **Database Requirements**: TBA.
- **Data Storage and Retrieval**: TBA.
- **ERD**: <a href="https://drive.google.com/file/d/1SQGknZQ-QDj3morG5dkWPVc8OHFHgD7v/view?usp=sharing" target="_blank" rel="noopener noreferrer">Click Here</a>

## 10. External Interface Requirements (TBA)
- **User Interfaces**: 
- **API Interfaces**:
- **Hardware Interfaces**: 
- **Software Interfaces**: 

## 11. Glossary
- **CRUD**: Create, Read, Update, Delete.
- **JWT**: JSON Web Token for authentication.

## 12. Appendices
- **Trello Board**: <a href="https://trello.com/b/rNZOMshn/dream-airlines" target="_blank" rel="noopener noreferrer">Click Here</a>
- **Revision History**: 
  **v1.0.0** (May 2025): Initial draft.