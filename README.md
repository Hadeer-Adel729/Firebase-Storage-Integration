Overview
--------
This project demonstrates the integration of Firebase storage into a web application. Users can upload , retrieve, and delete images which are stored in Firebase Storage and their corresponding URLs are saved in the Firebase Realtime Database. by entering their user ID. Each user must enter their ID to log in or sign up, ensuring secure access to their files.

Web Application
---------------
Firebase Hosting and JavaScript Client:

-Create a webpage and deploy it using Firebase hosting.

-Use JavaScript to access the Firebase database and read the links node.

-Dynamically display the download links in a table format on the webpage.

-Each download link will have a delete button beside it; clicking that button should delete the corresponding record from the database.

Firebase Configuration
----------------------
1.Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/u/0/).

2.Enable Firebase Storage and Firebase Realtime Database in the Firebase Console.

3.Add your web app to the same Firebase project.

4.Obtain your Firebase project's configuration object (      firebaseConfig).

5.Replace the placeholder values in the firebaseConfig object in the HTML file with your Firebase project's configuration.

Deploy Web Application
-----------------------
Use these commands:

1.Install the Firebase CLI:

      npm install -g firebase-tools

Initialize Firebase in your project directory:

      firebase init
  
Deploy your web application:

      firebase deploy

Hosting
-------
You can access the hosted application at:

[Firebase Image Integration App](https://webapp-b7d29.web.app)
