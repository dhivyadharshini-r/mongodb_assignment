Railway Reservation System

This is a Railway Reservation System developed using MongoDB and Node.js. The system allows users to book train tickets, check seat availability, and manage reservations.

## Features

- User Registration: Users can create an account and login to the system.
- Train Search: Users can search for trains based on the source and destination stations.
- Seat Availability: Users can check the availability of seats on a specific train.
- Ticket Booking: Users can book tickets for a selected train and specify the number of seats.
- Reservation Management: Users can view and manage their reservations, including canceling bookings.
- Admin Dashboard: Admins have access to a dashboard where they can manage trains, stations, and users.

## Technologies Used

- Node.js: A JavaScript runtime environment for server-side development.
- Express.js: A web application framework for Node.js.
- MongoDB: A NoSQL database for storing and retrieving data.
- Mongoose: An object modeling tool for MongoDB in Node.js.

## Prerequisites

- Node.js and npm must be installed in the system.
- MongoDB installed and running locally or a remote MongoDB database connection string.

## Installation

1. Clone the repository:

   
   git clone https://github.com/dhivya/railway-reservation-system.git
   

2. Navigate to the project directory:

   
   cd railway-reservation-system
   

3. Install the dependencies:

   
   npm install
   

4. Create a `.env` file in the root directory and add the following environment variables:

   
   MONGODB_URI=<your-mongodb-connection-string>
   SECRET_KEY=<your-secret-key>
   

5. Start the application:

   
   npm start
   

6. Open your browser and visit `http://localhost:3000` to access the application.


## Usage

1. Open the application in your browser and create a user account.
2. Log in using your credentials.
3. Use the search form to find trains between specific source and destination stations.
4. Check seat availability for a selected train.
5. Book tickets by providing the number of seats.
6. View and manage your reservations in the reservation section.
7. As an admin, log in using the admin account.
8. Access the admin dashboard to manage trains, stations, and users.

 

