# Real-Time Chat Application

## 📌 Project Overview
A full-featured real-time chat application that enables seamless communication between users with modern features and a responsive design.

## 🚀 Key Features
- Real-time messaging
- User authentication
- Private and group chats
- Message history
- Online/offline user status
- Responsive design
- Secure communication

## 🛠 Tech Stack
### Frontend
- React.js
- Redux (for state management)
- Socket.io-client
- Axios
- Material-UI or Tailwind CSS

### Backend
- Node.js
- Express.js
- Socket.io
- MongoDB
- Mongoose

### Authentication
- JWT (JSON Web Tokens)
- bcrypt for password hashing

## 📦 Project Structure
```
chat-application/
│
├── client/                # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── services/
│   └── package.json
│
├── server/                # Node.js backend
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── .gitignore
├── README.md
└── docker-compose.yml     # Optional containerization
```

## 🔧 Prerequisites
- Node.js (v14 or later)
- npm or yarn
- MongoDB

## 🚀 Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/Payal-20/Chat-Application.git
cd Chat-Application
```

### Backend Setup
```bash
cd server
npm install
# Create a .env file with the following variables:
# MONGODB_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
npm start
```

### Frontend Setup
```bash
cd client
npm install
npm start
```

## 🔐 Environment Variables
Create `.env` files in both `client` and `server` directories:

### Server `.env`
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/chat-app
JWT_SECRET=your_secret_key
```

### Client `.env`
```
REACT_APP_API_URL=http://localhost:5000/api
```

## 🧪 Running Tests
```bash
# Backend tests
cd server
npm test

# Frontend tests
cd client
npm test
```

## 🌟 Main Functionalities
1. User Registration
2. User Authentication
3. Real-time Messaging
4. User Profile Management
5. Chat Room Creation
6. Message History

## 📊 Performance Optimizations
- WebSocket for real-time communication
- Pagination for message history
- Efficient state management with Redux
- Memoization of React components

## 🔒 Security Features
- Password hashing
- JWT authentication
- Input validation
- Protection against XSS
- CORS configuration

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Roadmap
- [ ] Add end-to-end encryption
- [ ] Implement video/audio calls
- [ ] Dark/Light mode toggle
- [ ] Push notifications
- [ ] User blocking/reporting

Project Link: [https://github.com/Payal-20/Chat-Application](https://github.com/Payal-20/Chat-Application)
