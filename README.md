# Xiangqi Online - Chinese Chess Platform

A full-stack real-time Chinese Chess (Xiangqi) platform that supports online multiplayer, AI opponents, puzzles, learning courses, and community interaction.

---

## Features

### Online Multiplayer Mode
- Match with random players or create private rooms.
- Real-time gameplay with **Socket.IO**.
- In-game chat support during live matches.

### Offline Mode (Play with AI)
- Play against the computer using:
  - Static Evaluation Function
  - Minimax Algorithm
  - Alpha-Beta Pruning
- Adjustable AI difficulty.

### Puzzle Mode
- Solve preset chess puzzles.
- Difficulty levels from ⭐ to ⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐ (1 to 10 stars).
- Puzzle data and completion history are stored in **MySQL**.

### Learn Xiangqi (Courses)
- Admin-uploaded learning courses with text, images, or videos.
- Progress tracking to help users improve over time.

### Spectate Matches
- Watch live games being played by others.
- Learn strategies by observing experienced players.

### Community Chat
- Real-time global chat for logged-in users.
- Enhance community interaction and engagement.

---

## 🛠️ Tech Stack

### Frontend
- **React.js** – Component-based frontend framework.
- **Tailwind CSS** – Rapid UI development with utility classes.
- **JavaScript (ES6+)** – For UI logic and client-side interactivity.
- **Socket.IO (Client)** – Real-time communication.

### Backend
- **Node.js + Express.js** – API and Socket.IO server.
- **Socket.IO (Server)** – Handles matchmaking, live updates, chat.
- **MySQL** – Stores user info, puzzles, game states, messages.
- **dotenv** – For managing environment variables.

---

## 📁 Project Structure
/backend
- server.js / server1./ server2.js / servertest.js – API and Socket.IO servers
- uploads/ – Stores user-uploaded files
- .env – Environment variables
- package.json – Backend dependencies

/frontend
- public/ – Static frontend assets
- src/
  - components/
  - ActiveGames.js – Displays live games
  - background-home.js – Homepage background visuals
  - chess-chat.js – In-game & community chat system
  - chess-courses.js – Course list UI
  - chess-earth.js – (Optional) Map/global user view
  - chess-login.js – Login form
  - chess-offline.js – Play with AI (offline mode)
  - chess-online.js – Real-time online play
  - chess-puzzle.js – Puzzle solving interface
  - chess-register.js – User registration
  - course-detail.js – Detailed course view
  - home-page.js – Main homepage
  - SpectateGame.js – Spectator mode UI
  - tournament.js – Tournament bracket (if supported)

## Screenshots
![image](https://github.com/user-attachments/assets/0728e0fd-8eea-4c40-bacd-a0b20865cf43)
![image](https://github.com/user-attachments/assets/e2589844-8c4c-4ff8-b394-524053d0cc3f)
![image](https://github.com/user-attachments/assets/d08e0b5b-4e8d-48a0-8c96-ca108e6823f6)
![Ảnh chụp màn hình 2025-05-06 175210](https://github.com/user-attachments/assets/4c951389-2b71-4334-a92a-6754dd9badd8)
![Ảnh chụp màn hình 2025-05-06 175126](https://github.com/user-attachments/assets/ad4bbafa-70e0-463c-970a-28cdd02079d1)
![Ảnh chụp màn hình 2025-05-06 175302](https://github.com/user-attachments/assets/33514b4d-8b74-4b0d-88dc-a3195c6f5790)
![Ảnh chụp màn hình 2025-05-06 175332](https://github.com/user-attachments/assets/7813cc55-35bc-4aca-b426-07b0e9d655de)
![Ảnh chụp màn hình 2025-05-06 175550](https://github.com/user-attachments/assets/2bcedf31-9a4d-4df0-8117-e8df83f6df64)
![Ảnh chụp màn hình 2025-05-06 175517](https://github.com/user-attachments/assets/d0a96b66-6353-48f5-b19b-2c8135edfdcf)

## 🧪 Setup & Run Locally

```bash
Backend
cd backend
npm install
node server.js
node server1.js
node server2.js
node servertest.js

Frontend
cd frontend
npm install
npm start

## Contributing
Contributions are welcome! You can:
Submit bug reports or feature requests
Fork the repo and submit pull requests
Improve documentation
Please follow the conventional Git flow and use descriptive commit messages.
## Author
[Xuân Tùng]
🔗 GitHub: (https://github.com/xuantung12)
✉️ Email: nguyenxuantung1212004@gmail.com
If you still can't run the project, please contact me.











