# Engineering Prompts

Welcome to the **Engineering Prompts** repository! This repository contains a collection of **AI prompt chains** organized by different domains, primarily for assisting developers in various tasks such as code refactoring, CI/CD setup, database management, cloud, Kubernetes deployment, web development, API Development, security, and more.

Each prompt chain is designed to build context for ChatGPT before executing a task. They can be used in **ChatGPT Queue** for bulk prompting, job, or task-focused automation.

## Domains Covered

This repository contains prompt chains for the following domains:

1. **Code Refactoring & Development**
2. **CI/CD & DevOps**
3. **Database Management**
4. **Cloud & Kubernetes**
5. **Full-Stack Development**
6. **UX/UI & Design**
7. **Security & Authentication**
8. **Event-Driven Architecture & Integration**
9. **Content Creation & Marketing**
10. **Infrastructure & System Administration**
11. **System Monitoring & Debugging**
12. **Web Development**
13. **API Development**
14. **AI/ML Integration**
15. **Testing & Quality Assurance**
16. **Agentic AI**
17. **RAG Application Development**

---

## Use Cases and Prompts

### **1. Code Refactoring & Development**

* **GitHub Repo Insight Generator**  

  ```text
  "Take a public GitHub repository link and give a simple summary of what the project is about. Include basic details like stars, forks, issues, contributors, README info, and file structure. This will help new developers quickly understand the project before working on it."
  ```

* **Refactor Code for Better Readability**

  ```text
  "Please review the provided code and identify areas where readability can be improved. Focus on simplifying complex functions, improving variable names, and removing redundant code. Return the refactored code and explain the changes made to improve readability."
  ```

* **Translate Code from One Language to Another**

  ```text
  "Translate the provided code from {source_language} to {target_language}. Ensure that the functionality remains equivalent. Highlight major differences in syntax or constructs between the two languages and explain the changes."
  ```

* **Create Documentation from Code**

  ```text
  "Extract the necessary information from the provided code to create detailed documentation. This should include explanations for functions, methods, classes, and the purpose of the code. Return the documentation in markdown format."
  ```

* **Provide Code Explanations**

  ```text
  "Please analyze the provided code and explain its functionality step-by-step. Include explanations for each major part of the code and why it's necessary. Keep the explanation clear and concise."
  ```

* **Generate Git Commit Messages**

  ```text
  "Based on the code changes, generate concise and meaningful Git commit messages. Ensure the messages describe what was changed and why, and follow conventional commit standards."
  ```

* **Debug Code**

  ```text
  "Please review the provided code and the accompanying error message. Identify the cause of the error, suggest possible fixes, and return the corrected code with explanations of the changes made."
  ```

* **Write Regular Expressions**

  ```text
  "Create a regular expression for {use_case}. For example, to validate email addresses, generate a regex that matches valid email formats. Return the regular expression and explain how it works."
  ```

* **Generate Boilerplate Code**

  ```text
  "Generate boilerplate code for a {project_type} using {programming_language}. The code should include basic setup, functions, and structure for a starting point. Return the full code with instructions for customization."
  ```

* **Automate Code Formatting**

  ```text
  "Set up an automatic code formatting system using {tool}. Configure it to run on each commit or via pre-commit hooks. Return the necessary configuration and explain how it integrates into the workflow."
  ```

* **Explain Data Structures and Algorithms**

  ```text
  "Explain the following data structure/algorithm: {data_structure/algorithm}. Include its time complexity, use cases, and any common implementations. Provide code examples where applicable."
  ```

* **Generate Mock Data**

  ```text
  "Generate mock data for the following schema: {data_schema}. Include a variety of realistic values for testing purposes. Return the data in JSON, CSV, or another format as requested."
  ```

* **Create Code for a New Feature**

  ```text
  "Please create code to implement the following feature: {feature_description}. The feature should be fully functional and integrate smoothly with the existing codebase. Return the implementation along with an explanation."
  ```

* **Suggest Performance Optimizations**

  ```text
  "Analyze the provided code for performance bottlenecks. Suggest optimizations such as reducing time complexity, memory usage, or optimizing algorithms. Return the updated code with explanations of the optimizations."
  ```

* **Generate Build Scripts**

  ```text
  "Create a build script for automating the build process of a {project_type} using {build_tool}. The script should include steps for compiling, packaging, and versioning. Return the build script along with setup instructions."
  ```

* **Offer Security Best Practices**

  ```text
  "Provide a list of security best practices for {application_type}. Focus on areas like authentication, authorization, data protection, and secure coding practices. Return actionable advice with examples where necessary."
  ```

* **Assist in Code Reviews**

  ```text
  "Review the provided code and provide feedback. Focus on aspects like readability, performance, security, and maintainability. Suggest improvements and explain the rationale behind each recommendation."
  ```

* **Test for Compatibility After Upgrading Node.js Version**

  ```text
  "After upgrading Node.js from version 14 to 18, use Keploy to run automated tests to ensure that the application is working as expected. Set up Keploy to perform integration tests and verify that the backend, APIs, and frontend components are compatible with the new Node.js version. The tests should focus on key areas such as API responses, performance, and compatibility with external dependencies that may have been affected by the Node.js upgrade. Ensure that Keploy compares the results with the previous behavior recorded under Node.js 14 to detect any regressions or issues introduced by the upgrade. Return the Keploy test configuration, test cases, and results."
  ```

* **Integrate Third-Party Services**

  ```text
  "Integrate {third_party_service} into the existing project. Provide step-by-step instructions for setup, authentication, and API interaction. Return the integration code with explanations of how it works."
  ```

* **Write a Dockerfile for the Application**

  ```text
  "Create a Dockerfile to containerize the provided application. Ensure that the Dockerfile sets up the environment correctly, installs dependencies, and exposes the necessary ports. Return the Dockerfile with explanations."
  ```

* **Provide UX/UI Design Advice**

  ```text
  "Provide UX/UI design recommendations for the provided {website/app}. Focus on improving usability, accessibility, and aesthetics. Return a list of specific design improvements with examples where necessary."
  ```

* **Suggest Testing Strategies**

  ```text
  "Suggest a comprehensive testing strategy for {project_type}. The strategy should include unit tests, integration tests, and end-to-end tests. Provide recommendations for testing frameworks and tools, along with examples."
  ```

* **Intelligent Legacy Code Modernizer**

  ```text
  "Analyze this legacy codebase and produce a step-by-step modernization plan. Suggest incremental refactoring, API replacements, and removal of deprecated dependencies. For each step, provide sample code snippets or commands to automate the transformation safely, with explanations of risks and benefits."
  ```

* **Test for Regressions After Refactoring Code with Keploy**

  ```text
  "After refactoring the code, use Keploy to run automated tests to check if any regressions have been introduced. Set up Keploy to verify that the refactored code behaves as expected, ensuring that all existing functionalities remain intact. The tests should include integration tests to verify that API endpoints, data handling, and user interactions still function properly. Ensure that Keploy is set to compare the current behavior with previously recorded test cases to detect any discrepancies or regressions. Return the Keploy test configuration, test cases, and results showing the behavior of the refactored code."
  ```
* **Explain Java Inheritance with Code Example**
  ```text

  "Explain the concept of inheritance in Java using a code example with a base class and a derived class. Describe how method overriding works, and return the sample code along with a step-by-step explanation of how inheritance is applied."
  ```


* **AI-Powered Tech Debt Quantifier**

  ```text
  "Create a script that analyzes codebases to generate a tech debt heatmap using ML models. Output severity scores for code smells, outdated dependencies, and test coverage gaps with remediation priorities. Include integration with Jira/Trello."
  ```
  
