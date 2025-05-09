# requirement-analysis
# Requirement Analysis in Software Development
This repository is dedicated to exploring and documenting the Requirement Analysis phase of the Software Development Life Cycle (SDLC). It covers the concepts, importance, and best practices of gathering and defining software requirements. The goal is to provide a clear understanding of how effective requirement analysis contributes to successful project planning, design, and development.

## What is Requirement Analysis?

Requirement Analysis is a vital stage in the Software Development Life Cycle (SDLC) where the development team collects, examines, and defines the software's requirements. This step ensures that everyone involved has a shared and clear understanding of what the system should achieve and how it should behave.

## Why is Requirement Analysis Important?

- **Clarity and Understanding**: Ensures the development team fully grasps what stakeholders want from the software, minimizing misunderstandings.
- **Scope Definition**: Helps outline the boundaries of the project clearly, preventing uncontrolled changes or additions (scope creep).
- **Basis for Design and Development**: Serves as a dependable starting point for creating the system’s architecture and functionality.
- **Cost and Time Estimation**: Aids in making realistic predictions regarding budget, resources, and timeline.
- **Quality Assurance**: Guarantees that the end product aligns with the initial requirements, leading to better user satisfaction.

## Key Activities in Requirement Analysis

### 1. Requirement Gathering

- **Interviews**: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
- **Surveys/Questionnaires**: Distributing surveys to collect requirements from a larger audience.
- **Workshops**: Organizing workshops with stakeholders to discuss and gather requirements.
- **Observation**: Observing end-users in their working environment to understand their needs.
- **Document Analysis**: Reviewing existing documentation and systems to understand current functionalities and requirements.

### 2. Requirement Elicitation

- **Brainstorming**: Conducting brainstorming sessions to generate ideas and gather requirements.
- **Focus Groups**: Holding focus group discussions with selected stakeholders to gather detailed requirements.
- **Prototyping**: Creating prototypes to help stakeholders visualize the system and refine their requirements.

### 3. Requirement Documentation

- **Requirement Specification Document**: Creating a detailed document that lists all functional and non-functional requirements.
- **User Stories**: Writing user stories to describe functionalities from the user’s perspective.
- **Use Cases**: Creating use case diagrams to show interactions between users and the system.

### 4. Requirement Analysis and Modeling

- **Requirement Prioritization**: Prioritizing requirements based on their importance and impact on the project.
- **Feasibility Analysis**: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
- **Modeling**: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

### 5. Requirement Validation

- **Review and Approval**: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
- **Acceptance Criteria**: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
- **Traceability**: Establishing traceability matrices to ensure all requirements are addressed during development and testing.

# Types of Requirements

## Functional Requirements⚙️

define **what** the system should do — the core features and behaviors:

**Examples:** based on the booking management project:

- **Hotel Management Portal**: Hotel managers can add, update, and manage hotel details through a dedicated portal.
- **Customer Portal**: Customers can search for hotels, view listings, apply filters, and make bookings.
- **Search Functionality**: Users can search for hotels using various filters (e.g., location, price, availability).
- **Booking Process**: Users can book hotels through an online interface with date selection and room details.
- **Payment Integration**: The system supports payment processing via a third-party payment service.
- **View Bookings**: Users (both customers and managers) can view current and past bookings.
- **Content Delivery**: Hotel images, offers, and details are displayed via a fast-loading interface using a CDN.
- **Data Synchronization**: Data updates from hotel managers are reflected on the customer side in near real-time.
- **Messaging Queue**: Ensures real-time communication between services and data update propagation.
- **Database Operations**: System handles read/write operations across Hotel DB, Booking DB, Redis, and Cassandra.

## Non-Functional Requirements 🛡️

describe **how** the system performs and maintains quality:
**Examples** based on the booking management project

- **High Performance & Low Latency**: Fast response times using Redis (caching) and CDN (content delivery).
- **Scalability**: Microservices architecture allows the system to scale individual components independently under high user traffic.
- **Availability**: System should remain accessible and operational 24/7 to support global users.
- **Reliability**: Load balancers and replicated databases (master-slave) ensure consistent and reliable data access.
- **Fault Tolerance**: Messaging queue systems (Kafka, RabbitMQ) allow async processing to prevent failure on any one service.
- **Search Optimization**: Elasticsearch enables fast and relevant search results even under heavy data loads.
- **Data Archival**: Cassandra is used to store historical data, ensuring performance doesn’t degrade over time.
- **Security**: Sensitive operations like payments are handled via secure third-party integrations.
- **Maintainability**: The microservices structure supports easier updates and maintenance of specific features or services.

## Use Case Diagrams
### What Are Use Case Diagrams?
Use case diagrams are a type of UML (Unified Modeling Language) diagram used to visually represent the interactions between users (actors) and a system.
They show what the system does (its functionality) from the user's perspective.

### Benefits of Use Case Diagrams
- To capture functional requirements of a system.
- To show interactions between external users (actors) and the system.
- To provide a high-level overview of how the system behaves.
- To help both technical and non-technical stakeholders understand the system.

### use case diagram link: ![Use Case Diagram](https://github.com/Hannah3012/requirement-analysis/view/main/alx-booking-uc.png)



    
    
