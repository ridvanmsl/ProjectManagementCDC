# ProjectManagementCDC
CDC DATA REPLICATION
Project Definition:
This project aims to implement a real-time data replication system that captures changes in a SQL database, processes these changes, and transfers them to another database. Essentially, it involves capturing changes in a SQL database through debezium, transmitting them via Kafka using AKHQ, processing them using Apache Flink written in Java, and ultimately performing a sink operation to transfer the processed data to another database.

Purpose:
The purpose of this project is to facilitate stream processing and ensure consistency between different databases. Any change (create, update, delete) in the database will be instantly captured, processed using Apache Flink, and securely transferred to another database. This is intended to enhance cross-system integration and ensure data integrity.

Team Members:
Arman Yaycı: Apache Flink UI Configuration and Code development
İsa Şengül: AKHQ, Kafka Configuration
Rıdvan Musaoğlu: Docker Environment
Yiğit Bayramlı: Source and Target Database Configurations

Estimated Budget:
The estimated budget for this project will be determined based on various factors, including the scope of the implementation, technology costs, and potential challenges. The budget will cover the following key areas:
Technology Infrastructure:
Costs associated with acquiring or utilizing the necessary software and tools (Debezium, Kafka, Apache Flink).
Licensing fees for proprietary software, if applicable.
Hardware requirements for hosting the systems.
Development and Coding:
Compensation for developers, especially those skilled in Java for Apache Flink development.
Costs for code review and quality assurance processes.

Testing:
Resources for testing tools and frameworks.
Potential costs associated with testing environments and data.
Security Measures:
Investments in security protocols and tools to ensure secure data transfer.
Potential costs for security audits or assessments.
Training and Documentation:
Costs associated with training team members on new technologies and processes.
Documentation tools and resources.
Contingency:
A contingency budget to account for unforeseen challenges or changes in project scope.
Project Management:
Resources for project management tools and software.
Compensation for project managers overseeing the implementation.

Major MileStones and Target Dates
Project Initiation (Week 1):
Define project scope, objectives, and requirements.
Form project team and assign roles and responsibilities.
Infrastructure Setup (Week 2-3):
Acquire and configure necessary hardware for hosting.
Install and set up debezium, Kafka, and Apache Flink.
Development Phase (Week 4-5-6):
Develop Java code for Apache Flink.
Integrate debezium and Kafka for real-time data capture.
Implement mapping and transformation logic for data processing.
Testing and Quality Assurance (Week 7-8):
Conduct unit testing of individual components.
Perform integration testing to ensure seamless system functionality.

Security Implementation (Week 9 ):
Integrate security measures for data transfer.
Conduct security testing and address any vulnerabilities.
Deployment and Closure (Week 10):
Deploy the system to the production environment.
Monitor and optimize system performance.
Conduct a final project review, document lessons learned, and close the project.

Success Criteria of Project & Product:
Real-Time Data Replication:
Project: Capture and transmit changes promptly.
Product: Achieve near real-time data replication without delays.
Data Integrity and Consistency:
Project & Product: Ensure replicated data maintains integrity and consistency across databases.
Performance, Security, and User Satisfaction:
Project & Product: Optimize system performance for high data volumes, implement robust security measures, and prioritize user satisfaction through effective training and adoption.

Risks
Data Inconsistency and Loss:
Description: Inadequate handling of simultaneous transactions may lead to data inconsistency or loss during replication.
Mitigation: Implement robust transaction management mechanisms and conduct thorough testing.
Performance Bottlenecks:
Description: High data volumes may cause performance bottlenecks, impacting the real-time nature of data replication.
Mitigation: Conduct performance testing, optimize code, and scale infrastructure as needed.



Constraints:
Technological Limitations: Consideration must be given to the limitations of the technologies used (debezium, Kafka, Apache Flink).
Budgetary Constraints: The project may be constrained by a limited budget, requiring cost-effective solutions.

Dependencies:
Debezium and Kafka Integration: Debezium and Kafka need to be integrated correctly.
Apache Flink Installation: Apache Flink must be properly installed and configured.
Java Coding Skills: Proficiency in Java is required for developing the Java code that will run on Flink.
Database Connections: Reliable and fast connections to the relevant databases must be established.

Technologies for Software Development:
Programming Language: Java for Apache Flink development.
Change Data Capture (CDC): Debezium for capturing changes in the SQL database.
Message Broker: Apache Kafka for real-time data streaming and messaging.
Data Processing: Apache Flink for processing and analyzing streaming data.
Database Connectivity: JDBC for connecting to SQL databases.

Communicaon channels of team members:
1-Jira
2-Github
3-Confluence

Stakeholders
1-Musaoğulları Ltd.şti
2-Çamoluk otomotiv anonim şti.
3-Şengül Motors
