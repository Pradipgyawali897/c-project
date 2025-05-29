<h1 style="text-align:center;">🎮 C Project: SDL2-Based Chat Client & Server 💬</h1>

<p align="center">
  A real-time messaging application built using C, SDL2, and Windows Sockets. This project brings together low-level networking with a graphical user interface to simulate a simple but interactive client-server chat system.
</p>

<hr>

<h2>🧠 Project Description</h2>
<p>
This project is a real-time chat application written in C that showcases the power of integrating multimedia libraries with network communication. It consists of two parts:
</p>
<ul>
  <li><strong>Client:</strong> A graphical interface powered by SDL2 where users can type and send messages.</li>
  <li><strong>Server:</strong> A background console program that handles multiple client connections and message routing.</li>
</ul>

<p>
Messages are sent over TCP using Windows Sockets, and the client displays them using SDL_ttf fonts on a custom background. Notifications are enhanced with sound effects, and all chat history is logged for future reference.
</p>

<hr>

<h2>✨ Features</h2>
<ul>
  <li><strong>Interactive GUI:</strong> Clean SDL2 interface with background image and custom fonts.</li>
  <li><strong>Real-Time Messaging:</strong> Chat system using TCP sockets for instant communication.</li>
  <li><strong>Sound Alerts:</strong> Receive audio notifications every time a message arrives.</li>
  <li><strong>Chat Logging:</strong> Messages are stored locally in a history file.</li>
  <li><strong>Multi-User Support:</strong> The server can manage connections from multiple clients.</li>
  <li><strong>Efficient Networking:</strong> Uses <code>ws2_32</code> for robust Windows socket programming.</li>
</ul>

<hr>

<h2>🚧 Under the Hood</h2>
<p>
The core of the application combines C’s performance with the flexibility of SDL2’s multimedia capabilities. By blending text rendering, image display, and sound with classic socket programming, the project provides an engaging desktop-based communication system — all from scratch in C.
</p>

<hr>

<h3 align="center">💡 Ideal for learning systems programming, multimedia integration, and network communication.</h3>
