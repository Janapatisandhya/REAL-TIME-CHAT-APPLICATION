# REAL-TIME-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: JANAPATI Sandhya 

*INTERN ID*:CT04DL793

*DOMAIN*: FRONT END DEVELOPMENT 

*DURATION*:4WEEKS

*MENTOR*:NEELA SANTHOSH 

##DescriptionReal-Time Chat Application 

The objective of this project was to build a simple real-time chat application using basic web technologies—HTML, CSS, and JavaScript—within the SPCK Editor environment. The goal was to enable communication between two or more tabs opened in the same browser window, allowing users to exchange messages in real time. This functionality was successfully implemented using the localStorage API, a built-in feature of modern web browsers.

SPCK Editor is a lightweight, mobile-friendly code editor that allows developers to write, test, and run HTML/CSS/JavaScript code without the need for a full desktop development environment. It provides a fast and convenient platform for building and testing web projects, especially for front-end development.

In the developed application, the user interface consists of a message input field, a send button, and a display area to show the ongoing chat. When a user types a message and clicks the send button, the message is immediately displayed in the current tab and saved in the browser’s localStorage along with a timestamp to ensure uniqueness. Other open tabs of the same HTML file detect this change through the storage event listener, a browser event that fires whenever data stored in localStorage is modified by another tab. Once detected, the new message is retrieved and displayed, simulating real-time communication.

This setup allows seamless message reflection across different tabs in the same browser, but it does not support communication across different browsers (e.g., Chrome to Firefox). This limitation arises because localStorage is scoped per browser and per device. Each browser instance maintains its own separate storage, and the storage event only fires in the context of the browser where the change was made. Therefore, communication between different browsers—or even different devices—would require a backend service or cloud database such as Firebase or a WebSocket server.

The benefits of this approach include its simplicity, speed, and the lack of need for server-side code or databases. It is ideal for prototyping or creating local-only applications where real-time updates are needed between tabs. However, it is limited in scalability and practicality for broader applications involving multiple users or persistent message history.

To summarize, this project successfully demonstrates how to build a lightweight real-time chat system using only client-side technologies. By leveraging SPCK Editor for development and localStorage for data sharing, a fully functional chat experience was created for use within a single browser. This foundational project can serve as a stepping stone to more advanced real-time communication systems that use server-side technologies and support multi-user environments across multiple browsers and devices. for this task
