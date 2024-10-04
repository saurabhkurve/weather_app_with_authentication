# Weather Application

This is a weather application that provides weather updates and forecasts. The application includes authentication features using Java Simple Authentication and Java Spring Boot for creating login and register APIs.

## Features

- User registration and login
- Weather updates and forecasts 
- Secure authentication

## Prerequisites

- Java 17 or higher
- Maven
- MySQL 

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/weather-application.git
    cd weather-application
    ```

2. Set up the database:
    - Create a new database named `weather_db`.
    - Update the `application.properties` file with your database credentials.

3. Build the project:
    ```sh
    mvn clean install
    ```

## Usage

1. Run the application:
    ```sh
    mvn spring-boot:run
    ```

2. Access the application at `http://localhost:8080`.

## API Endpoints

- `POST /user/register` - Register a new user
- `POST /user/login` - Login an existing user
