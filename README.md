# Engineering Prompts


Welcome to the *Engineering Prompts* repository! This repository contains a collection of *AI prompt chains* organized by different domains, primarily for assisting developers in various tasks such as code refactoring, CI/CD setup, database management, cloud, Kubernetes deployment, web development, API Development, security, and more.

Each prompt chain is designed to build con text for ChatGPT before executing a task. They can be used in *ChatGPT Queue* for bulk prompting, job, or task-focused automation.

## Domains Covered

This repository contains prompt chains for the following domains:


1. *Code Refactoring & Development*
2. *CI/CD & DevOps*
3. *Database Management*
4. *Cloud & Kubernetes*
5. *Full-Stack Development*
6. *UX/UI & Design*
7. *Security & Authentication*
8. *Event-Driven Architecture & Integration*
9. *Content Creation & Marketing*
10. *Infrastructure & System Administration*
11. *System Monitoring & Debugging*
12. *Web Development*
13. *API Development*
14. *Mobile Development*
15. *Machine Learning & AI*
16. *Data Engineering & Analytics*
17. *Performance Optimization*
18. *Quality Assurance & Testing*
19. *Blockchain & Web3*
20. *IoT & Embedded Systems*
21. *Game Development*
22. *Legacy System Modernization*

---

## Use Cases and Prompts


### *1. Code Refactoring & Development*

* *Refactor Code for Better Readability*

   ```text
  Please review the provided code and identify areas where readability can be improved. Focus on simplifying complex functions, improving variable names, and removing redundant code. Return the refactored code and explain the changes made to improve readability.```
  

* *Translate Code from One Language to Another*

  ```text
Translate the provided code from {source_language} to {target_language}. Ensure that the functionality remains equivalent. Highlight major differences in syntax or constructs between the two languages and explain the changes.```
  

* *Create Documentation from Code*

  ```text
Extract the necessary information from the provided code to create detailed documentation. This should include explanations for functions, methods, classes, and the purpose of the code. Return the documentation in markdown format.```
  

* *Provide Code Explanations*

  ```text
 Please analyze the provided code and explain its functionality step-by-step. Include explanations for each major part of the code and why it's necessary. Keep the explanation clear and concise.```
  

* *Generate Git Commit Messages*

  ```text
  Based on the code changes, generate concise and meaningful Git commit messages. Ensure the messages describe what was changed and why, and follow conventional commit standards.```
  

* *Debug Code*

  ```text
 Please review the provided code and the accompanying error message. Identify the cause of the error, suggest possible fixes, and return the corrected code with explanations of the changes made.```
  

* *Write Regular Expressions*

  ```text
 Create a regular expression for {use_case}. For example, to validate email addresses, generate a regex that matches valid email formats. Return the regular expression and explain how it works.```
  

* *Generate Boilerplate Code*

  ```text
 Generate boilerplate code for a {project_type} using {programming_language}. The code should include basic setup, functions, and structure for a starting point. Return the full code with instructions for customization.```
  

* *Automate Code Formatting*

  ```text
 Set up an automatic code formatting system using {tool}. Configure it to run on each commit or via pre-commit hooks. Return the necessary configuration and explain how it integrates into the workflow.```
  

* *Explain Data Structures and Algorithms*

  ```text
  Explain the following data structure/algorithm: {data_structure/algorithm}. Include its time complexity, use cases, and any common implementations. Provide code examples where applicable.```
  

* *Generate Mock Data*

  ```text
  Generate mock data for the following schema: {data_schema}. Include a variety of realistic values for testing purposes. Return the data in JSON, CSV, or another format as requested.```
  

* *Create Code for a New Feature*

  ```text
Please create code to implement the following feature: {feature_description}. The feature should be fully functional and integrate smoothly with the existing codebase. Return the implementation along with an explanation.```
  

* *Suggest Performance Optimizations*

  ```text
 Analyze the provided code for performance bottlenecks. Suggest optimizations such as reducing time complexity, memory usage, or optimizing algorithms. Return the updated code with explanations of the optimizations.```
  

* *Generate Build Scripts*

  ```text
  Create a build script for automating the build process of a {project_type} using {build_tool}. The script should include steps for compiling, packaging, and versioning. Return the build script along with setup instructions.```
  

* *Offer Security Best Practices*

  ```text
 Provide a list of security best practices for {application_type}. Focus on areas like authentication, authorization, data protection, and secure coding practices. Return actionable advice with examples where necessary.```
  

* *Assist in Code Reviews*

  ```text
 Review the provided code and provide feedback. Focus on aspects like readability, performance, security, and maintainability. Suggest improvements and explain the rationale behind each recommendation.```
  

* *Test for Compatibility After Upgrading Node.js Version*

  ```text
  After upgrading Node.js from version 14 to 18, use Keploy to run automated tests to ensure that the application is working as expected. Set up Keploy to perform integration tests and verify that the backend, APIs, and frontend components are compatible with the new Node.js version. The tests should focus on key areas such as API responses, performance, and compatibility with external dependencies that may have been affected by the Node.js upgrade. Ensure that Keploy compares the results with the previous behavior recorded under Node.js 14 to detect any regressions or issues introduced by the upgrade. Return the Keploy test configuration, test cases, and results.```
  

