# Bus Ticket Booking System

Welcome to the Bus Ticket Booking System repository! This project is developed using the MERN (MongoDB, Express.js, React, Node.js) stack with TypeScript for building a comprehensive online platform for booking bus tickets.

## Project Overview

The Bus Ticket Booking System aims to provide users with a convenient and user-friendly way to search for bus routes, book tickets, and manage their travel plans online.

## Folder Structure

The project is organized into two main folders:

- **frontend**: This folder contains the React frontend application. It provides the user interface for searching routes, selecting seats, making bookings, and managing bookings.

- **backend**: This folder contains the Node.js backend application. It handles user authentication, booking processing, database management, and communication with external services.

## Features

- User Registration and Authentication: Users can create accounts and log in securely to access booking features.
- Route Search: Users can search for available bus routes, departure times, and fares.
- Seat Selection: Users can choose their preferred seats and view seat availability.
- Booking Management: Users can view their booking history, upcoming trips, and cancel bookings.
- Admin Dashboard: Admins can manage bus routes, schedules, fares, user accounts, and bookings.
- Payment Integration: Secure online payment processing through payment gateways.
- Notifications: Users receive booking confirmation and reminders via email or SMS(not implemented yet).
- Responsive Design: User-friendly interface accessible across various devices.

## Technology Stack

- Frontend: React (TypeScript), Redux
- Backend: Node.js (TypeScript), Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Payment Gateway Integration: Stripe.
- Hosting: not hosted yet

## Getting Started

1. Clone the repository using `git clone https://github.com/riaadmorshed/bus-ticket-booking.git`.
2. Navigate to the `frontend` folder and run `yarn install` to install frontend dependencies.
3. Navigate to the `backend` folder and run `yarn install` to install backend dependencies.
4. Configure environment variables in `.env` files (both frontend and backend) for database connection, API keys, etc.
5. Start the frontend development server using `yarn run dev` in the `frontend` folder.
6. Start the backend server using `yarn run dev` in the `backend` folder.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore, modify, and enhance the Bus Ticket Booking System. Happy coding!