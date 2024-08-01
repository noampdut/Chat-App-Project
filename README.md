# Chat App Project

#### Advanced project for the Advanced Programming course in Bar-Ilan University: Web Development Course

Welcome to the Chat App Project! This project includes three main components: an Android client, a React web client, and an ASP.NET server (with MongoDB connection). Below you'll find an overview of each component and links to their respective repositories.

## Overview
This chat application supports both web and Android platforms, allowing users to communicate seamlessly across devices. The project is divided into three main parts:

1. **ASP.NET Server**: Handles the backend logic, user authentication, and message storage.
2. **React Web Client**: A web-based client built with React for accessing the chat application via a browser.
3. **Android Client**: A mobile client built with Android Studio for accessing the chat application on Android devices.

## Repositories

### [ASP.NET Server](https://github.com/noampdut/Chat-Project-Server-Side-.NET-.git)
The server-side logic is implemented in ASP.NET. Follow the instructions in the repository to set up and run the server.

### [React Web Client](https://github.com/noampdut/Chat-Project-Frontend-Side.git)
The web client is built with React. Follow the instructions in the repository to set up and run the web client.

### [Android Client](https://github.com/noampdut/Chat-Project-Android-Side.git)
The mobile client is built with Android Studio. Follow the instructions in the repository to set up and run the Android client.

## Setup Instructions
To get the entire project running, follow these steps:

### Step 1: Run the ASP.NET Project (Server)
1. Clone the repository.
2. Navigate to the project directory.
3. Run `dotnet restore` to restore dependencies.
4. Run `dotnet run` to start the server on port 5001.

### Step 2: Run the React Web Client
1. Clone the repository.
2. Navigate to the `ex2/chat` directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the web client.

### Step 3: Run the Android Client
1. Clone the repository.
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Run the application on an emulator or physical device.

## User Credentials

### Admin Account
- **Username:** admin
- **Password:** n123456

### Additional Registered Users
- **Username:** noampdut
- **Password:** n123456
- **Username:** naama
- **Password:** n123456
- **Username:** ofek
- **Password:** n123456

### Additional Notes
- The server (API project) should be running on port 5001.
- In the settings page, enter the complete base URL, e.g., `http://10.0.2.2:5001/api/`.
- To add a new contact from the React client when the server is on the same computer, use `localhost:5001`.
- For chatting between two different devices, first log in, and once both devices are connected to the app, you can start chatting.

