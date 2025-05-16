# MT-Chat-server
Website new 
```
chat-app/
├── backend/
│   ├── server.py               # Python threaded chat server
│   ├── client_handler.py       # (Optional) Logic for handling clients
│   ├── auth.py                 # MongoDB user registration/login
│   ├── db.py                   # MongoDB connection and operations
│   ├── message_logger.py       # Store chat messages
│   ├── requirements.txt        # Python dependencies
│   └── .env                    # Env vars (Mongo URI, secret keys)
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/         # ChatWindow, LoginForm, etc.
│   │   ├── pages/              # Login.jsx, Chat.jsx
│   │   ├── App.js
│   │   ├── index.js
│   │   └── services/
│   │       ├── socket.js       # WebSocket client setup
│   │       └── api.js          # REST API wrapper (login, register)
│   └── package.json
│
├── docker-compose.yml          # (Optional) Run backend/frontend/DB together
└── README.md
```
