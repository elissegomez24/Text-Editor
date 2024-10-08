# Text Editor

## Description

A simple text editor application built with modern web technologies, featuring a Progressive Web App (PWA) setup, IndexedDB for storage, and a service worker for offline functionality.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Screenshots](#screenshots)
- [Deployment on Render](#deployment-on-render)
- [Deployed Application](#deployed-application)
- [License](#license)

## Features

- Create, edit, and delete text documents.
- Offline functionality via a service worker and IndexedDB.
- Installation as a PWA on supported devices.
- Intuitive and responsive user interface.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Build Tool:** Webpack
- **Service Worker:** Workbox
- **Storage:** IndexedDB
- **Backend:** Node.js, Express

## Installation

1. Clone the repository:
2. Navigate to both the client and server directories to install dependencies:

- cd client: npm install
- cd ../server: npm install

## Usage

1. Development

- To run the server and client concurrently during development, use- npm run start:dev
- This command uses concurrently to run both the client and server in development mode.

2. Building for Production

- To build the application for production, run- npm run build
- This will generate the optimized files in the dist directory of the client.

3. Running the Application

- After building for production, start the server- npm run start
- Start the development server- npm run start
- Open live server or go to the configured port.
- Use the application to create and manage text documents.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Screenshots

![Text-Editor/images/Text Editor1.png](<images/Text Editor1.png>)
![Text-Editor/images/Text Editor2.png](<images/Text Editor2.png>)
![Text-Editor/images/Text Editor3.png](<images/Text Editor3.png>)
![Text-Editor/images/Text Editor4.png](<images/Text Editor4.png>)

## Deployment on Render

To deploy the application using Render:

1. **Push to GitHub**
2. **Deploy on Render**
3. **Access Your Application**

## Deployed Application

https://text-editor-jo56.onrender.com

## License

This project is licensed under the [MIT LICENSE](LICENSE).

> [!NOTE]  
> Recourses used for creating code. Referred back to class work for file format such as reviewing class recording. Worked with peers on assignment and compared challenge template to assist with creating readme file.