* **Convert Monolithic code to Microservices**
  
  ```text
  "Break down the provided monolithic code into a modular microservices architecture. Ensure each microservice encapsulates a distinct business capability with clear separation of concerns. Maintain equivalent functionality across the system. For each extracted microservice, define its responsibility, input/output interface (e.g., REST API or message queue), and any dependencies it requires. Use clean, readable code following best practices for maintainability. After refactoring, explain the major architectural changes made, including how responsibilities were divided, how the services communicate, and any significant improvements in modularity or readability. Also, highlight trade-offs involved in the transformation from monolith to microservices, such as increased complexity or network overhead."
  ```

---

### **2. CI/CD & DevOps**

* **Set up CI/CD Pipelines**

  ```text
  "Help set up a CI/CD pipeline for the project using {CI_tool}. The pipeline should include stages for building, testing, and deploying the application. Provide configuration files and explanations of each stage."
  ```

* **Automate Code Formatting**

  ```text
  "Set up an automated code formatting system using {tool}. Configure it to run on each commit or via pre-commit hooks. Return the necessary configuration and explain how it integrates into the workflow."
  ```

* **Set up Cloud Cost Optimization Strategies**

  ```text
  "Provide strategies for optimizing cloud costs in {cloud_provider}. Focus on areas like reserved instances, auto-scaling, and rightsizing. Return recommendations and examples of how to implement them."
  ```

* **Create Docker Compose Configurations**

  ```text
  "Create a Docker Compose configuration file to set up {services}. The configuration should include service dependencies, environment variables, and port mappings. Return the Docker Compose YAML with an explanation."
  ```

* **Generate Cron Jobs for Task Scheduling**

  ```text
  "Write cron jobs to schedule tasks on a Linux system. The tasks should run at {interval} and execute {command}. Return the cron job configurations with explanations of each field."
  ```

* **Implement Automated Security Testing in CI/CD**

  ```text
  "Integrate automated security testing tools like {security_tool} into the CI/CD pipeline. Configure the pipeline to run security checks on each commit or pull request. Return the updated pipeline configuration."
  ```

* **Set up Serverless Architecture with Google Cloud Functions**

  ```text
  "Create a serverless architecture using Google Cloud Functions for {task}. The functions should trigger based on specific events and return the necessary code with setup instructions."
  ```

* **Write Infrastructure as Code (IaC) for AWS with CloudFormation**

  ```text
  "Write infrastructure-as-code (IaC) for AWS using CloudFormation. Automate the provisioning of resources such as EC2, RDS, and S3 for {application}. Return the CloudFormation templates with explanations."
  ```

* **Create a Custom Shell Script for System Administration**

  ```text
  "Create a custom shell script that automates {system_task} such as backups, log rotations, or user management. The script should be efficient and handle errors gracefully. Return the shell script with usage instructions."
  ```

* **Create an Event-Driven Architecture with Kafka**

  ```text
  "Set up an event-driven architecture with Kafka. Define the Kafka topics, producers, and consumers to handle real-time data processing. Return the code with configuration details."
  ```

* **Implement Data Preprocessing for Machine Learning**

  ```text
  "Implement data preprocessing steps for machine learning. This includes handling missing data, scaling features, and encoding categorical variables. Return the preprocessing code and explain each step."
  ```

* **Implement Serverless Functions on AWS Lambda**

  ```text
  "Set up serverless functions using AWS Lambda to perform {task}. Include setup instructions for the trigger and return the Lambda function code."
  ```

* **Set up Google Analytics for Portfolio Tracking**

  ```text
  "Set up Google Analytics tracking for my portfolio website. Provide the steps for adding tracking code and configuring goals. Return the setup instructions."
  ```

* **Optimize a Docker-Based Development Environment**

  ```text
  "Optimize the provided Docker development environment. Focus on reducing build time, improving caching, and streamlining container configurations. Return the optimized Dockerfile and Docker Compose file."
  ```

* **Chaos Engineering Pipeline Injector**

  ```text
  "Design a CI/CD stage that randomly introduces controlled failures (network latency, pod terminations) during pre-prod deployments. Generate resilience reports with recovery time metrics and weak spot visualizations."
  ```

---

### **3. Database Management**

* **Detect & Filter Redundant Data in PostgreSQL**

  ```text
  "Given the following PostgreSQL table structure: <Table columns with constraints>

  I suspect redundant or repeated data might be coming from a process that re-inserts the same ______, ________ and ________ combination multiple times.

  Write a SQL query to:

  - Identify all such repeated entries.
  - Filter out and create the new view without the duplicate entries.
  - Create a reusable filter CTL query for documentation in the future use.
  - Generate a delete statement that removes the duplicates but retains one unique record from each group.**

  Provide the SQL in a safe and modular way so I can review duplicates before deletion."
  ```

* **Design a General Entity-Relationship Diagram**

  ```text
  "Design an Entity-Relationship (ER) diagram for a sample application with multiple entities and relationships. Clearly define the primary keys, foreign keys, and relationship types (1:1, 1:N, N:M)."
  ```

* **Generate SQL Queries**

  ```text
  "Given the database schema and the following requirements (e.g., 'Find all users who joined after 2020'), generate an appropriate SQL query. Return the SQL query and explain its logic."
  ```

* **Explain Database Design**

  ```text
  "Please review the database schema provided and explain its design choices. Discuss normalization, relationships between tables, and indexing strategies. Suggest improvements for scalability and performance."
  ```

* **Design a Normalized Relational Database Schema**

  ```text
  "Design a relational database schema for {application}. Ensure that it is normalized up to 3NF, with proper primary/foreign keys and indexes. Return the schema in SQL format."
  ```

* **Set Up a PostgreSQL Database with Docker**

  ```text
  "Set up a PostgreSQL database in a Docker container. Include steps for configuring the database, creating the schema, and connecting to the container. Return the Dockerfile and Docker Compose configuration."
  ```

* **Implement Database Sharding**

  ```text
  "Implement database sharding for {database_name}. Define the sharding strategy and partition the data across multiple shards. Return the setup and configuration details."
  ```

* **Create and Optimize a NoSQL Database (MongoDB)**

  ```text
  "Set up and optimize a MongoDB database for {application}. Include recommendations for indexing, query optimization, and data modeling. Return the schema and optimization steps."
  ```

* **Optimize Database Queries for Performance**

  ```text
  "Analyze the provided database queries and suggest performance optimizations. This may include indexing, query refactoring, and reducing the complexity of joins. Return the optimized query with explanations."
  ```

* **Implement Multi-Threading and Concurrency Concepts**

  ```text
  "Explain the concepts of multi-threading and concurrency in {programming_language}. Focus on thread management, race conditions, and synchronization techniques. Provide code examples where applicable."
  ```

* **Setup Prisma with PostgreSQL in Node.js project**

```text
"Guide me through setting up Prisma with PostgreSQL in a Node.js project. Include steps to install dependencies, initialize Prisma, connect to a local PostgreSQL database, create a sample schema, and run migrations. Show the full commands and explain how the schema.prisma file works. Ensure the example includes one sample model like User"
```

* **Build CRUD API using Prisma and Express**

```text
"Help me build a complete CRUD REST API using Express.js and Prisma. Use a User model with fields like id, name, email, and createdAt. Include the routes for Create, Read (single & all), Update, and Delete. Show how Prisma Client is used in each route. Return the full Express route code with explanations."
```

