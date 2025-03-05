# User-Management-System-with-React-Node.js
Problem Statement: User Management System with React & Node.js

This project involves the development of a simple User Management System where users can be added and displayed dynamically. The goal is to build a full-stack application using React for the frontend and Node.js with Express for the backend. Through this project, you will get hands-on experience with key concepts such as JSX, the Virtual DOM, functional & class components, props, and event handling in React.
User Stories & Tasks
User Story 1: Setup & Initialization

As a developer, I want to set up a project with Node.js and React so that I can start building the application.

Tasks:

    Initialize a Node.js project with Express to serve as the backend.
    Create a React project using Vite or Webpack manually, ensuring that you have control over the project configuration.
    Set up Webpack and Babel for React compilation, allowing the use of JSX and modern JavaScript features in your React code.

User Story 2: Backend API with Node.js

As a developer, I want to create an API in Node.js that provides user data so that my React frontend can fetch and display it.

Tasks:

    Set up an Express server in Node.js.
    Create a simple REST API endpoint (/users) that returns a list of users in JSON format.
    Enable CORS (Cross-Origin Resource Sharing) so that the React frontend can fetch data from the backend without running into issues with cross-origin requests.

User Story 3: Display Users in React

As a user, I want to see a list of users displayed dynamically so that I can view the available users.

Tasks:

    Create a functional component called UserList in React to display user data.
    Use fetch or axios to send a request to the backend API and retrieve the list of users.
    Render the list of users dynamically using JSX and leverage the Virtual DOM to efficiently update the UI when the user data changes.

User Story 4: Add a New User

As a user, I want to add a new user through a form so that I can dynamically update the list of users.

Tasks:

    Create a UserForm component with an input field and a submit button.
    Use state in React to manage the form input.
    On form submission, send a POST request to the backend API to add a new user to the database.
    Update the displayed user list dynamically after adding a new user, ensuring that the UI reflects the changes immediately using React state.

User Story 5: Understanding Component Types & Props

As a developer, I want to implement both functional and class components so that I understand their differences.

Tasks:

    Convert the UserList component into a class component to demonstrate the use of lifecycle methods (such as componentDidMount for fetching data).
    Pass the user data as props from the parent component to UserList.
    Implement event handling (such as for the form submission) to ensure that the application behaves as expected.

Expected Outcome

By the end of this project, participants should have:

    A working full-stack application using React and Node.js, where the frontend dynamically fetches and displays user data.
    Experience in setting up Webpack and Babel manually for compiling React code.
    A hands-on understanding of functional & class components, the use of props, and how event handling works in React.
    A clear understanding of the Virtual DOM and how React dynamically updates the UI based on state changes.
    Successfully submitting and displaying user data through the application, with the ability to both view and add users.
---------------------------------------------------------------------------------------------------------------------------------------------------------

This repository will guide you through creating a simple and functional user management system while building fundamental knowledge of React and Node.js concepts. The project will consist of both backend and frontend components working together to create a seamless user experience.
