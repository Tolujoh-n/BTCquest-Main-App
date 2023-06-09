# ThetaQuest

ThetaQuest is a learning platform that uses blockchain technology for a secure educational experience. An escrow contract handles transactions and ensures funds are secure. ThetaQuest is a community that connects students with peers and educators to collaborate and learn together.

## Development server

Before starting the application, first create a database in mongo named "quizzards"
<br/>
To start the Server :
<br/>

1. `cd server`<br/>
2. `node index.js`
   <br/>

To run the application on the browser: <br/>

3. Open a new terminal and run cd client/quizzards-client<br/>
4. ` ng serve ` or ` npm start ` <br/>
5. Navigate to `http://localhost:4200/`.

## Features

<!-- 1. Used JWT for login -->
1.user can login
2. The user can play a quiz only once
3. On submitting a quiz, the user is redirected to the feedback page. Here the student cannot redirect back to the Quiz.
4. Chatbot is provided, so new users can easily navigate through the appication
5. Teachers can get an overview of student's performances with the help of charts.
