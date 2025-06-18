# **13. API Development**

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