* **Define and query relations in Prisma**

```text
"Teach me how to define and query relational data in Prisma. Use an example with two models: User and Post, where a user can have many posts. Show how to define the relation in schema.prisma, run migrations, and write queries to fetch a user with their posts. Include how to use include and select with Prisma Client"
```

* **Automated Query Optimization Assistant**

  ```text
  "Given a set of slow SQL queries and the current database schema, use AI to suggest and apply index improvements, query rewrites, and partitioning strategies. Return the optimized queries, new index statements, and a summary of expected performance gains."
  ``

* **Implement Query Migration**

  ```text
  "You are a database query migration expert. Given a {query} written for a specified {source_database}, convert it to be fully compatible with a specified {target_database}.  
  Adapt all syntax, functions, data types, and conventions as necessary. Ensure that the output query:  

  - Preserves the original logic,  
  - Uses correct equivalents in the target system,  
  - Is optimized according to best practices.  

  Provide brief explanations for non-trivial changes when applicable.  

  Input fields:  
  - source_database: (e.g., Oracle, MySQL, SQL Server)  
  - target_database: (e.g., PostgreSQL, SQLite, MariaDB)  
  - query: (Original source query to be migrated)  

  Output:  
  - A fully converted query compatible with the target database  
  - Optional: Short explanation of major differences or adaptations"

  ```
  
* **Create a Seed Script to Seed data to a database**

  ```text
  "Based on the schemas file, model file and service layer file I attached for the {a_table_in_the_database} and {a_specific_program_component}, please return a PostgreSQL seed script for the database. Please create realistic sample data"
  ```

* **Database Migration Strategy with Zero-Downtime Deployment**

  ```text
  "Design a comprehensive database migration strategy for {database_type} that ensures zero-downtime deployment. First assess the current system architecture and constraints, then provide a migration plan that includes: rollback procedures, data validation checkpoints, gradual migration techniques, infrastructure requirements, and deployment orchestration steps. Account for various scenarios including large datasets, concurrent user access, limited infrastructure, and different deployment environments. Provide both high-level strategy and detailed implementation scripts."
  ```
 ---

### **4. Cloud & Kubernetes**

* **Set Up Kubernetes Cluster on AWS EKS**

  ```text
  "Please guide the setup of a Kubernetes cluster using Amazon EKS. Include steps for configuring the cluster, setting up node groups, and connecting kubectl. Return the steps and configuration files."
  ```

* **Implement Persistent Storage in Kubernetes Using StatefulSets**

  ```text
  "Set up persistent storage in Kubernetes using StatefulSets. Configure PersistentVolumeClaims (PVC) and explain how it ensures data persistence. Return the YAML configuration files."
  ```

* **Set Up Cloud Storage with Amazon S3**

  ```text
  "Please provide the steps for setting up cloud storage using Amazon S3. Include how to create a bucket, set permissions, and manage files programmatically via AWS SDKs. Return the necessary code examples for integration."
  ```
* **Amazon S3 as a Static Website with CI/CD**

 ```text
   "Demonstrate how to host a static website on Amazon S3 and automate its deployment with GitHub Actions. Include S3 bucket website configuration, IAM policy setup, and a GitHub Actions workflow that uploads files on every push to the main branch."
  ```

* **Cloud Cost Anomaly Detector**
  
  ```text
  "Set up a monitoring system in Kubernetes that uses ML to detect and alert on unusual spikes in cloud resource costs. Include sample Prometheus/Grafana configurations and a script for automated cost anomaly remediation (e.g., scaling down unused pods)."
   ```
    
  * **Kubernetes Observability Stack with Prometheus, Grafana, and Loki**

  ```text
  "Deploy a fully integrated observability stack in Kubernetes using Helm—configure Prometheus for metrics and alerts, Grafana for dashboards, and Loki for centralized log aggregation with all necessary YAML and values files.."
  ```

* **Enable Auto-Scaling for Kubernetes Workloads**

  ```text
  "Guide me through setting up Horizontal Pod Autoscaler (HPA) in Kubernetes. Include CPU-based scaling configuration, metric server setup, and example deployment with auto-scaling enabled. Return sample YAML files and scaling thresholds."
  ```
  
* **Deploy a Multi-Container Pod in Kubernetes**

  ```text
  "Demonstrate how to deploy a multi-container pod (sidecar pattern) in Kubernetes. Explain use cases, share the pod definition YAML, and describe container interaction."
  ```

---

### **5. Full-Stack Development**

* **Develop a Full-Stack Web Application Using Django and React**

  ```text
  "Create a full-stack web application with Django as the backend and React for the frontend. Implement user authentication, RESTful API communication, and a simple CRUD interface. Return the project structure and code snippets."
  ```

* **Integrate a Payment Gateway (Stripe) in a Full-Stack App**

  ```text
  "Integrate Stripe for handling payments in a full-stack application with Django and React. Set up the backend to handle payments and the frontend to interact with Stripe's API. Return the code for integration."
  ```

* **Create a RESTful API with Express.js**

  ```text
  "Help me set up a RESTful API using Express.js. Define the necessary routes and controllers to support CRUD operations for a {resource}. Return the implementation of the API with explanations for each endpoint."
  ```

* **Implement Real-Time Updates with WebSockets**

  ```text
  "Set up real-time updates in the application using WebSockets. Provide the necessary code for both the server (using socket.io or similar) and the frontend to enable live updates."
  ```

* **Test Backend and Frontend for Regression Using Keploy**
  ```text
  "Set up Keploy in your full-stack application to test both the backend and frontend after an update. Configure Keploy for automatic integration testing, focusing on testing API endpoints, data handling, and the interaction between the frontend and backend. Ensure that Keploy is set to capture all changes in the API response, including edge cases, and validate that the frontend works correctly with the updated backend. Return the setup configuration and steps to trigger Keploy for testing."
  ```

* **Implement JWT-Based Authentication**
  ```text
  "Set up JWT-based authentication in a full-stack app using Express.js and React. Include login, token handling, and protected routes."
  ```

* **Use Context API and Custom Hooks in React**

  ```text
  "Show how to manage global state in React using Context API and custom hooks for session management or theme switching."
  ```

* **Connect React Frontend to Flask Backend**
    
  ```text
  "Build a full-stack app with a Flask backend and React frontend. Show how the frontend fetches data from Flask APIs."
  ```

* **Write Tests for Backend and Frontend**

  ```text
  "Guide me on writing unit and integration tests for a full-stack app using Jest for the backend and React Testing Library for the frontend."
  ```

* **Use Redux Toolkit in E-Commerce App**

  ```text
  "Build a full-stack e-commerce app where Redux Toolkit manages cart and user state in the frontend and Express/MongoDB powers the backend."
  ```

* **Deploy Full-Stack App on Render or Vercel**

  ```text
  "Explain how to deploy a full-stack app with React frontend on Vercel and Node.js/Django backend on Railway or Render. Include environment setup steps."
  ```
  
* **Newsletter Subscription System with MongoDB**

  ```text
  "Implement a backend newsletter subscription system using Express.js and MongoDB. Users should be able to subscribe by submitting their email address. Validate email format, prevent duplicate entries, and support unsubscription. Store all subscriber data in MongoDB. Return the full implementation including routes, email validation, MongoDB schema, and success/failure responses."
  ```

* **JWT-Based Authentication for Full-Stack App**

  ```text 
  "Secure a full-stack application using JSON Web Token (JWT) authentication. In the backend (Node.js + Express), implement user login and protected routes, generate JWT tokens, and use middleware to validate tokens. In the frontend (React), store the token securely using HttpOnly cookies or localStorage, send it with API requests, and protect routes using React Router. Return complete backend implementation and frontend logic for login, token storage, and route protection."
  ```

* **Transactional Order Confirmation Emails Using Nodemailer**

  ```text
  "Develop a backend service in Node.js to send transactional order confirmation emails using Nodemailer with SMTP configuration. Use a template engine like EJS or Handlebars to generate dynamic HTML emails. The email should include the customer's name, order ID, list of ordered items, total amount, and estimated delivery time. Return the complete code including SMTP setup, email template rendering, and the sendMail function."
  ```

* **OTP-Based Login System Using Node.js and MongoDB**

  ```text
  "Build an OTP (One-Time Password) based login system using Node.js and Express. The backend should generate a time-limited numeric OTP, send it to the user's phone or email, and validate it upon user input. Use MongoDB for OTP storage with expiry. Return the complete backend code including OTP generation, storage, verification, expiry logic, and rate limiting."
  ```

* **Develop a Full-Stack Mobile Application**

  ```text
  "Create a full-stack mobile application using React Native for the frontend and Node.js with Express for the backend. Implement user authentication, a RESTful API for data management, and real-time updates using WebSockets. Return the project structure, key code snippets, and setup instructions for both frontend and backend."

