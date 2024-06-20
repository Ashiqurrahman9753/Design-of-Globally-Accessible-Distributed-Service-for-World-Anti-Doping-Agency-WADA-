# Design-of-Globally-Accessible-Distributed-Service-for-World-Anti-Doping-Agency-WADA-
#WADA Athlete Location Tracking System
#Overview
This project outlines the design for a globally accessible distributed system for the World Anti-Doping Agency (WADA) to track the whereabouts of athletes. The system aims to provide a secure and scalable platform for athletes to submit their location information, and for Anti-Doping Organizations (ADOs) to access and verify this data efficiently.

#Project Status
Note: This project is currently in the design phase. The full design report is available in the repository.

#Features
Athlete Registration: Securely collect personal details and set up authentication.
Location Submission: Athletes submit their location at specific intervals.
Location Access: ADOs access athlete location data for compliance checks.
Reporting and Analytics: Tools for monitoring compliance and detecting patterns.
Profile Management: Athletes update their profile information.
System Administration: Superusers manage system operations and user permissions.
#Technologies
API Gateway: Manages API requests and responses.
AWS Lambda: Handles stateless functions and rapid scaling.
Amazon RDS: Provides relational database services with ACID compliance.
Amazon DynamoDB: Supports non-relational data storage.
Kubernetes: Manages containerized applications for horizontal scaling.
AWS CloudWatch: Monitors system performance and health.
API Endpoints
Register Athlete API: POST /api/athletes/register
Location Submission API: POST /api/locations/submit
Location Query API: GET /api/locations/query
Analytics and Reporting API: GET /api/reports/generate
Profile Management API: PUT /api/athletes/update
System Administration API: POST /api/admin/operations
Security and Compliance
Secure API Protocols: HTTPS for secure connections.
Data Encryption: Data at rest and in transit encryption using AWS services.
User Authentication: Managed with AWS Cognito.
GDPR Compliance: Ensures data privacy and user consent mechanisms.
#Documentation
For a detailed view of the design and implementation plan, please refer to the Design Report in this repository.
