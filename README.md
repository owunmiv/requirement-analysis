# Requirement Analysis in Software Development
This is to  document, analyze, and structure the requirements through a series of well-defined tasks. It will include a detailed blueprint of the requirement analysis phase for a booking management system. This project simulates a real-world development scenario, emphasizing clarity, precision, and structure in defining requirements to set the stage for successful project execution. Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

# Why is Requirement Analysis Important?
Getting the Requirements Analysis phase right means avoiding costly mistakes later on. If the foundation is weak or misaligned, everything built on it can crumble.

# Key activities involved in Requirement Analysis
1. Stakeholder Identification
2. Elicitation of Requirements
3. Documentation of Requirements
4. Analysis and Negotiation
5. Validation and Verification

# Types of Requirements
Key Functional Requirements:
Search Properties: Users should be able to search for properties based on various criteria such as location, price, and availability.
User Registration: New users should be able to create an account with personal details and login credentials.
Property Listings: Display properties with essential details and images.
Booking System: Users should be able to book properties, view booking details, and manage their bookings.
User Authentication: Secure login and registration process for users.
Non-functional Requirements 🛡️
Definition Describe how the system should perform. Examples: Performance, security, scalability, usability, reliability.

Key Non-functional Requirements:
Performance: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
Security: Ensure data encryption, secure login, and protect against common vulnerabilities.
Scalability: The system should be able to scale horizontally to handle increased traffic.
Usability: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
Reliability: The system should have an uptime of 99.9% and recover quickly from any failures.

# Use Case Diagram Example
Use Case Diagrams are a type of Unified Modeling Language (UML) diagram that visually represent the functional requirements of a system. They show how different users (actors) interact with the system and what actions (use cases) they can perform.

✅ Benefits of Use Case Diagrams Visual Clarity: Helps stakeholders understand the scope and functionality of the system at a glance.

Improved Communication: Bridges the gap between technical and non-technical teams.

Requirements Validation: Ensures all user interactions are captured before development begins.

Foundation for Testing: Helps in deriving test cases based on user flows.

🖼️ Part 2: Use Case Diagram for a Booking System 🎯 Actors: User (Customer) – Person who books services

Admin – Manages bookings and system data

(Optional: Payment Service if you want to model external systems)

🎯 Use Cases: Register / Login

Search availability

Make a booking

Cancel booking

View booking history

Receive confirmation

Manage services (Admin)

View all bookings (Admin)

Modify/cancel bookings (Admin)

🛠️ How to Create the Diagram Go to https://draw.io (or any UML diagram tool).

Create a UML > Use Case Diagram.

Use stick figures for actors and ovals for use cases.

Use arrows to show which actor performs each use case.

Once finished, export the image 

# How to establish and use Acceptance Criteria
Acceptance Criteria define the conditions that a software feature must meet to be accepted by the product owner or end users. They serve as a checklist to verify functional completeness and correctness.
Importance
Help align expectations between stakeholders and developers.
Provide a baseline for writing test cases.
Reduce ambiguity during development and QA
Example Scenario:"Guest successfully books a property and completes payment." Acceptance Criteria:

The system displays a checkout summary with booking details and total price.
The guest must confirm payment using a valid method.
Upon payment, the booking status updates to “Confirmed."
A confirmation email is sent within 60 seconds of transaction completion.
