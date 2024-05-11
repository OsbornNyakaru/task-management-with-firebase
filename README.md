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

##File Structure 

task-manager/
│
├── index.html
├── style.css
├── app.js
└── README.md


- `index.html`: Main HTML file for the web application.
- `style.css`: CSS file for styling the user interface.
- `app.js`: JavaScript file for application logic and Firebase integration.

## Contributing

Contributions to Task Manager are welcome! If you'd like to contribute to this project, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



