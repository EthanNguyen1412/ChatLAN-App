ChatLAN - Corporate Internal Chat Application
1. Project Overview
ChatLAN is a desktop application designed for real-time, secure internal communication within a corporate network. Built with JavaFX, it utilizes a client-server architecture to ensure that all messages are handled centrally and delivered instantly to online users.

2. Features
Real-time Messaging: Instant text communication between authenticated users.
Client-Server Architecture: A central server manages connections and message routing.
User Authentication: Users must log in with a valid username and password to join the chat.
Graphical User Interface (GUI): A user-friendly and intuitive interface built with JavaFX.

3. Technology Stack
Programming Language: Java
GUI Framework: JavaFX
Networking: Java Sockets for client-server communication.
Build Tool: Maven/Gradle (or IDE default)

4. Setup and Installation
To run this project, you need to have Java Development Kit (JDK) 8 or higher installed.

Step 1: Clone the Repository
git clone [https://github.com/EthanNguyen1412/ChatLAN-App]

Step 2: Run the Server
The server must be started first to listen for client connections.
Open the project in your IDE (e.g., IntelliJ IDEA, Eclipse).
Locate and run the Server.java file (or the main class for the server module).
The server will start and print a message to the console, such as "Server is running and waiting for clients...".

Step 3: Run the Client
Once the server is running, you can launch one or more client instances.
In your IDE, locate and run the Client.java file (or the main class for the client module).
A login window will appear.
Repeat this step to open multiple chat windows for different users.

5. How to Use
User Accounts
The application has several pre-configured user accounts for testing purposes.
Password for all accounts: 1
Usernames:
bao
vanh
luc
vu
nick
nigga

Note: This username is for testing only. It is recommended to change it in a professional or public context.

Log in with any of these credentials on different client windows to start chatting.
