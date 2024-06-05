# Welcome to `FixFlex Documentation`!

## Table of Contents

### Chapter 1: Introduction

- [1.1 Overview](#11-overview)
- [1.2 Objectives](#12-objectives)
- [1.3 Purpose](#13-purpose)
- [1.4 Scope](#14-scope)
- [1.5 General Constraints](#15-general-constraints)

### Chapter 2: Planning and Analysis

- [2.1 Project Planning](#21-project-planning)
  - [2.1.1 Feasibility](#211-feasibility)
  - [2.1.2 Estimated Cost](#212-estimated-cost)
  - [2.1.3 Gantt Chart](#213-gantt-chart)
- [2.2 Analysis and Limitation of Existing System](#22-analysis-and-limitation-of-existing-system)
- [2.3 Need for New System](#23-need-for-new-system)
- [2.4 Analysis of the New System](#24-analysis-of-the-new-system)
  - [2.4.1 User Requirements](#241-user-requirements)
  - [2.4.2 System Requirements](#242-system-requirements)
  - [2.4.3 Domain Requirements](#243-domain-requirements)
  - [2.4.4 Functional Requirements](#244-functional-requirements)
  - [2.4.5 Non-Functional Requirements](#245-non-functional-requirements)
- [2.5 Advantages of the New System](#25-advantages-of-the-new-system)
- [2.6 Risk and Risk Management](#26-risk-and-risk-management)

### Chapter 3: System Design

- [3.1 Software Architecture Diagram](#31-software-architecture-diagram)
- [3.2 Design of Database (ERD or Class Diagram)](#32-design-of-database-erd-or-class-diagram)
- [3.3 Use Case Diagram](#33-use-case-diagram)
- [3.4 Sequence Diagram](#34-sequence-diagram)
- [3.5 Activity Diagram](#35-activity-diagram)
- [3.6 State Diagram](#36-state-diagram)
- [3.7 Workflow Diagram](#37-workflow-diagram)
- [3.8 Deployment Diagram](#38-deployment-diagram)
<!-- - [3.9 Component Diagram](#39-component-diagram) -->

### Chapter 4: System Implementation and Results

- [4.1 Software Architecture](#41-software-architecture)
- [4.2 Flowchart or Workflow](#42-flowchart-or-workflow)

### Chapter 5: Testing

- [5.1 Test Cases](#51-test-cases)
- [5.2 Bug Reports](#52-bug-reports)

### Chapter 6: Result

- [6.1 Expected Results](#61-expected-results)
- [6.2 Actual Results](#62-actual-results)

### Chapter 7: Conclusion

- [7.1 Conclusion](#71-conclusion)

---

## Chapter 1: Introduction

### 1.1 Overview

**What is FixFlex?**

FixFlex is a platform that connects people who need tasks done with individuals willing to complete those tasks for pay. It operates like traditional freelancing platforms such as Upwork, Fiverr, and Freelancer, where users can post tasks or jobs, and taskers make offers on these tasks. The user then selects the most suitable tasker for the job.

**Key Differences:**

- FixFlex focuses on a wide range of everyday tasks and services.
- Specializes in connecting people who need tasks like plumbing, electricity, painting, cleaning, moving, and more with handymen willing to perform these tasks for pay.

**For Task Posters:**

- Creating a job listing is straightforward.
- Upload a detailed description of your task, specify the category, set your budget, and add any relevant images or documents.

**For Taskers:**

- Set offers that users can choose from.
- Create a compelling profile highlighting your expertise, experience, and previous work.
- Browse through a variety of tasks, submit quotes, and communicate directly with potential clients.

**Platform Features:**

- Transparency and trust with ratings and reviews.
- Secure and straightforward payments.
- Mobile apps for both iOS and Android devices for convenient access.

Whether you're looking to get a task done or to offer your skills, FixFlex is your go-to platform for seamless, efficient, and trustworthy service exchanges.

### 1.2 Objectives

- **Accessibility for All:** FixFlex's primary goal is to be an inclusive platform, welcoming users from various walks of Egypt. We aim to bridge the gap between demand and supply in the service sector, ensuring easy access for everyone.
- **Support for Varied Needs:** FixFlex provides a comprehensive range of categories, ensuring that no matter what your requirements are, you will find a skilled professional to help you.
- **Upholding Privacy and Confidentiality:** We place a high value on the privacy and confidentiality of our users. Personal information and transaction details are securely handled and protected.
- **Ensuring Quality and Reliability:** FixFlex implements a robust system of ratings and reviews, ensuring a reliable and quality experience.
- **Fostering a Community of Support:** By providing a platform where individuals can seek help and professionals can offer their services, FixFlex aims to foster a sense of community and mutual support.

### 1.3 Purpose

- **Diversity in Services:** FixFlex provides many services that the customer needs with high quality, so that the customer can find what he needs in one place.
- **Speed:** FixFlex works to quickly respond to the request and ensures its presence in all governorates in Egypt for rapid arrival.

### 1.4 Scope

- **Broad Geographic Reach:** FixFlex aims to assist people across various locations and regions.
- **Verification and Transparency:** Ensuring the authenticity of the cases and building trust with donors by supporting campaigns with photos.
- **Open Platform:** FixFlex will be an open platform where any visitor can submit a case that requires assistance.

### 1.5 General Constraints

Understanding the limitations and constraints of a project is crucial for its successful execution and management. Here are the general constraints for the FixFlex project:

- **Time Constraint:** The project is subject to a specific timeline, which includes deadlines for each phase and the final rollout date.
- **Scope Constraint:** This defines the boundaries of the project, including its goals, deliverables, features, and functions.
- **Cost Constraint:** The budget of the project is a critical constraint, encompassing all financial resources required for timely and effective completion within the defined scope.
- **Collecting Raw Data:** Gathering the necessary data for the project poses its own set of challenges.

---

## Chapter 2: Planning and Analysis

### 2.1 Project Planning

**Development Approach and Methodology**

- **System Development Life Cycle:** We followed the system development life cycle approach with its 7 phases: planning, analysis, design, development, testing, deployment, and maintenance.

![OIP](https://github.com/fixflex/backend/assets/124518625/6b0bdbf3-cbcd-498d-8137-0e83735fe755)

- **Methodology:** We followed Agile analysis and design methodology, developing all related UML diagrams.

#### 2.1.1 Feasibility

**Technical Feasibility:** The technical feasibility of the project was assessed by considering the available resources,
technologies, and infrastructure required for the development and deployment of the FixFlex platform.
The project team conducted a thorough analysis of the technical requirements and evaluated the available technologies and tools to determine
the feasibility of implementing the proposed system.

#### 2.1.2 Estimated Cost

**Development Cost:** The estimated cost of developing the FixFlex platform was calculated based on the resources, technologies, and infrastructure required for the project.
The development cost included expenses related to software development, hardware, licensing, hosting, and other associated costs.

#### 2.1.3 Gantt Chart

## 2.1.3 Gantt Chart

### Productivity & Workflow Template

#### Project Initiation #project-initiation

- **Define Scope**
  - Identify key features
  - Set objectives
- **Requirements Gathering**
  - Collect requirements from stakeholders
  - Document requirements

#### Design Phase #design-phase

- **System Architecture Design**
  - Data flow design
  - Services identification
  - Integrations outline
- **UI/UX Design**
  - Web application design
  - Mobile application design

#### Development Phase #development-phase

- **Backend Development**
  - Authentication module
  - Task management system
  - User management system
  - Payment processing
  - Notifications system
- **Frontend Development**
  - Web application frontend
  - Mobile application frontend
- **Integration of Third-Party Services**
  - Paymob integration
  - OneSignal integration
  - WhatsApp API integration
- **Database Design and Implementation**
  - Users database
  - Tasks database
  - Payments database
  - Notifications database

#### Testing Phase #testing-phase

- **Unit Testing**
  - Backend unit tests
  - Frontend unit tests
- **Integration Testing**
  - Backend and frontend integration
  - Third-party services integration
- **User Acceptance Testing (UAT)**
  - Real user feedback collection
  - Necessary adjustments

#### Deployment Phase #deployment-phase

- **Deployment to Serverless Platform**
  - Render deployment
- **Monitoring and Optimization**
  - Performance monitoring
  - Scalability optimization

#### Launch Phase #launch-phase

- **User Training and Support**
  - Training sessions
  - Support documentation
- **Post-launch Support and Maintenance**
  - Bug fixes
  - Feature enhancements

### Resources

- **Tools:**
  - Project management software
  - Design tools (e.g., Figma)
  - Development environment
  - Testing tools
- **Team:**
  - Project manager
  - UX/UI Designers
  - Backend Developers
  - Frontend Developers
  - Mobile Developers
  - QA Engineers

### Notes

- Weekly check-ins scheduled every [Day of Week]
- Bi-weekly sprint reviews and planning
- Maintain version control using [Version Control System]
- Ensure documentation is updated continuously

### 2.4 Analysis of the New System

#### 2.4.1 User Requirements

Our FixFlex will consist of the following users:

1. **User:**
   - Can create an account, log in, upload a profile image, update profile details, post tasks, receive offers, track task status, communicate with taskers, rate taskers, and make payments.
2. **Tasker:**
   - Can do everything a user does, plus upload work type, phone number, location to profile, browse tasks, make offers, and send notifications.
3. **Admin:**
   - Can delete or update tasks, and manage user and tasker details.

#### 2.4.2 System Requirements

- **Software and Hardware:** Details of the software, hardware, and network infrastructure used for the system.
- **Database:** The type and location of the database.
- **Programming Languages:** The programming languages used in the system.

#### 2.4.3 Domain Requirements

- **Business Needs:** The benefits and goals of the system for the business, aligning with project and stakeholder objectives.

#### 2.4.4 Functional Requirements

1. **Registration:**
   - Users must log in with basic details (first name, last name, email, password, mobile number, address).
2. **Login User:**
   - Users log in with email and password, edit profiles, and upload profile images.
3. **Login Admin:**
   - Admin logs in with email and password, updates profile, manages users and tasks.
4. **Task Posting:**
   - Users describe tasks, set budgets, select categories, and post tasks.
5. **Browse Task:**
   - Taskers browse tasks, view details, make offers, and complete tasks.
6. **Real-time Chat:**
   - Users and taskers communicate in real-time through the built-in chat system.
7. **Task Status Tracking:**
   - Users track task status and receive notifications.
8. **Ratings and Review:**
   - Users rate taskers and leave reviews based on their experience.

#### 2.4.5 Non-Functional Requirements

1. **Performance Requirements:**
   - Support multiple users, normalized and distributed database, and frequent backups.
2. **Safety Requirements:**
   - Database backup to prevent data loss.
3. **Security Requirements:**
   - Ensure system consistency and security, restrict communication during user validation.
4. **Usability:**
   - Achieve user goals easily, perform tasks quickly, and provide a simple design.

### 2.5 Advantages of the New System

- **Unified Home Repair Services:** Brings together multiple services in one place.
- **Comprehensive Service Range:** Focuses on a variety of services, not just one.

### 2.6 Risk and Risk Management

**Risks:**

1. Not gaining customer trust.
2. Responsibility due to providing many services.

---

## Chapter 3: System Design

### 3.1 Software Architecture Diagram

![diagram-export-6-3-2024-4_52_20-AM](https://github.com/fixflex/backend/assets/124518625/07d13334-31f0-400b-82a1-ad4c6f4ac67f)

<!-- ![diagram-export-6-3-2024-4_07_24-AM](https://github.com/fixflex/backend/assets/124518625/9613428a-f276-490a-a69e-7cb9de723579)
![diagram-export-6-3-2024-12_55_29-AM](https://github.com/fixflex/backend/assets/124518625/7be183fc-3d78-4dda-95ba-0d992c8dadd0) -->

### 3.2 Design of Database (ERD or Class Diagram)

![diagram-export-6-3-2024-12_16_26-AM](https://github.com/fixflex/backend/assets/124518625/c094b37f-0e4b-41a6-9d28-2df0da258110)

<!-- [View on Eraser![](https://app.eraser.io/workspace/XwWDPW5cER2Ni7aB0mRw/preview?elements=z_CjHs8IOks5nioHBSA7gw&type=embed)](https://app.eraser.io/workspace/XwWDPW5cER2Ni7aB0mRw?elements=z_CjHs8IOks5nioHBSA7gw) -->

### 3.3 Use Case Diagram

![diagram-export-6-2-2024-5_35_06-AM](https://github.com/fixflex/backend/assets/124518625/9821d322-2b4b-41fa-907e-2e98fdb23695)

### 3.4 Sequence Diagram

<!-- ![diagram-export-6-3-2024-5_22_11-AM](https://github.com/fixflex/backend/assets/124518625/6a5edb6e-a134-4d01-b9f2-f8488e94af3c) -->

![diagram-export-6-2-2024-2_58_19-AM](https://github.com/fixflex/backend/assets/124518625/2b088b98-5f52-427d-bacc-7a5b931d1b19)

<!-- ![diagram-export-6-3-2024-5_22_11-AM](https://github.com/fixflex/backend/assets/124518625/71853e1f-467b-4f41-be44-285f26c33364)
![diagram-export-6-2-2024-5_45_12-AM](https://github.com/fixflex/backend/assets/124518625/5a8ecca1-19cf-49bc-9e08-2291b06546f8)
![diagram-export-6-2-2024-2_58_19-AM](https://github.com/fixflex/backend/assets/124518625/2b088b98-5f52-427d-bacc-7a5b931d1b19) -->

<!--
[![APIs and Services](https://app.eraser.io/workspace/uLd8gYOOKbkHgaqYzJQ7/preview?elements=6-V8_N9yupVgbS8NmmFVCg&type=embed)](https://app.eraser.io/workspace/uLd8gYOOKbkHgaqYzJQ7?elements=6-V8_N9yupVgbS8NmmFVCg) -->

### 3.5 Activity Diagram

![diagram-export-6-3-2024-5_45_23-AM](https://github.com/fixflex/backend/assets/124518625/520c2a24-b8ea-43f9-b8a1-0569d3f1b828)

<!-- ![diagram-export-6-2-2024-5_54_09-AM](https://github.com/fixflex/backend/assets/124518625/c0a8ea52-ecc6-4de3-90fb-bf5a77625418) -->

### 3.6 State Diagram

![diagram-export-6-3-2024-5_50_41-AM](https://github.com/fixflex/backend/assets/124518625/b8b73304-e6e3-4fd4-a94c-d2335464d7ab)

<!-- ![diagram-export-6-2-2024-6_05_06-AM](https://github.com/fixflex/backend/assets/124518625/07393cf0-45c2-4802-84db-430ba57f4c0d) -->

### 3.7 Workflow Diagram

![diagram-export-6-3-2024-1_55_55-AM](https://github.com/fixflex/backend/assets/124518625/82feb5d9-872c-4a59-82c5-6c629464005a)

### 3.8 Deployment Diagram

![diagram-export-6-3-2024-6_55_38-AM](https://github.com/fixflex/backend/assets/124518625/b196bf46-d42d-4b94-abf8-972e7b433840)

## Chapter 4: System Implementation and Results

### 4.1 Software Architecture

The backend of `fixflex` follows a modular, scalable, and maintainable architecture, leveraging TypeScript, Express.js, and MongoDB. The architecture is designed to ensure code reusability, separation of concerns, and scalability to accommodate future growth and changes in the application's requirements.

## Model-View-Controller (MVC) Pattern 🌐

The backend architecture of `fixflex` follows the Model-View-Controller (MVC) pattern, which divides the application into three main components:

- `Models`: Represents the data structure of the application, interacts with the database using Mongoose, and defines the schema for each resource.
- `Controllers`: Processes incoming requests, interacts with services, and returns responses to clients.
- `Routes`: Defines the API endpoints, maps HTTP methods to controller actions, and provides a standardized interface for clients to interact with the application.

## Data Access Object (DAO) Pattern 💾

The backend architecture of `fixflex` employs the Data Access Object (DAO) pattern to separate the data access logic from the business logic. The DAO pattern encapsulates the database operations for each resource into a separate file, providing a clean and modular structure for managing data access.

## Data Transfer Object (DTO) Pattern 📦

The backend architecture of `fixflex` uses Data Transfer Objects (DTOs) to transfer data between layers and components. DTOs define the structure of data exchanged between the client and server, ensuring consistency and type safety throughout the application.

## Service Layer 🛠️

The backend architecture of `fixflex` includes a service layer that encapsulates the business logic of the application, interacts with the data access layer, and provides a centralized interface for controllers to access application functionality. The service layer helps maintain separation of concerns, improves code reusability, and facilitates testing and debugging.

## Middleware 🚪

The backend architecture of `fixflex` includes middleware functions that intercept incoming requests, perform actions, and pass control to the next middleware or route handler. Middleware functions are used for tasks such as authentication, error handling, logging, input validation, and more, providing a modular and extensible architecture for managing request processing.

## Dependency Injection 🔄

The backend architecture of `fixflex` employs dependency injection using the tsyringe package to manage component dependencies and improve code maintainability, flexibility, and testability. Dependency injection helps decouple components, promote code reuse, and facilitate the implementation of inversion of control (IoC) principles.

## Database Schema 📊

The database used for `fixflex` is MongoDB, a NoSQL database that stores data in a flexible, JSON-like format.

See - [3.2 Design of Database (ERD or Class Diagram)](#32-design-of-database-erd-or-class-diagram) file for more details.

The database schema for `fixflex` consists of the following collections:

- `Users`: Stores user information such as name, email, phone number, password, role, profile picture, and verification status.
- `Taskers`: Stores tasker information such as user ID, description, skills, qualifications, availability, ratings, and earnings.
- `Tasks`: Stores task information such as user ID, title, description, category, location, status, budget, images, and timestamps.
- `Categories`: Stores category information such as name, description, parent category, and subcategories.
- `Coupons`: Stores coupon information such as code, discount amount, expiry date, and usage limit.
- `Offers`: Stores offer information such as task ID, tasker ID, amount, status, and timestamps.
- `Reviews`: Stores review information such as task ID, tasker ID, user ID, rating, comment, and timestamps.
- `Chats`: Stores chat information such as user IDs, task ID, tasker ID, and timestamps.
- `Messages`: Stores message information such as chat ID, user ID, tasker ID, content, and timestamps.
- `Transactions`: Stores transaction information such as user ID, tasker ID, amount, type, status, and timestamps.

## RESTful API Design 📐

The API design for `fixflex` follows RESTful principles, with clear and predictable URL structures, HTTP methods, and status codes. The API endpoints are organized into resource-based routes, with each route corresponding to a specific resource or entity in the system. The API design includes the following key features:

- `Resource-Based Routes`: Organizes API endpoints into resource-based routes such as /users, /tasks, /taskers, /offers, /reviews, /categories, and /coupons.
- `CRUD Operations`: Implements Create, Read, Update, and Delete operations for all resources using HTTP methods such as GET, POST, PUT, PATCH, and DELETE.
- `Pagination and Filtering`: Supports pagination and filtering for listing resources, allowing users to limit the number of results and filter based on specific criteria.
- `Search and Sorting`: Allows users to search for resources based on keywords, categories, locations, and other criteria, enhancing resource discovery.
- `Error Handling`: Provides informative error messages, status codes, and error responses to help clients understand and handle errors effectively.

## Modular Structure 🧩

- **Controllers**: Handle incoming requests, process data, and send responses to clients.
- **Services**: Contain business logic, interact with the database, and perform operations on data.
- **Models**: Define data structures and schemas for MongoDB collections using Mongoose.
- **Routes**: Define API endpoints, route requests to controllers, and handle HTTP methods.
- **Middleware**: Implement custom middleware functions for authentication, validation, error handling, etc.
- **Exceptions**: Define custom exception classes to handle errors and exceptions in the application.
- **Helpers**: Contain utility functions, helper classes, and third-party integrations to assist with common tasks.
- **Config**: Store configuration settings, environment variables, and validation rules.
- **DB**: Contain data access objects (DAOs) to interact with the MongoDB database.
- **Docs**: Define Swagger documentation files for API endpoints and models.
- **DTOs**: Define data transfer objects (DTOs) to transfer data between layers and components.
- **Interfaces**: Define TypeScript interfaces for data structures, models, and API requests and responses.
- **Middlewares**: Implement custom middleware functions for authentication, validation, error handling, etc.
- **Routes**: Define API endpoints, route requests to controllers, and handle HTTP methods.
- **Services**: Contain business logic, interact with the database, and perform operations on data.
- **Sockets**: Implement real-time communication between clients and servers using WebSockets.
- **Types**: Define custom TypeScript types, interfaces, and declarations for better type safety and code quality.
<!--

## Error Handling 🚨

The backend architecture of `fixflex` includes a robust error handling mechanism to catch and handle exceptions gracefully, providing informative error messages, status codes, and error responses to clients. The error handling mechanism includes the following key features:

- `Custom Exceptions`: Defines custom exception classes to handle errors and exceptions in the application, providing detailed error messages and status codes.
- `Error Middleware`: Implements error middleware functions to catch and handle exceptions, log errors, and send error responses to clients.
- `Global Error Handling`: Centralizes error handling logic in a global error handler middleware to ensure consistent error responses across the application.
- `Error Logging`: Logs errors and exceptions to track application behavior, monitor performance, and debug issues effectively.
- `Error Response Format`: Standardizes error responses with a consistent format, including status codes, error messages, error details, and stack traces. -->

---

## Chapter 5: Testing

### 5.1 Unit & Integration Testing

![Screenshot 2024-05-31 204309](https://github.com/fixflex/backend/assets/124518625/9dded167-f93e-4948-8aa5-49617f7c3889)
![Screenshot 2024-05-31 204333](https://github.com/fixflex/backend/assets/124518625/2ea07ee6-1197-4838-9132-c8d2afb3b18d)
![Screenshot 2024-05-31 204406](https://github.com/fixflex/backend/assets/124518625/6b52933d-29ee-4643-8a82-afb112e1134f)
![Screenshot 2024-05-31 204429](https://github.com/fixflex/backend/assets/124518625/3b43a4d0-d118-4ff2-9f46-ee049b907ba0)
![Screenshot 2024-05-31 204449](https://github.com/fixflex/backend/assets/124518625/4e065708-966f-43c4-8318-992778cdaab0)
![Screenshot 2024-05-31 204509](https://github.com/fixflex/backend/assets/124518625/a2422030-a6b8-4f89-9b18-6618782873f8)
![Screenshot 2024-05-31 204537](https://github.com/fixflex/backend/assets/124518625/d0bddf6e-e1bd-413b-8f84-ebf7ae22c59c)
![Screenshot 2024-05-31 204632](https://github.com/fixflex/backend/assets/124518625/2b8ce811-10a2-4223-85e3-87e8dec38f51)
![Screenshot 2024-05-31 204659](https://github.com/fixflex/backend/assets/124518625/1f7d5275-7ae8-40e2-b118-957c14b58ac2)

### 5.2 Bug Reports

---

## Chapter 6: Result

### 6.1 Expected Results

The FixFlex platform is expected to:

- Provide an inclusive, user-friendly platform connecting task posters with skilled taskers.
- Offer a wide range of categories for various tasks and services.
- Ensure high standards of quality and reliability through a robust system of ratings and reviews.
- Facilitate secure and straightforward payment transactions.
- Enhance accessibility with mobile applications for both iOS and Android devices.
- Foster a supportive community where users can share experiences and grow together.

### 6.2 Actual Results

The actual results of the FixFlex platform will be evaluated based on the following criteria:

- User feedback on the ease of use and functionality of the platform.
- The number of successful task completions and user engagements.
- The effectiveness of the rating and review system in maintaining service quality.
- User satisfaction with payment security and transaction processes.
- The adoption rate of the mobile applications among users.
- The level of community engagement and support fostered by the platform.

---

## Chapter 7: Conclusion

### 7.1 Conclusion

In conclusion, the FixFlex platform represents a significant advancement in connecting individuals seeking various task services with skilled professionals ready to offer their expertise. By prioritizing accessibility, reliability, and community support, FixFlex aims to become a go-to solution for everyday tasks and services.

We extend our heartfelt gratitude to Dr. Helal Ahmed, our esteemed supervisor, for his invaluable guidance and support throughout our graduation project. His insights and encouragement have been instrumental in the successful development and implementation of FixFlex.