* **Integrate an AI Text Generation API into a Full-Stack App**

  ```text
  "Integrate an AI API such as OpenAI or Hugging Face into a full-stack application with Django and React. Set up the backend to handle text generation requests using the API, and configure the frontend to capture user input and display AI-generated responses in real time. Return the complete code for integration."

* **Implement Role-Based Access Control (RBAC) in a Full-Stack App**

  ```text
  "Implement role-based access control in a full-stack application using Django and React. Define roles like Admin, Editor, and Viewer. Restrict access to specific backend API routes and conditionally render frontend components based on roles. Return the role-check logic, middleware, and protected route implementation."
  ```

* **Build Production-Ready MERN Stack Application with Advanced Features**

  ```text
  "Develop a comprehensive production-ready full-stack application using the MERN stack (MongoDB, Express.js, React, Node.js) with advanced features including user authentication with JWT and refresh tokens, role-based access control (RBAC), real-time notifications with Socket.io, file upload handling with AWS S3 integration, comprehensive error handling and logging, API rate limiting and security middleware, responsive design with Material-UI or Tailwind CSS, automated testing suite with Jest and Cypress, Docker containerization, CI/CD pipeline with GitHub Actions, and performance optimization techniques. Include proper project structure, environment configuration, database seeding, API documentation with Swagger, and deployment instructions for cloud platforms. Return the complete application architecture, code implementation, and deployment guide."

* **Build a Flutter + Node.js Full-Stack App with ML Integration and Firebase Auth** 
  ```text 
  "Build a full-stack application with Flutter as the frontend and Node.js (Express) as the backend. Use Firebase Authentication for user login/signup and MongoDB for storing data. Integrate a pre-trained machine learning model via a Python API or hosted service (e.g., for recommendation, classification, or NLP). Ensure the frontend captures user input, sends it to the backend, triggers the ML model, and returns results to display in the UI. Return code for each layer along with setup instructions and architecture overview."
  ```

---

### **6. UX/UI & Design**

* **Modernize an Outdated App UI**
 
  ```text
  "You are given screenshots of an outdated mobile app UI. Suggest modern design improvements based on current design trends, material design guidelines, and usability best practices."
  ```

* **Provide UX/UI Design Advice**

  ```text
  "Provide UX/UI design recommendations for the provided {website/app}. Focus on improving usability, accessibility, and aesthetics. Return a list of specific design improvements with examples where necessary."
  ```
  
* **Create a Wireframe from App Description**

  ```text
  "Based on the following app idea or description, suggest a low-fidelity wireframe layout for key screens. Include layout, navigation flow, and key UI elements. Return the structure as a textual or block-based wireframe."
  ```
  
* **Suggest a Color Palette and Typography**

  ```text
  "Suggest a modern, accessible color palette and complementary typography for a {type of app/website}. Justify the choices based on contrast, readability, and emotional impact."
  ```
  
* **Improve Landing Page Layout**

  ```text
  "Evaluate the provided landing page layout. Suggest improvements in layout hierarchy, visual balance, and call-to-action placement. Return a list of actionable layout changes."
  ```

* **Evaluate Mobile Responsiveness**

  ```text
  "Evaluate the mobile responsiveness of the given {website/app}. Suggest layout or style adjustments for optimal viewing across different screen sizes, including phones and tablets."
  ```

* **Improve Onboarding Experience**

  ```text
  "Analyze the user onboarding process for {website/app}. Recommend improvements to reduce friction and increase user retention. Provide mockup ideas or flow adjustments if applicable."
  ```

* **Color & Typography Optimization**

  ```text
  "Audit the color scheme and typography of the {website/app}. Suggest changes to improve readability, contrast ratios, and visual consistency based on WCAG accessibility guidelines."
  ```
  
* **Accessibility-First Redesign Assistant**
  
  ```text
  "Review the provided web interface and generate a redesign plan that achieves WCAG 2.2 AA accessibility compliance. Include annotated wireframes, color contrast checks, and ARIA attribute recommendations."
  ```
  
* **UX/UI Review for Onboarding Flow**

  ```text
  "Evaluate the onboarding experience of the provided {website/app}. Suggest UX/UI improvements that enhance first-time user engagement, reduce friction, and promote task completion. Focus on clarity of instructions, visual hierarchy, button placement, and accessibility. Return actionable recommendations with examples where applicable."
  ```
  
* **Provide Improvements to Redesign**

  ```text
  "An app is not accessible to visually impaired users. Redesign the app to ensure full accessibility for all users. Consider navigation, screen reader compatibility, color contrast, and touch targets."
  ```
  
* **Provide Acessible Color Palettes**

  ```text
  "Provide a set of accessible color palettes that comply with WCAG standards. The palettes should offer sufficient contrast and visual distinction for users with visual impairments. Return color combinations in hex codes and explain the accessibility rationale."
  ```

* **Audit UI for WCAG Compliance**

  ```text
  "Analyze the provided website or application UI and identify issues related to WCAG 2.1 accessibility compliance. Suggest specific changes to improve color contrast, keyboard navigation, screen reader support, and overall usability."
  ```

* **Create Animations using Framer Motion or GSAP**

  ```text
  "Create animation strategies using Framer Motion or GSAP for enhancing user experience on{given_web_application}. Include code snippets for entrance animations, transitions, and hover effects."
  ```

* **Suggest UX Improvements Based on User Goals**

  ```text
  "Analyze a digital product intended for {user persona} with the primary goal of {goal}. Suggest UX improvements that reduce friction, clarify CTAs, and guide the user efficiently. Include ideas for onboarding, navigation, and error prevention/recovery."
  ```

* **Improve Interaction Design**

  ```text
  "Review the interaction design for this component/page: {description or link}. Suggest improvements that would make the experience smoother and more intuitive. Consider animation timing, gesture control (if mobile), transitions, and feedback cues."
  ```

* **UX Writing Improvements**

  ```text
  "Review the UX writing and microcopy for this interface: {screen/page/component}. Suggest clearer, more helpful, and user-friendly alternatives. Focus on button labels, error messages, tooltips, and onboarding text."
  ```

---

### **7. Security & Authentication**