* *Integrate Third-Party Services*

  ```text
Integrate {third_party_service} into the existing project. Provide step-by-step instructions for setup, authentication, and API interaction. Return the integration code with explanations of how it works.```
  

* *Write a Dockerfile for the Application*

  ```text
 Create a Dockerfile to containerize the provided application. Ensure that the Dockerfile sets up the environment correctly, installs dependencies, and exposes the necessary ports. Return the Dockerfile with explanations.```
  

* *Provide UX/UI Design Advice*

  ```text
Provide UX/UI design recommendations for the provided {website/app}. Focus on improving usability, accessibility, and aesthetics. Return a list of specific design improvements with examples where necessary.```
  

* *Suggest Testing Strategies*

  ```text
 Suggest a comprehensive testing strategy for {project_type}. The strategy should include unit tests, integration tests, and end-to-end tests. Provide recommendations for testing frameworks and tools, along with examples.```
  

* *Test for Regressions After Refactoring Code with Keploy*

  ```text
 After refactoring the code, use Keploy to run automated tests to check if any regressions have been introduced. Set up Keploy to verify that the refactored code behaves as expected, ensuring that all existing functionalities remain intact. The tests should include integration tests to verify that API endpoints, data handling, and user interactions still function properly. Ensure that Keploy is set to compare the current behavior with previously recorded test cases to detect any discrepancies or regressions. Return the Keploy test configuration, test cases, and results showing the behavior of the refactored code.```
  

* *Generate Design Patterns Implementation*

  ```text
 Implement the {design_pattern} pattern in {programming_language} for the following use case: {use_case_description}. Provide a complete implementation with explanations of how the pattern solves the problem and when to use it.```
  

* *Create Code Metrics Dashboard*

  ```text
 Set up a code metrics dashboard using tools like SonarQube or CodeClimate. Configure it to track code quality metrics such as cyclomatic complexity, code coverage, and technical debt. Return the configuration and setup instructions.```
  

* *Implement Error Handling Strategies*

  ```text
  Implement comprehensive error handling for the provided code in {programming_language}. Include try-catch blocks, custom error classes, logging, and user-friendly error messages. Return the enhanced code with error handling explanations.```
  

---

### *2. CI/CD & DevOps*

* *Set up CI/CD Pipelines*

  ```text
Help set up a CI/CD pipeline for the project using {CI_tool}. The pipeline should include stages for building, testing, and deploying the application. Provide configuration files and explanations of each stage.```
  

* *Automate Code Formatting*

  ```text
  ```Set up an automated code formatting system using {tool}. Configure it to run on each commit or via pre-commit hooks. Return the necessary configuration and explain how it integrates into the workflow.```
  

* *Set up Cloud Cost Optimization Strategies*

  ```text
  ```Provide strategies for optimizing cloud costs in {cloud_provider}. Focus on areas like reserved instances, auto-scaling, and rightsizing. Return recommendations and examples of how to implement them.```
  

* *Create Docker Compose Configurations*

  ```text
  ```Create a Docker Compose configuration file to set up {services}. The configuration should include service dependencies, environment variables, and port mappings. Return the Docker Compose YAML with an explanation.```
  

* *Generate Cron Jobs for Task Scheduling*

  ```text
  ```Write cron jobs to schedule tasks on a Linux system. The tasks should run at {interval} and execute {command}. Return the cron job configurations with explanations of each field.```
  

* *Implement Automated Security Testing in CI/CD*

  ```text
  ```Integrate automated security testing tools like {security_tool} into the CI/CD pipeline. Configure the pipeline to run security checks on each commit or pull request. Return the updated pipeline configuration.```
  

* *Set up Serverless Architecture with Google Cloud Functions*

  ```text
  ```Create a serverless architecture using Google Cloud Functions for {task}. The functions should trigger based on specific events and return the necessary code with setup instructions.```
  

* *Write Infrastructure as Code (IaC) for AWS with CloudFormation*

  ```text
  ```Write infrastructure-as-code (IaC) for AWS using CloudFormation. Automate the provisioning of resources such as EC2, RDS, and S3 for {application}. Return the CloudFormation templates with explanations.```
  

* *Create a Custom Shell Script for System Administration*

  ```text
  ```Create a custom shell script that automates {system_task} such as backups, log rotations, or user management. The script should be efficient and handle errors gracefully. Return the shell script with usage instructions.```
  

* *Create an Event-Driven Architecture with Kafka*

  ```text
  ```Set up an event-driven architecture with Kafka. Define the Kafka topics, producers, and consumers to handle real-time data processing. Return the code with configuration details.```
  

* *Implement Data Preprocessing for Machine Learning*

  ```text
  ```Implement data preprocessing steps for machine learning. This includes handling missing data, scaling features, and encoding categorical variables. Return the preprocessing code and explain each step.```
  

