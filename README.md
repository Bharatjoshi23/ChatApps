Chat Application

This is a simple chat application built using HTML, CSS, JavaScript, PHP, and MySQL. The application allows users to communicate in real-time by sending and receiving messages. It utilizes WebSocket for real-time communication and PHP for handling server-side operations.

Features
Real-time messaging with WebSocket
User registration and authentication
Persistent message storage using MySQL
Simple and responsive user interface
Demo
You can check out a live demo of the chat application here.
https://thisischatapp.000webhostapp.com/
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/chat-app.git
cd chat-app
Import the database schema
Create a new MySQL database and import the database.sql file provided in the sql folder.
Configure the database
Open config.php file located in the php folder.
Update the database credentials:
php
Deploy the application
Place the entire contents of the chat-app folder into your web server root directory (e.g., Apache's www folder).
Start your web server
Start your web server (e.g., Apache, Nginx) and make sure PHP is properly configured.
Usage
Open your web browser and navigate to the address where you deployed the chat application.

Register a new account using the "Sign Up" option if you're a new user, or log in with your existing credentials.

Once logged in, you'll be directed to the chat interface. Here, you can see your contacts and start sending messages to other users.

Messages will be delivered and displayed in real-time using WebSocket.

Contributing
We welcome contributions to improve the chat application. If you find any issues or have suggestions, please feel free to open an issue or submit a pull request.

Before contributing, please make sure to review the Contribution Guidelines.


Acknowledgments
This chat application was inspired by chat-ws-php.
Happy chatting! If you have any questions or need further assistance, feel free to contact us.

Developed by Bharat Joshi
