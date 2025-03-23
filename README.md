# 🖥️ Java Client-Server Communication 🖥️

This project demonstrates a simple **client-server communication** using Java sockets. It includes a `Client` and a `Server` that exchange messages over a network connection. This is a great example to understand the basics of networking in Java! 🚀

---

## 🌟 Features

- **Simple Communication**: The client sends a message to the server, and the server responds with a message.
- **Timeout Handling**: The server has a timeout of 10 seconds to handle idle connections.
- **Port Configuration**: The server listens on port `8081`, and the client connects to the same port.
- **Error Handling**: Both client and server handle exceptions gracefully.

---

## 🛠️ How It Works

### **Server**
- The server listens on port `8081` for incoming client connections.
- When a client connects, the server sends a response message: `"Hello from the server"`.
- The server then closes the connection.

### **Client**
- The client connects to the server running on `localhost` at port `8081`.
- It sends a message to the server: `"Hello from the client!!"`.
- The client reads the server's response and prints it to the console.


---

### **Key Highlights**
- **Features**: Highlighted the key features of the project.
- **Learning Outcomes**: Explained what you can learn from this project.


Let me know if you need further enhancements! 🚀