* *Implement Serverless Functions on AWS Lambda*

  ```text
  ```Set up serverless functions using AWS Lambda to perform {task}. Include setup instructions for the trigger and return the Lambda function code.```
  

* *Set up Google Analytics for Portfolio Tracking*

  ```text
  ```Set up Google Analytics tracking for my portfolio website. Provide the steps for adding tracking code and configuring goals. Return the setup instructions.```
  

* *Optimize a Docker-Based Development Environment*

  ```text
  ```Optimize the provided Docker development environment. Focus on reducing build time, improving caching, and streamlining container configurations. Return the optimized Dockerfile and Docker Compose file.```
  

* *Implement Blue-Green Deployment Strategy*

  ```text
  ```Design and implement a blue-green deployment strategy for {application} using {deployment_tool}. Include scripts for traffic switching, rollback procedures, and health checks. Return the deployment configuration and scripts.```
  

* *Set up Multi-Environment Configuration Management*

  ```text
  ```Create a configuration management system for multiple environments (dev, staging, prod) using {config_tool}. Include environment-specific variables, secrets management, and configuration validation. Return the setup configuration.```
  

* *Implement GitOps Workflow with ArgoCD*

  ```text
  ```Set up a GitOps workflow using ArgoCD for continuous deployment. Configure ArgoCD to sync with Git repositories and automatically deploy changes to Kubernetes clusters. Return the ArgoCD configuration and Git repository structure.```
  

* *Create Monitoring and Alerting with Prometheus and Grafana*

  ```text
  ```Set up monitoring and alerting for {application} using Prometheus and Grafana. Include custom metrics, alerting rules, and dashboard configurations. Return the complete monitoring stack setup.```
  

---

### *3. Database Management*

* *Generate SQL Queries*

  ```text
  ```Given the database schema and the following requirements (e.g., 'Find all users who joined after 2020'), generate an appropriate SQL query. Return the SQL query and explain its logic.```
  

* *Explain Database Design*

  ```text
  ```Please review the database schema provided and explain its design choices. Discuss normalization, relationships between tables, and indexing strategies. Suggest improvements for scalability and performance.```
  

* *Design a Normalized Relational Database Schema*

  ```text
  ```Design a relational database schema for {application}. Ensure that it is normalized up to 3NF, with proper primary/foreign keys and indexes. Return the schema in SQL format.```
  

* *Set Up a PostgreSQL Database with Docker*

  ```text
  ```Set up a PostgreSQL database in a Docker container. Include steps for configuring the database, creating the schema, and connecting to the container. Return the Dockerfile and Docker Compose configuration.```
  

* *Implement Database Sharding*

  ```text
  ```Implement database sharding for {database_name}. Define the sharding strategy and partition the data across multiple shards. Return the setup and configuration details.```
  

* *Create and Optimize a NoSQL Database (MongoDB)*

  ```text
  ```Set up and optimize a MongoDB database for {application}. Include recommendations for indexing, query optimization, and data modeling. Return the schema and optimization steps.```
  

* *Optimize Database Queries for Performance*

  ```text
  ```Analyze the provided database queries and suggest performance optimizations. This may include indexing, query refactoring, and reducing the complexity of joins. Return the optimized query with explanations.```
  

* *Implement Multi-Threading and Concurrency Concepts*

  ```text
  ```Explain the concepts of multi-threading and concurrency in {programming_language}. Focus on thread management, race conditions, and synchronization techniques. Provide code examples where applicable.```
  

* *Design Database Migration Strategy*

  ```text
  ```Create a database migration strategy for transitioning from {old_database} to {new_database}. Include data migration scripts, rollback procedures, and zero-downtime migration techniques. Return the migration plan and scripts.```
  

* *Implement Database Connection Pooling*

  ```text
  ```Set up database connection pooling for {application} using {connection_pool_library}. Configure optimal pool sizes, connection timeouts, and error handling. Return the configuration and implementation code.```
  

* *Create Database Backup and Recovery Procedures*

  ```text
  ```Design automated database backup and recovery procedures for {database_system}. Include incremental backups, point-in-time recovery, and disaster recovery plans. Return the backup scripts and recovery procedures.```
  

* *Implement Database Replication Setup*

  ```text
  ```Set up database replication for {database_system} with master-slave configuration. Include failover mechanisms, read replica setup, and data consistency checks. Return the replication configuration and monitoring setup.```
  

---

### *4. Cloud & Kubernetes*

* *Set Up Kubernetes Cluster on AWS EKS*

  ```text
  ```Please guide the setup of a Kubernetes cluster using Amazon EKS. Include steps for configuring the cluster, setting up node groups, and connecting kubectl. Return the steps and configuration files.```
  

* *Implement Persistent Storage in Kubernetes Using StatefulSets*

  ```text
  ```Set up persistent storage in Kubernetes using StatefulSets. Configure PersistentVolumeClaims (PVC) and explain how it ensures data persistence. Return the YAML configuration files.```
  

* *Set Up Cloud Storage with Amazon S3*

  ```text
  ```Please provide the steps for setting up cloud storage using Amazon S3. Include how to create a bucket, set permissions, and manage files programmatically via AWS SDKs. Return the necessary code examples for integration.```
  

