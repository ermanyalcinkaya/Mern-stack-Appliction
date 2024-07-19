# Blood-Bank-Mern-Stack-Project

MERN blood bank app project
The MERN Stack Blood Bank Project is a web application that leverages MongoDB, Express.js, React.js, and Node.js to facilitate blood donation and management. It includes features such as donor registration, blood requests, inventory management, user authentication, and search functionality.


# Instructions: How to Run?
    If you have nodejs install then start with step 3
    1- Download nodejs from there : https://nodejs.org/en
    2- Install nodejs
    3- Download Project
    4- unzip the project files
    5- Open your Terminal/Command Prompt on the project’s root folder and run this command "npm i express".
    6- open client folder that is inside of your root folder then run this command "npm install".
    7- create .env file inside of your client folder and then add this code: 
    "
        REACT_APP_BASEURL = http://localhost:8080/api/v1
    ",
    8- create .env file on the project root folder and then add this code:
    "
        PORT = 8080
        DEV_MODE = development
        MONGO_URL = mongodb+srv://rizwansarwartiger:4tHSE4GFVtJwWdaD@cluster0.vgvweqh.mongodb.net/bloodBank
        JWT_SECRET = TECHINFOYT123
    "
    That's it now open your Terminal/Command Prompt on the project root and run this command "node server.js"
    after that open new Terminal/Command Prompt inside of the client folder and then run this "npm start".