* **Offer Security Best Practices**

  ```text
  "Provide a list of security best practices for {application_type}. Focus on areas like authentication, authorization, data protection, and secure coding practices. Return actionable advice with examples where necessary."
  ```

* **Implement JWT-Based Authentication**

  ```text
  "Implement JSON Web Token (JWT) authentication in the provided application. The system should handle token generation, validation, and secure access to protected routes. Return the code with explanations."
  ```

* **Zero Trust Architecture Quickstart**
  
  ```text
  "Transform the current system architecture into a Zero Trust model. Output a step-by-step migration plan, including network segmentation, identity verification at every layer, and continuous authentication strategies. Provide sample policies and enforcement scripts."
  ```

---

### 8. Event-Driven Architecture & Integration

* **Design Scalable Kafka Event Architecture**  

  ```text
  "Design an event-driven architecture using Apache Kafka. Define at least two Kafka topics with justification for their partitioning and replication factors. Provide producer and consumer code in [Language] (e.g., Python, Java) for one topic, including configuration details for idempotence, compression, and fault tolerance. Explain how the setup handles backpressure and scales under load."
  ```

* **Robust Third-Party Service Integration** 

  ```text 
  "Integrate {third_party_service} into the existing project. Detail setup steps (dependency installation, environment variables), authentication (API keys/OAuth 2.0 flow), and rate-limited API interactions. Provide error-handling code for network failures and invalid responses, with a circuit-breaker implementation. Include a workflow diagram illustrating data flow between components."
  ```

* **Implement Change Data Capture (CDC) Pipeline**  
 
  ```text
  "Design a CDC system using Debezium and Kafka Connect. Configure connectors for {database_type} to capture real-time database changes. Provide deployment manifests, transformation logic for schema evolution, and dead-letter queue handling for failed events. Include monitoring setup for lag and throughput metrics."
  ```

* **Build Event Sourcing/CQRS System**  
  
  ```text
  "Implement an event-sourced architecture using Kafka as the event store. Define event schemas for {domain_entity} state changes, command handlers, and read-model projections. Provide code for idempotent event processing, snapshotting strategy, and consistency validation between write/read models."
  ```

* **Design Cross-Cluster Event Replication**  

```text
  "Configure MirrorMaker2 for geo-replication between Kafka clusters. Define replication policies, topology discovery, and offset synchronization. Provide Terraform modules for multi-region deployment with metrics for replication latency and failover procedures during region outages."
  ```

* **Integrate Serverless Event Consumers**  

```text
  "Connect Kafka to serverless platforms (AWS Lambda/Google Cloud Functions). Develop consumer functions in [Language] with checkpointing, batch processing, and autoscaling configuration. Include cold-start optimization and cost analysis for different throughput scenarios."
  ```  

* **Create Schema Registry Governance**  
 
 ```text
  "Implement schema evolution governance using Confluent Schema Registry. Define compatibility rules (BACKWARD/FORWARD), schema lifecycle management, and client serialization/deserialization logic. Provide CI/CD pipeline for schema validation and version rollback procedures."
  ```

---

### **9. Content Creation & Marketing**

* **Create a Personal Portfolio Website**

  ```text
  "Help me build a personal portfolio website. The site should include sections for my bio, projects, skills, and contact information. Make sure it's responsive and easy to navigate. Return the basic HTML/CSS/JS code for the website."
  ```

* **Create platform-specific strategies development**

  ```text
  "Evaluate the content strategy of the given {brand/website}. Suggest improvements for audience engagement, SEO, and brand voice. Provide actionable content ideas, platform-specific strategies, and examples to enhance reach and conversion."
  ```

* **Write SEO-Optimized Blog Content**

  ```text
  "Generate a blog post on {topic} optimized for SEO. Use keyword research to include high-traffic keywords naturally, structure the post with headings and subheadings, and ensure it is engaging and informative. Return the content with SEO suggestions."
  ```
  
* **Design a Social Media Content Calendar**

  ```text
  "Create a 30-day content calendar for social media marketing focused on {industry or brand}. Include post ideas for Instagram, LinkedIn, Twitter, and Facebook, along with captions, hashtags, and recommended posting times."
  ```
  
* **Generate LinkedIn Summary and Job Descriptions**

  ```text
  "Generate a compelling LinkedIn summary and job description based on the following details: {job_title}, {skills}, {experience}. Ensure the summary is concise, professional, and highlights key achievements."
  ```
  
* **Create a Content Strategy for YouTube Channel Growth**
  
  ```text
  "Help me develop a 3-month content strategy for a YouTube channel about {niche}. Include video ideas, SEO titles, descriptions, and tips to improve watch time and subscriber growth."
  ```

* **Generate Email Marketing Campaign Content**
  
  ```text
  "Generate a sequence of 5 marketing emails for a {product/service} launch. Each email should have a specific goal (awareness, interest, decision, action) and include an engaging subject line, body copy, and CTA."
  ```
  
* **Create Infographic Content for Marketing**
  
  ```text
  "Generate content and layout suggestions for an infographic on {topic}. Include key statistics, headings, concise text blocks, and suggestions for visuals and icons."
  ```
  
* **Write a Brand Story for Marketing Purposes**
  
  ```text
  "Craft a compelling brand story for {company/brand name}. Include the origin, mission, values, and vision. The tone should resonate with {target audience} and be suitable for use on a website or promotional material."
  ```
   
* **Develop Ad Copy for a Google/Facebook Ads Campaign**
  
  ```text
  "Write 3 variations of ad copy for a Google or Facebook Ads campaign promoting {product/service}. Include strong hooks, benefits, and calls to action. Tailor the tone for {audience type}."
  ```
  
* **Generate Podcast Episode Topics and Scripts**
  
  ```text
  "Generate a list of 10 podcast episode topics on {theme/niche}. For one of them, provide a detailed script outline including intro, segment breakdowns, key talking points, and closing remarks."
  ```

* **Email Marketing Campaign Writer**

  ```text
  "Create a 5-part email marketing sequence for a product/service called "{product_name}". The goal is to {goal}. Each email should be short, persuasive, and follow copywriting frameworks like AIDA or PAS. Include subject lines, preview text, and CTAs."
  ```

---

### **10. Infrastructure & System Administration**

* **Create an Infrastructure as Code (IaC) for AWS with CloudFormation**

  ```text
  "Write infrastructure-as-code (IaC) for AWS using CloudFormation. Automate the provisioning of resources such as EC2, RDS, and S3 for {application}. Return the CloudFormation templates with explanations."
  ```

* **Set Up Serverless Architecture with Google Cloud Functions**

  ```text
  "Create a serverless architecture using Google Cloud Functions for {task}. The functions should trigger based on specific events and return the necessary code with setup instructions."
  ```

* **Create Terraform Code for AWS Resources**

  ```text
  "Write Terraform configuration files to provision AWS resources (EC2, RDS, S3, etc.) for {application}. Include variable support and a README with deployment instructions."
  ```

* **Automate Backup & Disaster Recovery**

  ```text
  "Design an automated backup and disaster recovery plan for {infrastructure_type}. Include scripts/configuration to back up databases and VM instances with scheduled recovery points."
  ```
* **Proactive Incident Simulation Toolkit**
  
  ```text
  "Create a toolkit that simulates real-world infrastructure incidents (e.g., server outage, DNS failure, disk full) and provides automated runbooks for detection, alerting, and step-by-step resolution. Include sample scripts and monitoring configurations."
  ```

---

### **11. System Monitoring & Debugging**

