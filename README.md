# REAL-TIME-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS PVT. LTD

NAME: SAMIR KUMAR

INTERN ID: CT106DG371

DOMAIN: FRONTEND WEB DEVELOPMENT

BATCH DURATION: JUNE 5th,2025 TO JULY 20th,2025  (6 weeks)

MENTOR NAME : NEELA SANTHOSH KUMAR

# DESCRIPTION OF TASK PERFORMED :

As a task under my internship at CODTECH, I developed Connectify, a responsive and real-time one-on-one chat application that enables seamless communication between users. This project was aimed at exploring and implementing real-time web communication using modern JavaScript technologies, offering users a clean, interactive, and efficient chatting experience.

The foundation of Connectify lies in Socket.IO, a powerful JavaScript library that enables real-time, event-based, bidirectional communication between clients and the server using WebSocket technology. The backend of the application was built using Node.js, chosen for its asynchronous, non-blocking I/O and event-driven nature—perfectly suited for real-time communication. I used Express.js, a minimalist Node.js framework, to manage server-side routing, serve static files, and streamline the backend structure.

On the client side, I designed the frontend using HTML, CSS, and vanilla JavaScript, focusing on responsiveness and usability. When a user accesses the app, they are first prompted to enter a unique username, which is temporarily stored on the server through the Socket.IO connection. This ensures each user is uniquely identifiable during their session.

Once logged in, the user is redirected to the chat interface. Here, they can initiate a private conversation by entering the recipient’s username. The app instantly checks if the recipient is online by referencing active socket connections on the server. If the recipient is available, messages are exchanged in real-time, appearing instantly in both users' chat windows. If the intended recipient is offline, a notification alerts the sender that the message cannot be delivered.

To handle these interactions, I implemented multiple Socket.IO events, such as user_connected, message_sent, and user_disconnected. The server maintains an in-memory mapping of usernames to socket IDs to ensure messages are correctly routed. Messages are dynamically appended to the chat window using DOM manipulation, with clear visual separation between sent and received messages. The interface also features a scrollable message area, enhancing usability and navigation.

From a design perspective, Connectify features a fixed navigation bar displaying the application name and a sleek chat interface styled with CSS. The layout includes input fields for entering the recipient’s name and message, alongside a "Send" button. Error handling mechanisms are in place to manage empty inputs or unavailable recipients, providing users with helpful feedback without disrupting the experience.

Although Connectify is currently a functional prototype, the project was developed with scalability and extensibility in mind. Future enhancements could include persistent chat storage using databases, user authentication, encryption for privacy, and even media sharing. These would further transform Connectify into a robust, production-ready communication tool.

In conclusion, Connectify demonstrates the effectiveness of combining Socket.IO, Node.js, Express.js, and frontend technologies to create a lightweight, real-time chat application. The project not only fulfilled the internship requirements but also strengthened my understanding of real-time systems, event-driven programming, and full-stack web development. This hands-on experience has been instrumental in sharpening my backend and frontend skills while delivering a practical, real-world solution for live communication.


# OUTPUT OF THE TASK

![Image](https://github.com/user-attachments/assets/e1e81f3f-3082-46aa-84e9-cf0d8fa29d19)

![Image](https://github.com/user-attachments/assets/87c3746f-01bd-4ca6-b2d0-425ddda324df)

![Image](https://github.com/user-attachments/assets/10ec73fc-db51-438d-9ef7-aaf02759abb0)
