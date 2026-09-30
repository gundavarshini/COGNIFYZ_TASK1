# Cognifyz Level 1 - Task 1
## HTML Structure and Basic Server Interaction

### 📊 Overview

This project is developed as part of the **Cognifyz Technologies Full Stack Development Internship – Level 1, Task 1**.

The objective of this task is to understand the fundamentals of **HTML form creation, Node.js server development, Express.js routing, form submission, and server-side rendering using EJS**.

The application allows users to enter information through an HTML form. The submitted data is sent to the Express.js server, processed on the server side, and dynamically displayed using an EJS template.



## 🎯Task Objective

The main objectives of this task are:

- Create a structured HTML page with a user input form.
- Set up a basic Node.js server using Express.js.
- Create server-side endpoints to handle form submissions.
- Process user input on the server.
- Use EJS for server-side rendering.
- Dynamically generate an HTML response based on submitted data.


  🧰  Technologies Used

- **HTML5** - For creating the user interface and form.
- **CSS3** - For styling the web pages.
- **Node.js** - For running the server-side application.
- **Express.js** - For handling HTTP requests and routing.
- **EJS (Embedded JavaScript Templates)** - For server-side rendering.
- **npm** - For managing project dependencies.


## Project Structure

Level1_Task1/
│
├── node_modules/
│
├── public/
│   └── style.css
│
├── views/
│   ├── index.ejs
│   └── result.ejs
│
├── package.json
├── package-lock.json
└── server.js


| File/Folder         | Description                                   |
| ------------------- | --------------------------------------------- |
|  server.js          | Main Express.js server file                   |
|  views/index.ejs    | Main page containing the input form           |
|  views/result.ejs   | Displays the submitted data dynamically       |
|  public/style.css   | CSS file used for styling                     |
|  package.json       | Contains project information and dependencies |
|  package-lock.json  | Locks the installed dependency versions       |
|  node_modules/      | Contains installed npm packages               |


Application Workflow

The application follows the following workflow:

User Opens Website
        ↓
   HTML Form
        ↓
 User Enters Data
        ↓
   Submit Form
        ↓
 Express.js Server
        ↓
 Process Form Data
        ↓
   EJS Template
        ↓
 Dynamically Generated
      Response
        ↓
 Display Result
 
🚀 How It Works

1. HTML Form

The application provides a form where users can enter information.

The form sends the submitted data to the Express.js server using an HTTP request.

2. Express.js Server

The server.js file creates an Express.js server and defines the required routes.

The server receives the submitted form data and processes it.

3. Form Submission

When the user clicks the Submit button, the entered information is sent to the server.

The Express.js server receives the request and extracts the form values.

4. Server-Side Rendering

EJS is used to dynamically generate the result page.

The submitted information is passed from the Express.js server to result.ejs.

5. Dynamic Result

The result page displays the information entered by the user.

This demonstrates the basic concept of communication between the frontend and backend.

Installation and Setup

Step 1: Clone the Repository
git clone <YOUR_GITHUB_REPOSITORY_URL>

Step 2: Navigate to the Project
cd Level1_Task1

Step 3: Install Dependencies
npm install

If Express and EJS are not installed, run:

npm install express ejs
Step 4: Start the Server
node server.js

The server will start successfully.

Step 5: Open the Application

Open the following URL in your browser:

http://localhost:3000

Features

->User-friendly HTML form
->Express.js backend server
->Form submission handling
->Server-side data processing
->Dynamic HTML generation
->EJS template rendering
->CSS-based page styling
->Basic frontend-backend interaction

📑 Learning Outcomes

Through this task, I gained practical knowledge of:

->Creating HTML forms

->Understanding client-server communication

->Creating a Node.js application

->Working with Express.js

->Creating HTTP routes

->Handling POST requests

->Processing form data

->Using EJS templates

->Implementing server-side rendering

->Organizing a Node.js project

Screenshots

Home Page

<img width="701" height="695" alt="image" src="https://github.com/user-attachments/assets/11279821-74c5-4b2b-b2dd-0dac28497ea6" />


Result Page

<img width="818" height="691" alt="image" src="https://github.com/user-attachments/assets/fe4bc3eb-76af-40a0-9f12-59cfb7e831f9" />

Create a screenshots folder in the project and place your screenshots inside it.

Future Enhancements

The application can be extended with:

->Form validation

->Improved responsive UI

->Database integration

->User authentication

->Error handling

->REST API integration

->Additional form fields
->Persistent storage of submitted information

Internship

Organization: Cognifyz Technologies
Program: Full Stack Development Internship
Level: Level 1 - Beginner
Task: Task 1 - HTML Structure and Basic Server Interaction

Author

Varshini Reddy

GitHub: <YOUR_GITHUB_PROFILE_URL>

Conclusion

This project demonstrates the fundamental interaction between a frontend HTML form and a Node.js backend using Express.js. It also introduces server-side rendering using EJS, providing a foundation for developing more advanced full-stack web applications.