* *Implement Kubernetes Autoscaling*

  ```text
  ```Set up Horizontal Pod Autoscaler (HPA) and Vertical Pod Autoscaler (VPA) in Kubernetes. Configure scaling policies based on CPU, memory, and custom metrics. Return the autoscaling configuration files.```
  

* *Create Kubernetes Ingress Controller Setup*

  ```text
  ```Configure an Ingress controller in Kubernetes using {ingress_controller}. Set up SSL termination, load balancing, and routing rules for multiple services. Return the Ingress configuration and setup instructions.```
  

* *Implement Kubernetes Secrets and ConfigMaps Management*

  ```text
  ```Set up secrets and ConfigMaps management in Kubernetes. Include encryption at rest, secret rotation, and best practices for sensitive data handling. Return the configuration files and management scripts.```
  

* *Design Multi-Cloud Architecture Strategy*

  ```text
  ```Design a multi-cloud architecture strategy using {cloud_providers}. Include data replication, failover mechanisms, and cost optimization across different cloud platforms. Return the architecture design and implementation plan.```
  

---

### *5. Full-Stack Development*

* *Develop a Full-Stack Web Application Using Django and React*

  ```text
  ```Create a full-stack web application with Django as the backend and React for the frontend. Implement user authentication, RESTful API communication, and a simple CRUD interface. Return the project structure and code snippets.```
  

* *Integrate a Payment Gateway (Stripe) in a Full-Stack App*

  ```text
  ```Integrate Stripe for handling payments in a full-stack application with Django and React. Set up the backend to handle payments and the frontend to interact with Stripe's API. Return the code for integration.```
  

* *Create a RESTful API with Express.js*

  ```text
  ```Help me set up a RESTful API using Express.js. Define the necessary routes and controllers to support CRUD operations for a {resource}. Return the implementation of the API with explanations for each endpoint.```
  

* *Implement Real-Time Updates with WebSockets*

  ```text
  ```Set up real-time updates in the application using WebSockets. Provide the necessary code for both the server (using socket.io or similar) and the frontend to enable live updates.```
  

* *Test Backend and Frontend for Regression Using Keploy*

  ```text
  ```Set up Keploy in your full-stack application to test both the backend and frontend after an update. Configure Keploy for automatic integration testing, focusing on testing API endpoints, data handling, and the interaction between the frontend and backend. Ensure that Keploy is set to capture all changes in the API response, including edge cases, and validate that the frontend works correctly with the updated backend. Return the setup configuration and steps to trigger Keploy for testing.```
  

* *Implement Server-Side Rendering with Next.js*

  ```text
  ```Set up server-side rendering (SSR) for a React application using Next.js. Include dynamic routing, API routes, and optimization for SEO. Return the Next.js configuration and example pages.```
  

* *Create GraphQL API with Apollo Server*

  ```text
  ```Implement a GraphQL API using Apollo Server for {application}. Define schemas, resolvers, and mutations for CRUD operations. Include authentication and error handling. Return the complete GraphQL implementation.```
  

* *Implement Microservices Architecture*

  ```text
  ```Design and implement a microservices architecture for {application}. Include service discovery, API gateway, inter-service communication, and data consistency patterns. Return the architecture design and implementation.```
  

---

### *6. UX/UI & Design*

* *Provide UX/UI Design Advice*

  ```text
  ```Provide UX/UI design recommendations for the provided {website/app}. Focus on improving usability, accessibility, and aesthetics. Return a list of specific design improvements with examples where necessary.```
  

* *Create Responsive Design System*

  ```text
  ```Design a comprehensive design system for {application} including color palette, typography, component library, and responsive breakpoints. Return the design system documentation and CSS/styled-components implementation.```
  

* *Implement Accessibility (A11y) Improvements*

  ```text
  ```Audit the provided {website/application} for accessibility compliance and implement WCAG 2.1 AA standards. Include ARIA labels, keyboard navigation, screen reader compatibility, and color contrast improvements. Return the accessibility implementation and testing checklist.```
  

* *Design Progressive Web App (PWA) Features*

  ```text
  ```Convert the existing web application into a Progressive Web App (PWA). Implement service workers, offline functionality, push notifications, and app manifest. Return the PWA implementation and configuration files.```
  

---

### *7. Security & Authentication*

* *Offer Security Best Practices*

  ```text
  ```Provide a list of security best practices for {application_type}. Focus on areas like authentication, authorization, data protection, and secure coding practices. Return actionable advice with examples where necessary.```
  

* *Implement JWT-Based Authentication*

  ```text
  ```Implement JSON Web Token (JWT) authentication in the provided application. The system should handle token generation, validation, and secure access to protected routes. Return the code with explanations.```
  

* *Implement OAuth 2.0 with Social Login*

  ```text
  ```Set up OAuth 2.0 authentication with social login providers (Google, Facebook, GitHub) for {application}. Include token validation, user profile management, and security best practices. Return the implementation code.```
  

* *Perform Security Vulnerability Assessment*

  ```text
  ```Conduct a security vulnerability assessment of the provided application. Check for common vulnerabilities like SQL injection, XSS, CSRF, and insecure dependencies. Return a security report with remediation recommendations.```
  

