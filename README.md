# ChalkWars School Platform Documentation

## Project Overview

**ChalkWars School Platform** is a Single Page Application (SPA) developed using Angular 14 and Firebase. It serves as an educational platform that provides a seamless user experience with custom Bootstrap styling and Firebase backend integration.

- **Project URL:** [ChalkWars School Platform](https://echo-angular-project.web.app/login)
- **GitHub Repository:** [ChalkWars Firebase Angular](https://github.com/sagi-daniel/ChalkWars-firebase-angular.git)

## Features

- **User Authentication:** Secure login and registration using Firebase Authentication.
- **Real-time Database:** Data storage and synchronization with Firebase Realtime Database.
- **Custom Bootstrap Design:** Utilizes a customized Bootstrap theme for responsive and visually appealing UI.
- **Admin Dashboard:** Manage user accounts and view platform statistics.

## Technologies Used

- **Frontend:** Angular 14, TypeScript, HTML, CSS, SCSS, Custom Bootstrap
- **Backend:** Firebase (Authentication, Realtime Database)
- **Deployment:** Firebase Hosting

## Getting Started

To run this project locally, follow these steps:

### 1. Clone the Repository

``` 
git clone https://github.com/sagi-daniel/ChalkWars-firebase-angular.git
cd ChalkWars-firebase-angular
```

### 2. Install Dependencies
Make sure you have Node.js and Angular CLI installed. Then, install the project dependencies:
```
npm install
```

### 3. Set Up Firebase
- Go to Firebase Console [https://console.firebase.google.com].
- Create a new Firebase project or use an existing one.
- Register your application and get the Firebase configuration details.
- Replace the configuration details in src/environments/environment.ts and src/environments/environment.prod.ts.

### 4. Run the Application
Start the Angular development server:
```
ng serve
```
Open your browser and go to [http://localhost:4200] to view the application

## Deployment 
To deploy the application to Firebase Hosting:

+ Install Firebase CLI if not already installed:
```
npm install -g firebase-tools
 ```
+ Log in to Firebase:
```
firebase login
 ```
+ Initialize Firebase in the project directory:
```
firebase init
 ```
Follow the prompts to set up Firebase Hosting.

+ Deploy the application:
```
ng build --prod
firebase deploy
```

### Project Structure

- src/: Source files for the Angular application.
  - app/: Main application folder containing components, services, and modules.
  - environments/: Environment-specific configuration files.
  - assets/: Static assets such as images and styles.
- angular.json: Angular CLI configuration file.
- firebase.json: Firebase Hosting configuration file.
- package.json: Project dependencies and scripts.

### Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request with a clear description of the changes.

### Contact
For any questions or issues, please reach out to:
- Email: dsagi727@gmail.com
- GitHub: sagi-daniel
