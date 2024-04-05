# PWA-TextEditor

## Contents
- [Description](#description)
- [Dependencies](#require)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)

## Description

This Progressive Web Application is a comprehensive digital organizer, providing users with a centralized platform to store and manage all their essential information and resources. One of its standout features is its offline capability, allowing users to access and utilize the application without an internet connection. Whether jotting down notes, saving code snippets, or organizing tasks, this PWA ensures that users can seamlessly access their data anytime, anywhere, making it a versatile and reliable tool for enhancing productivity and efficiency.

## Dependencies

- "dependencies": 
    - "express": "^4.19.2",
    - "if-env": "^1.0.4",
    - "code-mirror-themes": "^1.0.0",
    - "idb": "^6.1.2",
    - "express": "^4.17.1"
  
- "devDependencies": 
    - "concurrently": "^5.3.0",
    - "nodemon": "^2.0.22",
    - "@babel/core": "^7.15.0",
    - "@babel/plugin-transform-runtime": "^7.15.0",
    - "@babel/plugin-proposal-object-rest-spread": "^7.20.7",
    - "@babel/preset-env": "^7.15.0",
    - "@babel/runtime": "^7.15.3",
    - "babel-loader": "^8.2.2",
    - "css-loader": "^6.2.0",
    - "html-webpack-plugin": "^5.3.2",
    - "http-server": "^0.11.1",
    - "style-loader": "^3.2.1",
    - "webpack": "^5.51.1",
    - "webpack-cli": "^4.8.0",
    - "webpack-dev-server": "^4.0.0",
    - "webpack-pwa-manifest": "^4.3.0",
    - "workbox-webpack-plugin": "^6.2.4",
    - "nodemon": "^2.0.4"


## Installation

There is some installation requred:

- Dependencies need to run the application. First, you will need to run the following code:

    - "start:dev": 
    ```
    concurrently \"cd server && npm run server\" \"cd client && npm run dev\"
    ```
    - "start":
    ```
    npm run build && cd server && node server.js
    ```
    - "server":
    ```
    cd server nodemon server.js --ignore client
    ```
    - "build":
    ```
    cd client && npm run build
    ```
    - "install":
    ```
    cd server && npm i && cd ../client && npm i
    ```
    - "client":
    ```
    cd client && npm start
    ```
## Usage

This application showcases proficiency in developing Progressive Web Applications (PWAs) and demonstrates my ability to create versatile and user-centric digital solutions. This project taught hands-on experience implementing key PWA features such as offline functionality, service workers, IndexedDB integration, and webpack bundling. This project highlights dedication to staying current with modern web development practices and commitment to delivering innovative solutions that prioritize usability and performance.

## Credits

- Karen Bourgeois, 
- Tutors

## License

MIT

## Badges


