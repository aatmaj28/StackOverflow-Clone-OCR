# 🚀 StackOverflow Clone with OCR Technology

My team and I developed an enhanced version of the Stack Overflow clone with OCR technology using api-ninjas API. We integrated API Ninjas - Image to Text API to streamline the interaction process with the community and improve the website's overall user experience. The addition of OCR technology enables users to easily extract and interact with text-based content, making the website more fluid and efficient.....!!📱✨

## 🎯 Features

- **🔍 OCR Integration**: Upload images and extract text instantly using API Ninjas technology
- **👥 User Authentication**: Secure signup and login functionality
- **❓ Question Management**: Ask, edit, and delete questions
- **💬 Interactive Responses**: Post and manage answers
- **👍 Voting System**: Upvote/downvote questions and answers
- **🏷️ Tag System**: Organize content with relevant tags
- **👤 User Profiles**: Customizable profiles with watched tags and bio
- **🎨 Responsive Design**: Clean and intuitive user interface

## 🛠️ Tech Stack

- **Frontend**: React.js, Redux
- **Backend**: Express.js
- **Styling**: CSS3
- **OCR API**: api-ninjas Text to Image API
- **Authentication**: JWT
- **Icons**: Font Awesome
- **Date Formatting**: Moment.js

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
```

2. **Install dependencies**
```bash
# Frontend
cd client
npm install

# Backend
cd server
npm install
```

3. **Set up environment variables**
Create a `.env` file in the server directory:
```env
PORT=5000
CONNECTION_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. **Start the application**
```bash
# Frontend
npm start

# Backend
npm start
```

## 📂 Project Structure

```
├── client/                     # Frontend directory
│   ├── .git/                  # Git directory
│   ├── build/                 # Build output directory
│   ├── node_modules/          # Frontend dependencies
│   ├── public/                # Public assets
│   ├── src/                   # Source code
│   ├── .gitignore            # Git ignore rules
│   ├── package.json          # Frontend package configuration
│   ├── package-lock.json     # Frontend package lock
│   └── README.md             # Frontend documentation
│
└── server/                     # Backend directory
    ├── .git/                  # Git directory
    ├── controllers/           # Route controllers
    ├── middlewares/          # Custom middleware functions
    ├── models/               # Database models
    ├── node_modules/         # Backend dependencies
    ├── routes/               # API routes
    ├── .gitignore           # Git ignore rules
    ├── index.js             # Server entry point
    ├── package.json         # Backend package configuration
    └── package-lock.json    # Backend package lock
```

## 🔑 Key Features Explained

### OCR Technology Integration
- Seamlessly extract text from images using the camera icon in the question editor
- Powered by API Ninjas for accurate text recognition
- Supports PNG and JPEG formats

### User Authentication
- JWT-based authentication system
- Secure password handling
- Protected routes for authenticated users

### Profile Management
- Customizable user profiles
- Bio and watched tags
- Join date tracking
- Activity history

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Stack Overflow for inspiration
- API Ninjas for OCR Image to Text API
- The open-source community

## 📁 Project Files
🔗 Access the complete project files here: https://drive.google.com/drive/folders/1tipuBG0SDzfSrZBGoVTIwj_TR61lBNEy?usp=share_link

---

Made by Aatmaj Amol Salunke, Sanskar Swaraj, and Madhavendra Dixit at Manipal University Jaipur, as a part of our Minor Project in Semester 5.
