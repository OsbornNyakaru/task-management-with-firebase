# Task Management with Firebase

## Description

Task Manager is a simple web application designed to help users organize their tasks. With Task Manager, users can easily add new tasks, delete existing tasks, and keep track of their to-do list efficiently.

## Features

- **Add Tasks**: Users can add new tasks by typing the task description in the input field and clicking the "Add Task" button.
- **Delete Tasks**: Users can remove tasks from the list by clicking the delete button next to each task.
- **Firebase Integration**: Task Manager utilizes Firebase Firestore for storing tasks, providing a seamless and scalable solution for data management.

## Technologies Used

- HTML: Structure of the web application.
- CSS: Styling the user interface to enhance the user experience.
- JavaScript: Adding interactivity and functionality to the application.
- Firebase Firestore: Cloud-hosted NoSQL database for storing and syncing data in real-time.

## Getting Started

To run Task Manager locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.

### Firebase Setup

To enable Firestore for Task Manager:

1. Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
2. Add a web app to your Firebase project.
3. Copy your Firebase configuration (apiKey, authDomain, projectId, etc.) and replace the placeholders in `app.js` with your actual Firebase configuration.
4. Enable Firestore in your Firebase project.

## Folder Structure

