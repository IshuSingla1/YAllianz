# YAllianz eClaims System

This repository houses the microservices for YCompany's eClaims System, a comprehensive platform designed to streamline the auto insurance claim processing experience for customers, adjusters, surveyors, and third-party partners (workshops and car rentals).

## Project Overview

**Microservices Architecture:** The system is built on a modular microservices architecture, promoting scalability, maintainability, and independent deployment of functionalities.

**Technologies (Replace with your actual choices):** While specific technologies aren't mentioned here, the system likely leverages technologies like Spring Boot, Java, Oracle DB, React, AWS, Elasticsearch, and Redis.

**Deployment:** The microservices are intended to be deployed on AWS Cloud using Elastic Kubernetes Service (EKS), taking advantage of Kubernetes features.

## Microservices
The system is composed of the following microservices, each with its dedicated functionalities:

1. **Customer Portal Service:** Manages customer login, profile information, claim submissions, and status updates.
2. **Incident Management Service:** Assigns claims to adjusters and surveyors based on location and availability.
3. **Surveyor Service:** Handles surveyor data and allows submission of damage assessments.
4. **Adjuster Service:** Manages adjuster data, enables claim valuation, and facilitates approval.
5. **Third-Party Service:** Manages workshop and car rental partner data, allowing work order submissions and status updates.
6. **Payment Service:** Processes customer payments for claim repairs.
7. **Reporting Service:** Generates reports on various aspects of claims processing (processing time, amount paid, etc.), with role-based access control for different reports.
8. **Document Management Service:** Stores and archives all claim documents for auditing and compliance purposes.
9. **Notification Service:** Triggers alerts and notifications to relevant parties (customers, adjusters, etc.) when claim status changes occur.


## Contribution Guidelines
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Implement your changes and write unit tests.
- Submit a pull request for review.


## Disclaimer
This README provides a general overview. Specific implementation details, configurations, and technology choices will vary based on your project's requirements.