* *Implement Rate Limiting and DDoS Protection*

  ```text
  ```Implement rate limiting and DDoS protection for {application} using {rate_limiting_tool}. Configure request throttling, IP blocking, and monitoring. Return the security configuration and implementation.```
  

* *Set up Web Application Firewall (WAF)*

  ```text
  ```Configure a Web Application Firewall (WAF) for {application} using {WAF_provider}. Set up rules for common attacks, custom filtering, and monitoring. Return the WAF configuration and security policies.```
  

---

### *8. Event-Driven Architecture & Integration*

* *Set Up an Event-Driven Architecture with Kafka*

  ```text
  ```Set up an event-driven architecture with Kafka. Define the Kafka topics, producers, and consumers to handle real-time data processing. Return the code with configuration details.```
  

* *Help Integrate Third-Party Services*

  ```text
  ```Integrate {third_party_service} into the existing project. Provide step-by-step instructions for setup, authentication, and API interaction. Return the integration code with explanations of how it works.```
  

* *Implement Event Sourcing Pattern*

  ```text
  ```Implement event sourcing pattern for {application} using {event_store}. Design event schemas, aggregate handling, and event replay mechanisms. Return the event sourcing implementation and configuration.```
  

* *Create Message Queue System with RabbitMQ*

  ```text
  ```Set up a message queue system using RabbitMQ for {use_case}. Configure exchanges, queues, routing keys, and dead letter queues. Return the RabbitMQ setup and producer/consumer code.```
  

---

### *9. Content Creation & Marketing*

* *Create a Personal Portfolio Website*

  ```text
  ```Help me build a personal portfolio website. The site should include sections for my bio, projects, skills, and contact information. Make sure it's responsive and easy to navigate. Return the basic HTML/CSS/JS code for the website.```
  

* *Write SEO-Optimized Blog Content*

  ```text
  ```Generate a blog post on {topic} optimized for SEO. Use keyword research to include high-traffic keywords naturally, structure the post with headings and subheadings, and ensure it is engaging and informative. Return the content with SEO suggestions.```
  

* *Generate LinkedIn Summary and Job Descriptions*

  ```text
  ```Generate a compelling LinkedIn summary and job description based on the following details: {job_title}, {skills}, {experience}. Ensure the summary is concise, professional, and highlights key achievements.```
  

* *Create Technical Documentation Website*

  ```text
  ```Build a technical documentation website using {documentation_tool} for {project}. Include API documentation, tutorials, code examples, and search functionality. Return the documentation structure and configuration.```
  

* *Implement Content Management System (CMS)*

  ```text
  ```Set up a content management system using {CMS_platform} for {website_type}. Configure custom content types, user roles, and publishing workflows. Return the CMS setup and customization code.```
  

---

### *10. Infrastructure & System Administration*

* *Create an Infrastructure as Code (IaC) for AWS with CloudFormation*

  ```text
  ```Write infrastructure-as-code (IaC) for AWS using CloudFormation. Automate the provisioning of resources such as EC2, RDS, and S3 for {application}. Return the CloudFormation templates with explanations.```
  

* *Set Up Serverless Architecture with Google Cloud Functions*

  ```text
  ```Create a serverless architecture using Google Cloud Functions for {task}. The functions should trigger based on specific events and return the necessary code with setup instructions.```
  

* *Implement Infrastructure Monitoring with Terraform*

  ```text
  ```Create Terraform configurations for provisioning and monitoring infrastructure on {cloud_provider}. Include resource monitoring, alerting, and cost tracking. Return the Terraform modules and monitoring setup.```
  

* *Set up Load Balancer Configuration*

  ```text
  ```Configure load balancers for {application} using {load_balancer_type}. Set up health checks, SSL termination, and traffic distribution algorithms. Return the load balancer configuration and setup instructions.```
  

---

### *11. System Monitoring & Debugging*

* *Debug Performance Issues in Production Systems*

  ```text
  ```Analyze the performance of the production system and identify bottlenecks. Suggest and implement optimizations to improve speed, reduce memory usage, and increase scalability. Return the optimized code and explanations.```
  

* *Set up Application Performance Monitoring (APM)*

  ```text
  ```Implement application performance monitoring using {APM_tool} for {application}. Configure performance metrics, error tracking, and alerting. Return the APM setup and dashboard configuration.```
  

* *Create Log Aggregation and Analysis System*

  ```text
  ```Set up log aggregation and analysis using {logging_stack} (e.g., ELK Stack). Configure log parsing, indexing, and visualization dashboards. Return the logging infrastructure setup and configuration.```
  

* *Implement Distributed Tracing*

  ```text
  ```Set up distributed tracing for microservices using {tracing_tool} (e.g., Jaeger, Zipkin). Configure trace collection, analysis, and performance monitoring across services. Return the tracing implementation and configuration.```
  

---

### *12. Web Development*

* *Write Tests for Front-End Components*

  ```text
  ```Write unit and integration tests for the provided front-end components using {testing_framework}. Ensure the tests cover all major use cases and edge cases. Return the test code with explanations.```
  

* *Implement Advanced CSS Animations and Transitions*

  ```text
  ```Create advanced CSS animations and transitions for {website_elements}. Include keyframe animations, transform effects, and performance optimizations. Return the CSS code with explanations and examples.```
  

