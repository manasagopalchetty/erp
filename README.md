1.1 Overview
This is designed to handle customer data management in an ERP system. It utilizes Spring Boot for creating RESTful APIs

1.2 Prerequisites
Java 8 or later
Maven
Apache Spark

2.1 Build and Run
bash
Copy code
mvn clean install
java -jar target/erp-customer-microservice.jar
3. APIs
3.1 Get All Customers
Endpoint: GET /api/customers
Description: Retrieves a list of all customers.
3.2 Get Customer by ID
Endpoint: GET /api/customers/{id}
Description: Retrieves details of a specific customer by ID.
3.3 Add New Customer
Endpoint: POST /api/customers
Description: Adds a new customer to the system.

3.4 Update Customer
Endpoint: PUT /api/customers/{id}
Description: Updates details of a specific customer by ID.
3.5 Delete Customer
Endpoint: DELETE /api/customers/{id}
Description: Deletes a customer from the system by ID.
Parameters:
{id}: Customer ID
4. Data Profiling with Apache Spark
4.1 Trigger Data Profiling
Endpoint: POST /api/data-profiling
Description: Triggers Apache Spark for data profiling.
4.2 Get Data Profiling Results
Endpoint: GET /api/data-profiling-results
Description: Retrieves the results of the data profiling.
5. Conclusion
This documentation provides an overview of the ERP customer , its APIs for customer management, and integration with Apache Spark for data profiling. Refer to this documentation for usage and integration details.
