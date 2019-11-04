# Rental Application
A cross-platform (iOS & Android) e- commerce mobile application to facilitate the process of renting furniture. This project has been developed using React native, TypeScript, MobX and CSS. The back - end of this project was also developed and is available [here](https://github.com/manas-github/rental-serverapp-springboot "Rental Application Backend")
The major functional feature of this project includes :
  - Signup
  - Login
  - Managing profile
  - Viewing products available
  - Viewing trending products of last 24 hour
  - Searching products
  - Adding and managing cart
  - Checkout cart
  - Managing order history
  - Logout
  
 The non functional feature includes :
  - JWT based API call for authentical and security
  - Session management and auto login
  - Live searching of products
  
# Getting started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
  
## Prerequisites
To get started with this project you will need :
 
  Node
 ```
  Download the latest version from official website (https://nodejs.org).
 ```
  Expo cli : To install expo cli, open terminal and run
 ```
  npm install -g expo-cli
 ```
  Emulator
 ```
  Emulator or any mobile device (iOS/Android)
 ```

## Starting project
  Once you are ready with Node and expo, clone this project repository using terminal
  ```
    git clone https://github.com/manas-github/rental-app.git
  ```
  This will create a local copy of this project on your system. (Don't worry, changing any files on your local system will not change the source code here). Once the project folder is created, move into the folder in terminal
  ``` 
    cd rental-app
  ```
  Install all the module dependencies
  ```
    npm install
  ```
  Start the server
  ```
    npm start
  ```
  If the server doesn't start using npm start doesn't work for some reason or gives some error, try
  ```
    expo start -c
  ```
   
  
