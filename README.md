This is a real time chat application built by using MERN stack.

<h3>packages Used</h3><br>
<h4>Mongoose:</h4>to connect my application to mongodb database and access it.
<h4>bcrypt:</h4> to hash the user passwords.
<h4>Nodemon:</h4> to run the backend server automatically because everytime running the server manually would be a hustle.
<h4>jwt-token:</h4> to authorize the user.
<h4>cookie-parser:</h4> to manage the session of the user.
<h4>zustand :</h4> Used zustand for managing the state.

<h3>how to install the necessary packages?</h3>
if u want to run the application. after cloning navigate to frontend folder by using <code> cd frontend<code> <br>
and run <code>npm install<code>. this will install all the necessary packages for frontend  like daisy ui, zustand etc<br>
now navigate to backend by using <code> cd backend <code> after goinf to root directory <br>
run npm install to install all the necessary packages like bcrypt,nodemon,cookie parser,etc<br>
after installing necessary packages now u need to configure the database i have used mongoose for mongodb <br>
create a mongodb cluster and copy the connection string and use it in the env by the name <strong>MONGO_DB_URI<strong><br>
later create a jwt tocken and configure it in env file too<br> 

<h3>How to run the application</h3>
after configuring all the necessary packages and files navigate to backend and run <code>npm start<code>
and navigate to frontend and run <code>npm run dev<code>  these will start your frontend and backend servers <br>
in my case it was port 3000 to access the application. check your port when you run the frontend and access on the port.
thats all



