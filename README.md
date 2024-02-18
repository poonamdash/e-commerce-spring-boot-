# E-Commerce Spring Boot Application

This is a sample e-commerce application built using Spring Boot. It provides basic functionality for managing products, customers, and orders.

## Features

- **Product Management**: CRUD operations for managing products.
- **Customer Management**: CRUD operations for managing customers.
- **Order Management**: Place orders and view order history.
- **Authentication**: Secure endpoints using Spring Security.

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf (for templating)
- MySQL (or any other database of your choice)

## How to Run

1. Clone the repository: `git clone https://github.com/poonamdash/e-commerce-spring-boot.git`
2. Navigate to the project directory: `cd e-commerce-spring-boot`
3. Build the project: `mvn clean install`
4. Run the application: `mvn spring-boot:run`
5. Access the application at `http://localhost:8080`

## Configuration

- Database configuration: Update `application.properties` with your database settings.
- Security configuration: Update `SecurityConfig.java` with your authentication requirements.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
