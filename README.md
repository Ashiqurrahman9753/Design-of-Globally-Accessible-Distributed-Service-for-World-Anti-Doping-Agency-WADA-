# Design of Globally Accessible Distributed Service for World Anti Doping Agency WADA
An AWS-native distributed system designed for tracking athlete whereabouts with a focus on high availability, scalability, and system resilience.

🚀 Performance Benchmarks
Designed to meet strict global operational standards:

Throughput: 1,000+ requests per second.

Response Time: <2 seconds for location submissions.

Concurrency: Supports 10,000 concurrent users without performance degradation.

Availability: 99.9% uptime using multi-region AWS failover.

🛠 Tech Stack & Infrastructure
Compute: AWS Lambda (stateless processing) & Amazon EKS (Kubernetes).

Database: Amazon RDS (ACID-compliant relational data) & DynamoDB (high-performance NoSQL).

Networking: Amazon Route 53 (geolocation routing) & CloudFront (CDN).

Security: AWS Cognito for athlete/ADO authentication and GDPR-compliant data handling.

🏗 System Architecture
Detailed description of the serverless and containerized hybrid model.

🛡 Failure & Resilience Model
The architecture is designed for "Self-Healing":

Auto-Recovery: EC2 instances automatically reboot or migrate on failure.

Multi-Region Failover: Real-time data replication across 3+ geographic regions.

Observability: Unified logging and real-time monitoring via AWS CloudWatch.

