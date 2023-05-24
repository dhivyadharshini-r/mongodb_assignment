# Schedule-REACT-APP
# React app using  Node.js, Express.json, and MongoDB Atlas Project in Visual Studio Code

This README file provides an outline and command for setting up the Schedule REACT APP that combines React for the frontend, Node.js with Express for the backend server, and MongoDB Atlas for the database using Visual Studio Code as the development environment.

## Prerequisites

Before progressing, make sure you have the following installed:

- Visual Studio Code: Download and install Visual Studio Code from the website [https://code.visualstudio.com](https://code.visualstudio.com).

- Node.js: Make sure that that you have installed Node.js in your system. You can download it from [https://nodejs.org](https://nodejs.org) and follow the installation instructions for your operating system.(version 12 or above)

- MongoDB Atlas: Construct a MongoDB Atlas cluster by following the instruction on [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).(version 4 or above)

## Project Setup

1. Open Visual Studio Code and navigate the project directory where you want to create your project.

2. Clone the project repository from GitHub:
   ```
   git clone https://github.com/Dhivya/Schedule-REACT-APP.git
   ```

3. Open the project folder in Visual Studio Code:
   ```
   cd nosql
   code .
   ```

4. Install the required dependencies:
   - Open the integrated terminal in Visual Studio Code: View -> Terminal.
   - Run the following command to install the dependencies for the backend server:
     ```
     cd backend
     npm install
     ```

   - Run the following command to install the dependencies for the React frontend:
     ```
     cd frontend
     npm install
     ```

5. Configure environment variables:
   - Create a `.env` file in the root of the `server` folder.
   - Add the following environment variables to the `.env` file:
     ```
     PORT= 5000
     MONGODB_URI=mongodb+srv://dineshvc33:dineshvc33@cluster0.5facuqt.mongodb.net/CRUD_DB?retryWrites=true&w=majority
     ```

## Running the Application

1. Start the backend server:
   - Open seperate terminal in Visual Studio Code: View -> Terminal.
   - Run the following command in the terminal:
     ```
     cd backend
     npm run dev
     ```

2. Start the React app:
   - Open a new separate terminal in Visual Studio Code: View -> Terminal.
   - Run the following command in the terminal:
     ```
     cd frontend
     npm start
     ```

The React app will be accessible at `http://localhost:3000`, and the Node.js backend server will be running at the defined port.

## Project Structure

The project structure is organized as follows:

  - `/frontend`: Contains the React frontend application.
  - `/backend`: Contains the Node.js backend server.
  - `/routes`: Contains the API routes for user authentication and reservation related operations.
  - `/controllers`: directory contains the controllers for handling different functionalities.
  - `/models`: directory contains the database models for reservation.
  - `server.js`: Entry point for the server.

Feel free to modify and extend the project structure based on your requirements.

## API Endpoints

The Node.js server provides the following API endpoints for task management:

- **GET /api/tasks** - Retrieves all tasks.
- **POST /api/tasks** - Creates a new task.
- **GET /api/tasks/:id** - Retrieves a specific task by ID.
- **PUT /api/tasks/:id** - Updates a specific task by ID.
- **DELETE /api/tasks/:id** - Deletes a specific task by ID.

Make sure to make the appropriate HTTP requests to these endpoints to perform  the task management operations.

The backend server provides API endpoints for interacting with the MongoDB Atlas database. You can define your own routes and controllers to handle defined functionalities.

## APP Functionalities

The Schedule app provides the following features:

- **Get Task**: Fetches the list of tasks from the server and displays them.
- **Update Task**: Allows users to update the details of the user.
- **Delete Task**: Enables users to delete the operation from the list.
- **Select Task**: Allows users to mark the operation as selected.

You can further customize and enhance these features based on your specific needs.

## Additional Resources

- React documentation: [https://reactjs.org/docs](https://reactjs.org/docs)
- Express documentation: [https://expressjs.com](https://expressjs.com)
- MongoDB Atlas documentation: [https://docs.atlas.mongodb.com](https://docs.atlas.mongodb.com)
- Visual Studio Code documentation: [https://code.visualstudio.com/docs](https://code.visualstudio.com/docs)