* **Debug Performance Issues in Production Systems**

  ```text
  "Analyze the performance of the production system and identify bottlenecks. Suggest and implement optimizations to improve speed, reduce memory usage, and increase scalability. Return the optimized code and explanations."
  ```

* **Log Analysis with ELK Stack**

  ```text
  "Configure log aggregation using the ELK (Elasticsearch, Logstash, Kibana) stack for {application/system}. Show how to filter and visualize critical events for debugging."
  ```

* **Create Health Check and Uptime Monitoring**

  ```text
  "Write health check endpoints and set up uptime monitoring using {tool like Pingdom, UptimeRobot}. Include alerting mechanisms and retry logic."
  ```

* **Analyze Memory Leaks in Node.js App**

  ```text
  "Identify and debug memory leaks in the provided Node.js application. Return optimized code, heap snapshot instructions, and memory profiling techniques."
  ```

* **Integrate Prometheus and Grafana Dashboards**
  ```text
  "Set up Prometheus and Grafana to monitor a Node.js application. Include steps for exporting application metrics, configuring Prometheus scraping, and creating a custom dashboard in Grafana to visualize performance and error metrics."
  ```

* **Debug Memory Leaks in Node.js or Python**
  ```text
  "Help diagnose memory leaks in a Node.js/Python application. Analyze heap snapshots or memory usage patterns, suggest tools like `memory_profiler` or `clinic.js`, and provide steps to fix common causes of leaks."
  ```

* **Generate Test Cases from Logs**

  ```text
  " Design an efficient test suite for the production environment to ensure stability, scalability, and minimal downtime. Include unit, integration, and stress test scenarios with explanations. Return test case examples and tools used."
  ```
---

### **12. Web Development**

* **Build a Dark/Light Mode Toggle**

  ```text
  "Add a dark/light mode switcher to a website using CSS variables and JavaScript. Ensure transitions are smooth and all elements follow the selected theme accurately."
  ```

* **Write Tests for Front-End Components**

  ```text
  "Write unit and integration tests for the provided front-end components using {testing_framework}. Ensure the tests cover all major use cases and edge cases. Return the test code with explanations."
  ```

* **Optimize Front-End Performance**

  ```text
  "Audit the performance of the given website. Suggest and implement optimizations such as lazy loading, code splitting, and CDN usage. Include metrics before and after."
  ```

* **SEO Optimization Checklist**

  ```text
   "Generate an SEO optimization checklist for {website}. Analyze meta tags, sitemap, robots.txt, image alt tags, structured data, and page speed. Return suggestions and corrected HTML snippets."
  ```

* **Secure Web App with Best Practices**

  ```text
  "Identify and fix security vulnerabilities in the provided web app code. Include fixes for XSS, CSRF, CORS misconfigurations, and session handling flaws."
  ```
  
* **Audit Website for Accessibility Issues**

  ```text
  "Please review the provided website code and identify any accessibility issues according to WCAG guidelines. Suggest improvements for better accessibility, such as proper use of ARIA attributes, color contrast, keyboard navigation, and semantic HTML. Return a list of issues found and recommended code changes."
  ```

* **Create a Reusable Form Component in React**

  ```text
  "Create a reusable React form component that takes input configuration as props, such as (validation rules, field names, and types). Give an example of how you would use it to create sign-up and login forms. Explain form state handling and include code."
  ```

* **Implement Theme Switching with State Persistence**  
  
  ```text
  "Provide a React or Next.js component to toggle between light and dark modes. Use CSS variables and persist user preference in `localStorage` or `cookies`, ensuring no hydration mismatch on rehydration."
  ```

* **Secure REST API Authentication Flow using JWT**

  ```text
  "Generate backend Express.js code to handle user login and registration using hashed passwords with bcrypt. Return a signed JWT on success and validate it via middleware for protected routes."
  ```

* **Generate a Scalable Folder Structure for a Full-Stack MERN App**

  ```text  
  "Design a scalable project structure for a MERN stack application, separating concerns like routes, controllers, services, models, and utilities. Include reasoning for each folder."
  ```

* **Optimize Frontend Performance in a React Application**  

  ```text
  "List concrete strategies and implement React code snippets to improve performance using memoization (`React.memo`, `useMemo`), lazy loading (`React.lazy`), and bundle splitting."
  ```

* **Implement Infinite Scrolling with Throttling and Pagination**  
  
  ```text
  "Generate a React component to implement infinite scrolling on a blog post feed. Use intersection observer or scroll event handlers with throttling and server-side pagination."
  ```

* **Design a CMS-Agnostic Blog Template** 

  ```text 
  "Generate reusable and CMS-agnostic frontend components (in React/Next.js or HTML/Alpine.js) that can dynamically display blog post content using Markdown, MDX, or CMS API responses (e.g., Sanity or Contentful)."
  ```

* **Write Access-Control Middleware for Role-Based Routing**  
  
  ```text
  "Provide middleware logic for a Node.js backend that implements role-based access control (RBAC). Include route protection for Admin, Editor, and Public user roles."
  ```

* **Implement Secure File Upload Handling in Express.js** 

  ```text 
  "Create a secure Express route using `multer` to handle image uploads with MIME type filtering, file size restrictions, and S3 bucket integration."
  ```

* **Transform JSON Schema to Form UI in React**  

  ```text
  "Generate a prompt chain or code logic that takes a JSON schema definition and renders a corresponding React form with input validation, field grouping, and dynamic rendering."
  ```

* **IMPLEMENT ADVANCED FRONTEND PERFORMANCE OPTIMIZATION**
    ```text
  "Optimize the provided web application for maximum performance and Core Web Vitals compliance. Implement advanced techniques including code splitting with dynamic imports, tree shaking, bundle analysis and optimization, image optimization with WebP/AVIF formats, lazy loading with Intersection Observer API, and critical CSS extraction. Add performance monitoring with Real User Monitoring (RUM), implement resource hints (preload, prefetch, preconnect), optimize font loading strategies, and minimize JavaScript execution time. Target metrics: LCP < 2.5s, FID < 100ms, CLS < 0.1, and overall Lighthouse score > 95."
  ```
  
* **Implement Lazy Loading of Components**
  ```text
  "Implement lazy loading in a React or Vue application to improve initial load time. Return code snippets using dynamic imports, explain how to apply it to routes or components, and describe the impact on performance."
  ```

---

### **13. API Development**

* **Design and Implement Comprehensive API Gateway for Microservices Architecture**

  ```text
  "Design and implement a comprehensive API Gateway for microservices architecture using {gateway_framework} (Kong, AWS API Gateway, or custom solution). Implement advanced features including intelligent routing with service discovery, request/response transformation, rate limiting with sliding window algorithms, circuit breaker patterns, authentication/authorization middleware, request/response logging with correlation IDs, and API versioning strategies. Include health checks, load balancing, caching strategies, and monitoring with Prometheus/Grafana. Provide configuration for multiple environments (dev, staging, prod) with environment-specific settings and security policies."
  ```

* **Generate OpenAPI Schema from Source Code**

  ```text
  "Given the following source code for a RESTful API implemented in {programming_language} with endpoints {list_of_endpoints}, generate an OpenAPI 3.0 schema that describes the API. The schema should include paths, request/response parameters, status codes, authentication methods, and other relevant details. Return the complete OpenAPI schema in YAML format."
  ```

* **Generate Curl Commands for Testing OpenAPI Endpoints**

  ```text
  "For the OpenAPI schema provided, generate `curl` commands to test the endpoints. Include examples for GET, POST, PUT, and DELETE requests. The `curl` commands should include the correct headers, body content (for POST/PUT), and any required authentication tokens (if applicable)."
  ```

