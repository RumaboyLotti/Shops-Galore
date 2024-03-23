# Java Web Store with React and Spring Boot

This Java capstone project is a web store application that offers a platform for users to buy and sell products. The application is built using React for the frontend, Spring Boot for the backend, and integrates with Stripe as the payment service provider.

## Technologies Used

- React
- Spring Boot
- Stripe API
- JavaScript
- HTML/CSS
- Java

## Features

- User authentication and authorization
- Product browsing, searching, and filtering
- Product listing and management for sellers
- Shopping cart functionality
- Secure payment processing with Stripe
- Order tracking and history
- Responsive design for various devices

## How to Use

1. Clone this repository to your local machine.
2. Set up the backend by navigating to the `backend` directory and running `./mvnw spring-boot:run`.
3. Set up the frontend by navigating to the `frontend` directory and running `npm install` followed by `npm start`.
4. Access the web store through your browser at `http://localhost:3000`.

## Backend Setup

- The backend is built with Spring Boot and uses Maven as the dependency management tool.
- Database configuration and other settings can be found in the `application.properties` file.
- Ensure that the required dependencies are installed and configured before running the backend server.

## Frontend Setup

- The frontend is developed with React and utilizes npm for package management.
- Make sure to install the required dependencies by running `npm install` before starting the frontend server.

## Payment Integration with Stripe

- To enable payment processing, you need to create an account on the Stripe website (https://stripe.com).
- Obtain your API keys from the Stripe dashboard and configure them in the backend code.
- Ensure that the frontend and backend communicate securely with Stripe's API for payment transactions.

## Folder Structure

- `backend`: Contains the Spring Boot backend code.
- `frontend`: Contains the React frontend code.
- `docs`: Additional documentation files.
- `README.md`: Project overview and setup instructions.
- `LICENSE`: Project license file.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
