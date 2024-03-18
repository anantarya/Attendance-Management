<h1 align="center">
    ATTENDANCE MANAGEMENT SYSTEM
</h1>



<br>



# About

The Attendance Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It aims to streamline attendance management.



## Technologies Used

- Frontend: React.js, Material UI, Redux
- Backend: Node.js, Express.js
- Database: MongoDB

<br>

# Installation


Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend 
```sh
cd backend
npm install
npm start
```

Create a file called .env in the backend folder.
Inside it write this :

MONGO_URL = mongodb://127.0.0.1/school

Instead of this link write your database link.

Terminal 2: Setting Up Frontend
```sh
cd frontend
npm install
npm start
```
Now, navigate to `localhost:3000` in your browser. 
The Backend API will be running at `localhost:5000`.

If this is not working then go to the src > redux > userRelated > userHandle.js

Write this after the import statements :

const REACT_APP_BASE_URL = "http://localhost:5000"

Now replace all process.env.REACT_APP_BASE_URL with REACT_APP_BASE_URL.

The problem here was that the .env file in the frontend was not working for other users while it works for me.
So you have to do this in the frontend. After this the project will run smoothly if not then you can contact me.

<br>

# Deployment


#   A t t e n d a n c e - M a n a g e m e n t 
 
 
