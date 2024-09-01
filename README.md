
# Expense Tracker using MERN Stack


### Vercel Link: https://expense-tracker-app-three-beryl.vercel.app/

## Project Description:

Objective: Create an application that allows users to track their daily expenses.
Details: Use MongoDB for storing expense data, Express.js for server-side logic,
React.js for the front-end, and Node.js for backend operations. Include features
like adding, editing, and categorizing expenses.

## Technical Architecture:

- Frontend:

    Utilize React.js for building the user interface, tsparticle library for awesome background effect and used other libraries like unique-names-generator, react-datepicker, moment

    Implement responsive design using CSS frameworks like Bootstrap and Material-Icons.

- Backend:

    Use Node.js and Express.js to build a RESTful API for handling client requests and serving as the application's backend.

    Implement authentication and authorization using JSON Web Tokens (JWT) and middleware to protect endpoints.

- Database:

    Store all data, including user information, expense entries, and categories, in MongoDB, a NoSQL database.

    Implement Mongoose ORM for schema definition and validation.

- Deployment:

    Deploy the application to a cloud provider like AWS and render.
    frontend has deployed on AWS and backend on Render.

    Set up Continuous Integration and Continuous Deployment (CI/CD) pipelines for automated builds and deployments.
## Run Locally

Clone the project

```bash
  git clone https://github.com/Priyanshu9898/Expense-Tracker-App
```

Go to the project directory

```bash
  cd Expense-Tracker-App
```

Go to the frontend directory and Install dependencies

```bash
  cd frontend
```
```bash
  npm install
```

Go to the backend directory and Install dependencies

```bash
  cd backend
```
```bash
  npm install
```

Start the frontend server

```bash
  npm start
```


Start the backend server

```bash
  npm run dev
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in backend folder

create config folder and add config.env file in it and all all env variables there.

`MONGO_URL` : Your MongoDB Connection String

`PORT`: PORT number


## Tech Stack

**Client:** React, Redux, react-bootstrap, Material Icons, tsparticles

**Server:** Node, Express

**Database:** MongoDB


## Screenshots

![App Screenshot](https://i.postimg.cc/6qLR3WNt/Expense-Management-System-Brave-19-04-2023-11-08-53.png)

![App Screenshot](https://i.postimg.cc/DynLNXqZ/Expense-Management-System-Brave-19-04-2023-11-08-59.png)

![App Screenshot](https://i.postimg.cc/Dy6L3wgc/Expense-Management-System-Brave-19-04-2023-11-15-46.png)

![App Screenshot](https://i.postimg.cc/13YF47bn/Expense-Management-System-Brave-19-04-2023-11-15-54.png)

![App Screenshot](https://i.postimg.cc/rwpWV2Z2/Expense-Management-System-Brave-19-04-2023-11-16-01.png)








