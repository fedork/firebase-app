# Firebase App Hosting Project

This project is a simple Firebase application that demonstrates the use of Firebase Hosting and Cloud Functions. 

## Project Structure

```
firebase-app
├── public
│   ├── index.html       # Main HTML file for the application
│   ├── styles.css       # CSS styles for the application
│   └── app.js           # JavaScript code for client-side logic
├── functions
│   ├── index.js         # Entry point for Firebase Cloud Functions
│   └── package.json     # Configuration file for Cloud Functions
├── .firebaserc          # Firebase project configuration settings
├── firebase.json        # Configuration file for Firebase Hosting
└── README.md            # Documentation for the project
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd firebase-app
   ```

2. **Install Firebase CLI**:
   If you haven't already, install the Firebase CLI globally:
   ```bash
   npm install -g firebase-tools
   ```

3. **Initialize Firebase**:
   Run the following command to initialize Firebase in your project:
   ```bash
   firebase init
   ```

4. **Deploy the application**:
   To deploy your application to Firebase Hosting, run:
   ```bash
   firebase deploy
   ```

## Features

- **Firebase Hosting**: Serves the static files from the `public` directory.
- **Cloud Functions**: Allows you to run backend code in response to events triggered by Firebase features and HTTPS requests.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.