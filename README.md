# Assignment-02-Patriti


## Use Cases
- User Registration
- User Authentication
- E-Scooter Reservation
- E-Scooter Pickup
- E-Scooter Drop-off
- User Account Management
- E-Scooter Maintenance
- E-Scooter Tracking
- E-Scooter Station Management
- Reporting Issues or Incidents
- User Billing and Payments

## User Stories
- As a user, I want to register for the service using my email and password.
- As a user, I want to log in to my account securely.
- As a user, I want to find the nearest available e-scooter.
- As a user, I want to reserve an e-scooter for a specific time.
- As a user, I want to unlock an e-scooter using the app.
- As a user, I want to end my ride and lock the e-scooter.
- As a user, I want to view my ride history and receipts.
- As a user, I want to report an issue with an e-scooter.
- As an admin, I want to track the location and status of all e-scooters.
- As an admin, I want to monitor the battery status of e-scooters.
- As an admin, I want to track user activity and history.

## Domain Stories
- Registration Flow (User signs up, verifies email, and sets a password).
- Ride Lifecycle (User finds, reserves, unlocks, rides, and locks the e-scooter).
- Maintenance Workflow (Regular collection, charging, and repairs of e-scooters).
- Station Management (Adding, removing, or relocating e-scooter stations).
- User Account Management (Profile updates, password reset, etc.).
- Reporting and Issue Resolution (User reports an issue, admin reviews, and takes action).
- Billing and Payment Processing (Calculating fares, handling payments).

## Event Storms
- User Registration Flow (Events: Registration, Verification, Password Set)
- Ride Lifecycle Events (Events: Reservation, Unlock, Ride, Lock)
- Maintenance Workflow Events (Events: Collection, Charging, Repair)
- Station Management Events (Events: Station Added, Station Removed, Station Relocated)
- User Account Management Events (Events: Profile Update, Password Reset)
- Issue Reporting and Resolution Events (Events: Issue Report, Review, Resolution)
- Billing and Payment Events (Events: Fare Calculation, Payment Process)

## Quality Attribute Scenarios
- **Performance:** The system should support concurrent user activity, ensuring quick e-scooter reservations and unlocks even during peak hours.
- **Security:** User data and payment information must be stored securely, and only authenticated users should have access to e-scooters.
- **Scalability:** The system should easily scale as more e-scooters and users are added.
- **Reliability:** E-scooter availability and the accuracy of tracking data should be highly reliable.
- **Usability:** The user app and company dashboard should be user-friendly and intuitive.
- **Maintainability:** The system should be easy to maintain and update, and e-scooters should be efficiently serviced.
- **Integration:** The system should integrate with payment gateways, mapping services, and e-scooter hardware for tracking and unlocking.