* *Set up Modern JavaScript Build Pipeline*

  ```text
  ```Configure a modern JavaScript build pipeline using {build_tool} (e.g., Webpack, Vite, Rollup). Include code splitting, tree shaking, and optimization plugins. Return the build configuration and setup instructions.```
  

* *Implement Web Performance Optimization*

  ```text
  ```Optimize web performance for {website/application}. Include lazy loading, image optimization, code splitting, and caching strategies. Return the optimization implementation and performance metrics.```
  

---

### *13. API Development*

* *Generate OpenAPI Schema from Source Code*

  ```text
  ```Given the following source code for a RESTful API implemented in {programming_language} with endpoints {list_of_endpoints}, generate an OpenAPI 3.0 schema that describes the API. The schema should include paths, request/response parameters, status codes, authentication methods, and other relevant details. Return the complete OpenAPI schema in YAML format.```
  

* *Generate Curl Commands for Testing OpenAPI Endpoints*

  ```text
  ```For the OpenAPI schema provided, generate ```curl``` commands to test the endpoints. Include examples for GET, POST, PUT, and DELETE requests. The ```curl``` commands should include the correct headers, body content (for POST/PUT), and any required authentication tokens (if applicable).```
  

* *Generate OpenAPI Schema for a Custom API with Source Code*

  ```text
  ```Given the following source code for an API implemented in {programming_language}, generate the OpenAPI schema for this API. The schema should cover all routes, parameters, request/response types, and status codes. Include both request body and query parameters where applicable, and provide the schema in YAML format.```
  

* *Create OpenAPI Schema and Curl Commands for a CRUD API*

  ```text
  ```Create an OpenAPI schema for a simple CRUD API with the following endpoints: ```GET /items```, ```POST /items```, ```PUT /items/{id}```, and ```DELETE /items/{id}```. Based on the schema, generate ```curl``` commands to test these endpoints with sample data, including headers and request bodies as necessary.```
  

* *Generate OpenAPI Schema for a Node.js API and Curl Examples*

  ```text
  ```Given the following source code for a Node.js API using Express, generate the corresponding OpenAPI 3.0 schema. Then, create ```curl``` commands to test each endpoint in the API, covering all HTTP methods (GET, POST, PUT, DELETE) and including sample request bodies for each method.```
  

* *Keploy CI/CD Integration Setup*

  ```text
  ```Set up a CI/CD pipeline to automatically run Keploy tests as part of the deployment process. Include configuration for GitHub Actions or Jenkins to run tests whenever new code is pushed to the repository.```
  

* *Implement API Rate Limiting and Throttling*

  ```text
  ```Implement rate limiting and throttling for {API} using {rate_limiting_library}. Configure different rate limits for different endpoints and user tiers. Return the rate limiting implementation and configuration.```
  

* *Create API Gateway Configuration*

  ```text
  ```Set up an API Gateway for microservices using {gateway_tool}. Configure routing, authentication, rate limiting, and request/response transformation. Return the gateway configuration and deployment instructions.```
  

* *Implement API Versioning Strategy*

  ```text
  ```Design and implement an API versioning strategy for {API}. Include URL versioning, header versioning, and backward compatibility handling. Return the versioning implementation and migration guide.```
  

---

### *14. Mobile Development*

* *Create React Native Cross-Platform App*

  ```text
  ```Develop a cross-platform mobile application using React Native for {app_description}. Include navigation, state management, and platform-specific optimizations. Return the app structure and key components.```
  

* *Implement Mobile App Authentication*

  ```text
  ```Implement authentication for a mobile app using {authentication_method}. Include biometric authentication, secure token storage, and session management. Return the authentication implementation for {platform}.```
  

* *Set up Mobile App Push Notifications*

  ```text
  ```Configure push notifications for a mobile app using {notification_service} (e.g., Firebase Cloud Messaging). Include notification scheduling, targeting, and analytics. Return the push notification setup and implementation.```
  

* *Optimize Mobile App Performance*

  ```text
  ```Optimize performance for a {platform} mobile app. Include memory management, rendering optimizations, and battery usage improvements. Return the optimization strategies and implementation code.```
  

* *Implement Mobile App Offline Functionality*

  ```text
  ```Implement offline functionality for a mobile app including data synchronization, offline storage, and conflict resolution. Use {offline_storage_solution} and return the offline implementation strategy and code.```
  

* *Create Mobile App CI/CD Pipeline*

  ```text
  ```Set up a CI/CD pipeline for mobile app deployment using {CI_tool}. Include automated building, testing, and deployment to app stores. Return the pipeline configuration and deployment scripts.```
  

---

### *15. Machine Learning & AI*

* *Implement Machine Learning Model Training Pipeline*

  ```text
  ```Create a machine learning pipeline for {ml_task} using {ml_framework}. Include data preprocessing, model training, validation, and hyperparameter tuning. Return the complete pipeline code and configuration.```
  

