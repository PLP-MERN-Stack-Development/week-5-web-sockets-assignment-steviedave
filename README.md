# 🗨️ IChat – A Real-Time Group Chat Application

**IChat** is a simple yet elegant multi-user chat application built with **Node.js**, **Express**, **Socket.IO**, and **vanilla HTML/CSS**. Designed with a clean UI and seamless real-time communication, IChat enables multiple users to chat on the same server simultaneously, with instant message delivery, typing indicators, timestamps, and auto-scrolling for long threads.

This project is perfect for developers looking to understand the core concepts of real-time communication on the web using web sockets.

---

## 🚀 Features

- 🔁 **Real-time messaging** powered by **Socket.IO**
- 👥 Supports multiple users chatting in different browser tabs or windows
- ✍️ **Typing indicators** show when someone is writing a message
- 🕒 **Timestamps** generated with **Moment.js**
- 🎨 **Responsive and elegant UI** with smooth interactions
- ⏬ **Automatic scroll** when messages overflow the chat window
- 🔄 **Live user count** updates in real time

---

## 📁 Project Structure

```plaintext
├── app.js                  # Main server-side application logic
├── package.json            # Project metadata and dependencies
├── public/                 # Static assets (HTML, CSS, client-side JS)
│   ├── index.html
│   ├── style.css
│   └── socket.js
├── .gitignore              # Ignore node_modules and .env
└── README.md               # Project overview and usage guide
```

---

## 🛠️ Technologies Used

- **Node.js** & **Express** – Back-end framework and server
- **Socket.IO** – Real-time, bi-directional communication
- **Moment.js** – Time formatting for message timestamps
- **HTML & CSS** – User interface
- **Nodemon** – Dev server with auto-restart on changes

---

## 📸 Screenshots

> Replace these placeholders with your own screenshots to showcase the UI and functionality.

- **Chat Interface with Multiple Users**

  ![Chat UI Screenshot](screenshots/Screenshot%202025-07-22%20004037.png)

- **Chat App In Action**

  ![Typing Screenshot](screenshots/Screenshot%202025-07-22%20012503.png)

  ![Typing Screenshot](screenshots/Screenshot%202025-07-22%20012532.png)


---

## 💻 How to Run the Project Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ichat.git
   cd ichat
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to:
   ```
   http://localhost:4000
   ```

5. **Testing multi-user chat**:
   - Open multiple tabs or browser windows.
   - Each instance will represent a different "user".
   - Type messages in one and see them reflected instantly in the others.

---

## 🧠 Key Concepts Behind the App

- **WebSockets with Socket.IO**: Unlike traditional HTTP requests, sockets allow persistent, real-time communication between the client and server. This makes chat apps responsive and efficient.
- **Typing Feedback**: When a user starts typing, the event is broadcast to others. When they stop, the typing status is removed.
- **Moment.js for Readability**: Timestamps are formatted cleanly to provide context for when messages were sent, enhancing user experience.
- **Auto Scroll Logic**: JavaScript ensures the chat window scrolls down automatically as new messages come in, mimicking the behavior of modern messaging platforms.

---

## ⚙️ Upcoming Features

- 🔐 **Authentication system** so users can register and log in
- 💾 **Database integration** to store messages and user data persistently

Stay tuned for updates as the project evolves!

---

## 📬 Contributing

Pull requests are welcome! If you'd like to improve the UI, add features like emojis, or implement chat rooms — feel free to fork and build on it.

---

## 📝 License

This project is open-source under the [ISC License](LICENSE).

---

## ✍️ Author

**Stephen David Oduor**