* **Generate OpenAPI Schema for a Custom API with Source Code**

  ```text
  "Given the following source code for an API implemented in {programming_language}, generate the OpenAPI schema for this API. The schema should cover all routes, parameters, request/response types, and status codes. Include both request body and query parameters where applicable, and provide the schema in YAML format."
  ```

* **Create OpenAPI Schema and Curl Commands for a CRUD API**

  ```text
  "Create an OpenAPI schema for a simple CRUD API with the following endpoints: `GET /items`, `POST /items`, `PUT /items/{id}`, and `DELETE /items/{id}`. Based on the schema, generate `curl` commands to test these endpoints with sample data, including headers and request bodies as necessary."
  ```

* **Generate OpenAPI Schema for a Node.js API and Curl Examples**

  ```text
  "Given the following source code for a Node.js API using Express, generate the corresponding OpenAPI 3.0 schema. Then, create `curl` commands to test each endpoint in the API, covering all HTTP methods (GET, POST, PUT, DELETE) and including sample request bodies for each method."
  ```

* **Keploy CI/CD Integration Setup**

  ```text
  "Set up a CI/CD pipeline to automatically run Keploy tests as part of the deployment process. Include configuration for GitHub Actions or Jenkins to run tests whenever new code is pushed to the repository."
  ```
---

### **14. AI/ML Integration**

* **Mocking AI/ML Output in Spring Boot APIs**

  ```text
  "How can Keploy be used to capture and replay backend responses for APIs built with Spring Boot and AI/ML models (such as a spam/ham email classifier), ensuring consistent integration testing even when model outputs vary due to randomness or training state?"
  ```

* **Automated Keploy Testing for AI APIs in CI/CD Pipelines**

  ```text
  "Set up a CI/CD pipeline to automatically run Keploy tests as part of the deployment process. 
  Include configuration for GitHub Actions or Jenkins to run tests whenever new code is pushed to the repository."
  ```

* **Build a Text Classification Model Using Scikit-learn**

  ```text
  "You're a Python ML assistant. Build a binary text classifier using Scikit-learn.
  1. Load `sci.space` and `comp.graphics` from the 20 Newsgroups dataset.
  2. Preprocess using `TfidfVectorizer` (stop words removed, max_df=0.7).
  3. Split data 80/20.
  4. Train a `LogisticRegression` model.
  5. Evaluate with `classification_report`.
  Return: commented code, sample output, and a suggestion for improvement."
  ```

* **Fine-Tune a BERT Model for Sentiment Analysis**

  ```text
  "Fine-tune a BERT model using Hugging Face Transformers for sentiment analysis.
  1. Load IMDB or custom dataset.
  2. Tokenize using `BertTokenizer`.
  3. Use `Trainer` API for training and evaluation.
  4. Run prediction on new input.
  Return: training code, evaluation metrics, and how to save the fine-tuned model."
  ```

* **Build an Image Classifier Using CNN (Keras/TensorFlow)**

  ```text
  "Build an image classification model using CNN in TensorFlow/Keras.
  1. Load CIFAR-10 dataset.
  2. Normalize and augment images.
  3. Create a CNN model with Conv2D, MaxPooling, and Dense layers.
  4. Train and evaluate the model.
  Return: training accuracy graph and confusion matrix."
  ```

* **Detect Anomalies in Streaming Data Using Isolation Forest**

  ```text
  "Simulate real-time anomaly detection using Isolation Forest.
  1. Generate synthetic streaming data.
  2. Train Isolation Forest on initial batch.
  3. Detect and flag anomalies in subsequent batches.
  Return: Python code with anomaly detection logic and visualization using matplotlib."
  ```

* **Deploy a Machine Learning Model Using FastAPI**

  ```text
  "Create a FastAPI service to serve ML predictions.
  1. Train and save a Scikit-learn model (e.g., RandomForest).
  2. Build a FastAPI app with a `/predict` endpoint.
  3. Accept JSON input and return predictions.
  Return: Python code for API setup and example API call with curl."
  ```

* **Tune Hyperparameters of XGBoost Using Optuna**

  ```text
  "Use Optuna to find optimal hyperparameters for an XGBoost model.
  1. Load any tabular dataset (e.g., Titanic).
  2. Define objective function for `study.optimize()`.
  3. Output best parameters and accuracy.
  Return: Python code with study summary and plot."
  ```

* **Build a PDF Q&A Bot Using LangChain and FAISS**

  ```text
  "Create a bot that answers questions from a PDF using LangChain and FAISS.
  1. Extract text using PyMuPDF.
  2. Generate embeddings with Hugging Face.
  3. Store vectors in FAISS.
  4. Use LangChain’s Retriever to answer queries.
  Return: complete pipeline and example Q&A results."
  ```

* **Train a Regression Model Using PyCaret**

  ```text
  "Build and evaluate a regression model using PyCaret.
  1. Load a housing dataset.
  2. Use `setup()`, `compare_models()`, and `predict_model()` functions.
  3. Analyze performance (R², MAE).
  Return: code with minimal effort using PyCaret."
  ```

* **Generate Synthetic Data Using SDV for Tabular ML Tasks**

  ```text
  "Use SDV to generate synthetic tabular data.
  1. Load a real CSV dataset.
  2. Train SDV's `GaussianCopula` model.
  3. Generate synthetic samples.
  4. Compare real vs. synthetic distributions.
  Return: Python code with evaluation using `sdmetrics`."
  ```

* **Real-Time Face Recognition System Using OpenCV**

  ```text
  "Build a real-time face recognition system using OpenCV and face encodings.
  1. Load and encode known faces.
  2. Capture webcam video and detect faces.
  3. Match detected faces with known encodings.
  Return: working code with recognition overlay on video."
  ```

* **Scaffold Django REST API from Specification**  
  
  ```text
  "Given a model name and its fields, generate Django model code, serializer, views (class-based using DRF), and URL configuration to build a complete CRUD API. Also include sample cURL requests and instructions for enabling JWT authentication in settings.py."
  ```
 
* **Exploratory Data Analysis (EDA) with Recommendations**

  ```text
  "Perform an in-depth exploratory data analysis on the given dataset (CSV format). Identify key trends, missing values, outliers, and feature correlations. Summarize findings and suggest three actionable insights for business decision-making."
  ```

* **Feature Engineering Automation**

  ```text
  "Here is the header format of the dataset and also the attached csv file for a binary classification problem with both categorical and numerical features, generate automated feature engineering steps using modern libraries (e.g., Featuretools, Scikit-learn). Include encoding, transformations, and feature selection methods."
  ```

* **ML Model Deployment with FastAPI**

  ```text
  "Wrap this trained machine learning model into a FastAPI app for real-time inference. Include endpoint for /predict, input schema validation using Pydantic, and Dockerfile for containerization. Give me the production level organization of code. Prefer to modularize the provided model if needed to enhance code readability. Provide me with the detailed python code with annotations.

  Here is the model:
  <model implementation or functions>"
  ```
* **Resume Compatibility Evaluator**  
 
 ```text
    "Create a prompt chain that takes as input a resume and job description. The output should include: a compatibility percentage, key aligned skills, missing qualifications, and actionable improvement tips for better job matching."
  ```
  
* **Set Up ML Model Monitoring**

```text
  Design a system to monitor the performance and drift of a deployed machine learning model. Include steps for collecting model metrics, setting up alerts, and visualizing results. Return a sample configuration and explanation.
```