* *Deploy ML Model with REST API*

  ```text
  ```Deploy a trained machine learning model as a REST API using {deployment_framework}. Include model serving, request validation, and response formatting. Return the deployment code and API documentation.```
  

* *Implement Data Preprocessing for Machine Learning*

  ```text
  ```Implement comprehensive data preprocessing for {dataset_type}. Include data cleaning, feature engineering, encoding, and normalization. Return the preprocessing pipeline and data quality checks.```
  

* *Create MLOps Pipeline with Model Versioning*

  ```text
  ```Set up an MLOps pipeline with model versioning using {mlops_tool}. Include experiment tracking, model registry, and automated deployment. Return the MLOps configuration and workflow.```
  

* *Implement Real-time ML Inference*

  ```text
  ```Set up real-time machine learning inference for {use_case} using {streaming_platform}. Include data streaming, model serving, and result processing. Return the real-time inference implementation.```
  

* *Create AI Chatbot with Natural Language Processing*

  ```text
  ```Develop an AI chatbot using {nlp_framework} for {domain}. Include intent recognition, entity extraction, and conversation management. Return the chatbot implementation and training data structure.```
  

* *Implement Computer Vision Pipeline*

  ```text
  ```Create a computer vision pipeline for {cv_task} using {cv_framework}. Include image preprocessing, model inference, and result visualization. Return the complete computer vision solution.```
  

---

### *16. Data Engineering & Analytics*

* *Design Data Lake Architecture*

  ```text
  ```Design a data lake architecture for {organization} using {cloud_provider}. Include data ingestion, storage layers, processing engines, and governance. Return the architecture design and implementation plan.```
  

* *Create ETL Pipeline with Apache Airflow*

  ```text
  ```Build an ETL pipeline using Apache Airflow for {data_source} to {destination}. Include data extraction, transformation, validation, and scheduling. Return the Airflow DAG and pipeline configuration.```
  

* *Implement Real-time Data Streaming*

  ```text
  ```Set up real-time data streaming pipeline using {streaming_technology}. Include data ingestion, processing, and analytics. Return the streaming pipeline implementation and monitoring setup.```
  

* *Create Data Warehouse Schema Design*

  ```text
  ```Design a data warehouse schema for {business_domain} using {dimensional_modeling_approach}. Include fact tables, dimension tables, and ETL processes. Return the schema design and implementation scripts.```
  

* *Implement Data Quality Monitoring*

  ```text
  ```Set up data quality monitoring and validation for {data_pipeline}. Include data profiling, anomaly detection, and quality metrics. Return the data quality framework and monitoring dashboards.```
  

* *Create Analytics Dashboard with BI Tools*

  ```text
  ```Build analytics dashboards using {bi_tool} for {business_metrics}. Include data connections, visualizations, and interactive filtering. Return the dashboard configuration and deployment guide.```
  

---

### *17. Performance Optimization*

* *Optimize Database Query Performance*

  ```text
  ```Analyze and optimize slow database queries for {database_system}. Include query plan analysis, index optimization, and query rewriting. Return the optimized queries and performance improvements.```
  

* *Implement Application Caching Strategy*

  ```text
  ```Design and implement a caching strategy for {application} using {caching_solution}. Include cache invalidation, TTL configuration, and cache warming. Return the caching implementation and configuration.```
  

* *Optimize Frontend Bundle Size*

  ```text
  ```Optimize frontend bundle size for {web_application}. Include code splitting, tree shaking, lazy loading, and compression techniques. Return the optimization configuration and performance metrics.```
  

* *Implement CDN and Static Asset Optimization*

  ```text
  ```Set up CDN and optimize static assets for {website}. Include image optimization, minification, and cache headers configuration. Return the CDN setup and asset optimization pipeline.```
  

* *Create Performance Testing Suite*

  ```text
  ```Create a comprehensive performance testing suite for {application} using {testing_tool}. Include load testing, stress testing, and performance monitoring. Return the test scripts and reporting setup.```
  

---

### *18. Quality Assurance & Testing*

* *Implement Automated Testing Framework*

  ```text
  ```Set up an automated testing framework for {application} using {testing_framework}. Include unit tests, integration tests, and end-to-end tests. Return the testing setup and example test cases.```
  

* *Create API Testing Suite*

  ```text
  ```Develop comprehensive API testing suite for {api} using {api_testing_tool}. Include functional testing, contract testing, and performance testing. Return the test suite and execution configuration.```
  

* *Implement Visual Regression Testing*

  ```text
  ```Set up visual regression testing for {web_application} using {visual_testing_tool}. Include screenshot comparison, responsive testing, and CI integration. Return the visual testing setup and configuration.```
  

* *Create Test Data Management Strategy*

  ```text
  ```Design test data management strategy for {application}. Include test data generation, anonymization, and environment management. Return the test data framework and management tools.```
  

* *Implement Behavior-Driven Development (BDD)*

  ```text
  ```Set up Behavior-Driven Development framework using {bdd_tool} for {project}. Include feature specifications, step definitions, and test execution. Return the BDD implementation and example scenarios.```
  

---

### *19. Blockchain & Web3*

