# Customer Application REST APIs
* **Create a Customer:** User can create a customer with valid details.
* **Update a Customer:** User can update an existing customer's details by customerId.
* **Retrieve Customers:** User can retrieve specific customer by customerId.
* **Retrieve Customers Pages:** User can retrieve customers based on pageSize, pageNumber, ascending and descending order.
* **Delete a Customer:** User can delete a customer by customerId.
* **Sync Customers data from SUNBASE API:** User can Sync Customers data from SUNBASE database.
## Technologies Used
* **Java 8+**
* **Spring Boot**
* **Spring MVC**
* **Spring Data JPA**
* **JWT Authentication**
* **MySQL (as the database)**
* **Maven (for dependency management)**

## Prerequisites
* Java Development Kit (JDK) version 8 or higher
* Spring Boot
* Maven

## Getting Started
To set up the project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/Amit8127/Customer-APIs.git`
2. Navigate to the project directory: `cd Customer-APIs`
3. Configure the database settings in `application.properties` file.
4. Build the project using Maven: `mvn clean install`
5. Run the application: `mvn spring-boot:run`
6. The application will be accessible at `http://localhost:8080`.

## Database Setup
This project uses MySQL as the database. Follow these steps to set up the database:
1. Install MySQL on your local machine.
2. Create a new database named customerData.
3. Update the database configuration in `application.properties` file.

## SignUp ScreenShot
![Img1.png](src%2Fmain%2Fjava%2Fcom%2Fdriver%2FImages%2FImg1.png)

## Login ScreenShot
![Img2.png](src%2Fmain%2Fjava%2Fcom%2Fdriver%2FImages%2FImg2.png)

## Table ScreenShot
![Img3.png](src%2Fmain%2Fjava%2Fcom%2Fdriver%2FImages%2FImg3.png)

## Add Customer Form
![Img4.png](src%2Fmain%2Fjava%2Fcom%2Fdriver%2FImages%2FImg4.png)

