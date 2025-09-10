# Overthrow - Real-time Multiplayer Strategy Card Game
Overthrow is a real-time multiplayer card game inspired by Coup, built with a focus on Socket.IO-powered room-based communication. Players can create or join game rooms and play rounds of strategic deception and deduction. Designed to explore backend networking, WebSockets, and multiplayer architecture in JavaScript, deployed on render CI/CD.

📝 Description
Overthrow lets users create private game rooms and connect with other players in real time. Players join by sharing room IDs, and the game keeps track of players per room using WebSockets. The initial build lays the foundation for scalable real-time gameplay, emphasizing networking, state tracking, and frontend-backend synchronization. Built to learn real-time multiplayer web game architecture.

💻 Tech Stack

-Frontend: HTML, JavaScript (Vanilla)
-Backend: Node.js, Express.js
-WebSockets: Socket.IO

🎮 Features
-Create multiplayer game rooms with unique room codes
-Join existing rooms with room ID
-Real-time player list updates
-Room auto-cleanup when players leave or disconnect
-Socket.IO-based backend state synchronization

Setup Instructions:

Clone repo - "git clone https://github.com/<your-username>/Overthrow.git"
             "cd Overthrow"
Install Dependencies - "npm install"
Run server locally - "node server.js", open browser to http://localhost:3000

Link: https://overthrow-game.onrender.com/

Screenshots:

<img width="1093" height="563" alt="image" src="https://github.com/user-attachments/assets/694f838b-08db-4c2c-9e66-73fcf2c7f0c9" />
<img width="750" height="1052" alt="image" src="https://github.com/user-attachments/assets/a6e923bd-248a-444d-9fde-a2d09ab5130c" />
<img width="594" height="425" alt="image" src="https://github.com/user-attachments/assets/c211b419-1f4e-4f52-aa01-ddc9304cf7c7" />
<img width="1714" height="882" alt="image" src="https://github.com/user-attachments/assets/9ad0c543-ee8e-4544-b5fa-c4ba8456676d" />
<img width="1645" height="898" alt="image" src="https://github.com/user-attachments/assets/9d62d4a3-9c44-4569-a659-abc617c9c9ff" />
<img width="1734" height="896" alt="image" src="https://github.com/user-attachments/assets/0e692db0-68ce-4274-8304-3325a84ff788" />

👤 My Role
This project was built independently. I designed both the frontend and backend, implemented the room management logic, and integrated real-time communication with Socket.IO.

🚀 Future Work
-Bugfix exchange
-Add permanent player identification between sessions
-Fix money display (image not loading)
