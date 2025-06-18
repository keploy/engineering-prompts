# **1. Code Refactoring & Development**

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