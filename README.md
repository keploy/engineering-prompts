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

---

## Use Cases and Prompts

### **1. Code Refactoring & Development**

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
  "Please analyze the provided code and explain its functionality step-by-step. Include explanations for each major part of the code and why it’s necessary. Keep the explanation clear and concise."
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

* **Test for Regressions After Refactoring Code with Keploy**

  ```text
  "After refactoring the code, use Keploy to run automated tests to check if any regressions have been introduced. Set up Keploy to verify that the refactored code behaves as expected, ensuring that all existing functionalities remain intact. The tests should include integration tests to verify that API endpoints, data handling, and user interactions still function properly. Ensure that Keploy is set to compare the current behavior with previously recorded test cases to detect any discrepancies or regressions. Return the Keploy test configuration, test cases, and results showing the behavior of the refactored code."
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

---

### **3. Database Management**

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

---

### **6. UX/UI & Design**

* **Provide UX/UI Design Advice**

  ```text
  "Provide UX/UI design recommendations for the provided {website/app}. Focus on improving usability, accessibility, and aesthetics. Return a list of specific design improvements with examples where necessary."
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

---

### **8. Event-Driven Architecture & Integration**

* **Set Up an Event-Driven Architecture with Kafka**

  ```text
  "Set up an event-driven architecture with Kafka. Define the Kafka topics, producers, and consumers to handle real-time data processing. Return the code with configuration details."
  ```

* **Help Integrate Third-Party Services**

  ```text
  "Integrate {third_party_service} into the existing project. Provide step-by-step instructions for setup, authentication, and API interaction. Return the integration code with explanations of how it works."
  ```

---

### **9. Content Creation & Marketing**

* **Create a Personal Portfolio Website**

  ```text
  "Help me build a personal portfolio website. The site should include sections for my bio, projects, skills, and contact information. Make sure it’s responsive and easy to navigate. Return the basic HTML/CSS/JS code for the website."
  ```

* **Write SEO-Optimized Blog Content**

  ```text
  "Generate a blog post on {topic} optimized for SEO. Use keyword research to include high-traffic keywords naturally, structure the post with headings and subheadings, and ensure it is engaging and informative. Return the content with SEO suggestions."
  ```

* **Generate LinkedIn Summary and Job Descriptions**

  ```text
  "Generate a compelling LinkedIn summary and job description based on the following details: {job_title}, {skills}, {experience}. Ensure the summary is concise, professional, and highlights key achievements."
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

---

### **11. System Monitoring & Debugging**

* **Debug Performance Issues in Production Systems**

  ```text
  "Analyze the performance of the production system and identify bottlenecks. Suggest and implement optimizations to improve speed, reduce memory usage, and increase scalability. Return the optimized code and explanations."
  ```

---

### **12. Web Development**

* **Write Tests for Front-End Components**

  ```text
  "Write unit and integration tests for the provided front-end components using {testing_framework}. Ensure the tests cover all major use cases and edge cases. Return the test code with explanations."
  ```

---

### **13. API Development**

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

### **14. AI / ML**

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