* *Create Smart Contract Development Environment*

  ```text
  ```Set up a smart contract development environment for {blockchain_platform}. Include development tools, testing framework, and deployment scripts. Return the development setup and example contracts.```
  

* *Implement DeFi Protocol Integration*

  ```text
  ```Integrate with DeFi protocols for {use_case}. Include wallet connection, transaction handling, and protocol interactions. Return the DeFi integration code and security considerations.```
  

* *Create NFT Marketplace*

  ```text
  ```Build an NFT marketplace on {blockchain_platform}. Include smart contracts, frontend interface, and IPFS integration. Return the marketplace implementation and deployment guide.```
  

* *Implement Blockchain Data Indexing*

  ```text
  ```Set up blockchain data indexing and querying using {indexing_solution}. Include event monitoring, data transformation, and API creation. Return the indexing implementation and query interface.```
  

---

### *20. IoT & Embedded Systems*

* *Create IoT Device Communication Protocol*

  ```text
  ```Implement communication protocol for IoT devices using {protocol}. Include device registration, data transmission, and security measures. Return the protocol implementation and device code.```
  

* *Set up IoT Data Pipeline*

  ```text
  ```Build IoT data pipeline for sensor data processing. Include data ingestion, real-time processing, and storage. Return the pipeline architecture and implementation code.```
  

* *Implement Edge Computing Solution*

  ```text
  ```Design edge computing solution for {iot_use_case}. Include edge device configuration, local processing, and cloud synchronization. Return the edge computing implementation and deployment guide.```
  

* *Create IoT Device Management System*

  ```Build IoT device management system for {device_fleet}. Include device provisioning, monitoring, and over-the-air updates. Return the management system implementation and device integration.```
  

---

### *21. Game Development*

* *Create Game Engine Architecture*

  ```text
  ```Design game engine architecture for {game_type} using {game_framework}. Include rendering system, physics engine, and asset management. Return the engine design and core components.```
  

* *Implement Multiplayer Game Networking*

  ```text
  ```Set up multiplayer networking for {game_type}. Include client-server architecture, state synchronization, and lag compensation. Return the networking implementation and server setup.```
  

* *Create Game Analytics and Telemetry*

  ```text
  ```Implement game analytics and telemetry system for {game}. Include player behavior tracking, performance metrics, and monetization analytics. Return the analytics implementation and dashboard setup.```
  

* *Optimize Game Performance*

  ```text
  ```Optimize game performance for {platform}. Include rendering optimizations, memory management, and frame rate improvements. Return the optimization strategies and implementation code.```
  

---

### *22. Legacy System Modernization*

* *Create Legacy System Migration Strategy*

  ```text
  ```Design migration strategy for legacy system {legacy_system} to modern architecture. Include risk assessment, migration phases, and rollback procedures. Return the migration plan and implementation roadmap.```
  

* *Implement API Gateway for Legacy Integration*

  ```text
  ```Create API gateway to integrate legacy systems with modern applications. Include protocol translation, data transformation, and security layers. Return the gateway implementation and integration guide.```
  

* *Refactor Monolith to Microservices*

  ```text
  ```Plan and implement refactoring of monolithic application to microservices architecture. Include service boundaries, data separation, and deployment strategy. Return the refactoring plan and implementation steps.```
  

* *Implement Strangler Fig Pattern*

  ```text
  ```Implement Strangler Fig pattern for gradual legacy system replacement. Include proxy setup, traffic routing, and feature migration. Return the pattern implementation and migration strategy.```
  

---

## Advanced Prompt Combinations

### *Cross-Domain Integration Prompts*

* *Full-Stack Application with ML Integration*

  ```text
  ```Create a full-stack application that integrates machine learning capabilities. Include model serving API, real-time predictions, and result visualization. The application should use {frontend_framework} for UI, {backend_framework} for API, and {ml_framework} for model serving. Return the complete application architecture and implementation.```
  

* *Cloud-Native Application with Advanced Monitoring*

  ```text
  ```Build a cloud-native application with comprehensive monitoring and observability. Include distributed tracing, metrics collection, log aggregation, and alerting. Deploy on {cloud_platform} with {container_orchestration}. Return the application code, infrastructure configuration, and monitoring setup.```
  

* *Secure API Gateway with Authentication and Analytics*

  ```text
  ```Implement a secure API gateway with OAuth2 authentication, rate limiting, and analytics. Include JWT validation, request/response transformation, and usage analytics. Use {gateway_technology} and integrate with {analytics_platform}. Return the gateway configuration and security implementation.```
  

* *Real-time Data Processing with Event-Driven Architecture*

  ```text
  ```Design real-time data processing system using event-driven architecture. Include data ingestion, stream processing, event sourcing, and real-time analytics. Use {streaming_platform} for events and {processing_framework} for computations. Return the architecture design and implementation code.```
  

* *DevSecOps Pipeline with Automated Security Testing*

  ```text
  ```Create a DevSecOps pipeline that integrates security testing throughout the development lifecycle. Include SAST, DAST, dependency scanning, and compliance checks. Use {ci_cd_platform} and {security_tools}. Return the pipeline configuration and security automation scripts.```
  