* **Automate ML Pipeline Deployment**

```text
  Create a pipeline to automate the training, evaluation, and deployment of a machine learning model using {tool/framework}. Return the pipeline definition and instructions for setup.
```

* **Explain Model Interpretability Techniques**

```text
  Explain the key techniques for interpreting and explaining machine learning model predictions, such as SHAP, LIME, or feature importance. Provide example code for one technique.
```
 
---

### **15. Testing & Quality Assurance**

* **Write Unit Testing for a Function**

  ```text
  "Write unit tests for the following function in {programming_language}: {function_name}. The tests using Jest or Mocha."
  ```

* **Set Up Integration Tests for REST APIs**

  ```text
  "Set up integration testing for the provided REST API using a testing framework like Supertest or Postman/Newman. Include tests for success cases, validation errors, and authentication flows."
  ```

* **Test REST APIs for Functional and Edge Cases**

  ```text
  "Write a comprehensive API test suite for the following RESTful endpoints using a tool like Postman, REST Assured, or Supertest. Include  tests for valid inputs, invalid inputs, edge cases, and authorization scenarios. Validate response status codes, payload structures, and headers. Return test scripts or collection exports along with a description of each test case."
  ```
---

### **16. Agentic AI**

* **Design a Multi-Agent Workflow**  
   ```text
   "Outline a multi-agent workflow for {task} using frameworks like LangGraph or CrewAI. Define each agent’s role (e.g., DataCollector, Planner, Executor, Verifier), their inputs/outputs, and how they communicate. Provide a sequence diagram or step-by-step description."
   ``` 

* **Implement an Agent with Memory**

   ```text
   "Show me how to implement an agent in Autogen that persists conversation history and key facts in ChromaDB. Include code snippets (e.g., using the langchain or CrewAI SDK) for saving, retrieving, and integrating memory into prompts."
   ```

* **Agent Task Delegation Strategy**

   ```text
   "Given a high-level goal (e.g., ‘Analyze market trends and generate a summary report’), write a prompt chain that uses LangGraph to break it into subtasks, assigns them to specialized agents, and then aggregates their outputs."
   ```

* **Error Handling & Recovery in Agents**

   ```text
   "Demonstrate how to detect and handle failures in an autonomous agent pipeline built with CrewAI (e.g., a web-scraping agent times out). Provide prompt or code templates for retry logic, fallback strategies, and alerting."
   ```

* **Evaluate Agent Performance Metrics**

   ```text
   "Define quantitative and qualitative metrics (e.g., task completion rate, avg. response time, accuracy) to evaluate an autonomous agent’s performance in Autogen, and show how to log and visualize these using a monitoring framework like Prometheus or Grafana."
   ```

* **Agent Orchestration with LangGraph**

   ```text
   "Write a LangGraph configuration that orchestrates three agents—ResearchAgent, AnalysisAgent, and NotificationAgent—with dependencies and data passing defined. Include sample YAML or JSON."
   ```

* **Secure Agent Actions**

   ```text
   "Explain best practices for sandboxing or restricting file, network, and system access for agents running under CrewAI. Provide examples of how to configure Docker containers or Kubernetes PodSecurityPolicies to enforce them."
   ```

* **Dynamic Prompt Refinement**

   ```text
   "Show how an Autogen agent can use its own logs or feedback loop to refine its prompts over time—e.g., if its summaries are too verbose, adjust the prompt to be more concise. Include code or pseudo-code in Python."
   ```

* **Integrate External APIs in Agents**

   ```text
   "Create a prompt template and runtime code for a LangGraph agent that fetches real-time stock prices from Alpha Vantage, processes them, and makes buy/sell decisions. Show how to plug in API keys and error handling."
   ```

* **End-to-End Agentic AI Demo**

    ```text
    "Compose a high-level README or tutorial that walks through building, testing (using Keploy), and deploying an agentic AI system with CrewAI or Autogen: from local development, through CI/CD, to production orchestration and monitoring."
    ```
    
---

### **17. RAG Application Development**

* **Generate a Complete RAG App Codebase (Python + LangChain)**  
  
  ```text
  ""You're a senior AI engineer. Build a modular Retrieval-Augmented Generation (RAG) application in Python using LangChain and ChromaDB. The application should support:

  1. Document ingestion from PDF, Markdown, and CSV formats.
  2. Text preprocessing with chunking and metadata tagging.
  3. Embedding generation using either OpenAI or HuggingFace Transformers.
  4. Persistent vector store setup with ChromaDB (local mode).
  5. A retrieval pipeline that supports top-k semantic search.
  6. An interactive QA interface using Streamlit for user queries and answer display.

  Ensure code quality with modular file structure, comments, and environment setup files (requirements.txt). Use best practices for scalability and readability."
  "
  ```

* **Create a FastAPI Backend for RAG App**

  ```text
  "You're a senior AI backend engineer. Build a FastAPI-based backend to serve a Retrieval-Augmented Generation (RAG) pipeline using LangChain or custom Python modules. The backend should expose relevant endpoints for uploading documents, querying questions, and retrieving responses — as defined in the user requirements. Integrate with a vector store like ChromaDB, and implement the RAG pipeline components: document ingestion, chunking, embedding, retrieval, and answer generation. Follow modular design principles and structure the codebase to support scalability, clarity, and future extension. Ensure the implementation meets the functional needs as defined above."
  "
  ```

* **Set Up Vector Store with ChromaDB**

  ```text
  "Provide Python code to set up a local ChromaDB instance for storing and querying document embeddings. Include functionality for creating collections, adding documents, and retrieving the top-k similar results for a user query."
  ```

* **Use HuggingFace Embeddings with FAISS**

  ```text
  "Write a Python script using HuggingFace Transformers to convert documents into embeddings and store them in a FAISS index. Enable functionality to search and retrieve the most relevant chunks based on cosine similarity."
  ```

* **Build a Streamlit UI for a RAG Chatbot**

  ```text
  "Create a Streamlit interface for a Retrieval-Augmented Generation chatbot. Allow users to upload files, ask questions, and receive contextual answers. Integrate with a backend that uses a vector store and a language model."
  ```

* **Generate Preprocessing & Chunking Pipeline**

  ```text
  "Design a text preprocessing and chunking pipeline for RAG. The pipeline should clean text, split it into overlapping chunks, and tag each chunk with metadata such as source, index, or timestamp. Optimize for embedding and retrieval accuracy."
  ```

* **LangChain RetrievalQA Pipeline with Prompt Template**

  ```text
  "Set up a RetrievalQA pipeline in LangChain using FAISS and OpenAI embeddings. Load documents, embed them, and create a prompt template to retrieve concise and context-aware answers to user queries."
  ```

* **Develop RAG App with Local LLM (e.g. Mistral-7B)**

  ```text
  "Build a RAG pipeline using a local language model like Mistral-7B. Include document ingestion, embedding via SentenceTransformers, ChromaDB for retrieval, and local inference for generating final answers."
  ```

* **Enable PDF Upload and Parsing for RAG**

  ```text
  "Add functionality to allow users to upload PDFs. Extract the text using PyMuPDF or pdfminer and convert it into clean, chunked segments for embedding and storage in the RAG pipeline."
  ```

* **Deploy RAG App on Render or Railway**

  ```text
  "Provide deployment instructions to host a RAG application on Render or Railway using FastAPI or Streamlit. Include a requirements.txt, Procfile, or Dockerfile for proper environment setup and execution."
  ```

---