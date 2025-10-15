
# 🏆 20-20 Challenge  
*A Mobile App for Enhancing Reading and Visual Interpretation Skills*

---

## 📖 Overview
**20-20 Challenge** is a cross-platform mobile application that promotes reading and visual interpretation through a structured and competitive yearly challenge.  
Participants are encouraged to **read 20+ books** and **watch 20+ movies** from various genres each year, improving their knowledge, communication skills, and creativity.  

The app builds a **friendly, engaging community** where users can share posts, interact with others, and track progress via leaderboards and feedback sections.

---

## 🧠 System Architecture
The project follows a **client–server architecture** with clear modular design:

### **Main Components**
- **Frontend:** React Native  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  

### **Modules**

#### 👤 Participant Module
- Sign-up / Login / Logout  
- Add, edit, or delete posts and comments  
- View feed, leaderboard, and guidelines  
- Edit profile & password  
- Share feedback  

#### 👥 Guest Module
- Continue as guest or create an account  
- View feed and guidelines  
- Share feedback  

Both modules connect to a central **MongoDB database** through RESTful APIs.

---

## 📁 Project Structure

```

challenge_2020/
│
├── Backend/                # Server-side (Node.js + Express)
│   ├── db.js               # MongoDB connection setup
│   ├── index.js            # Entry point of backend
│   ├── models/             # Mongoose schema definitions
│   ├── routes/             # API endpoints
│   ├── package.json        # Backend dependencies
│   └── node_modules/
│
└── Frontend/               # Client-side (React Native)
├── App.js              # Main app entry
├── SRC/                # Components, screens, utils
├── assets/             # Images, icons, etc.
├── app.json
├── babel.config.js
├── package.json        # Frontend dependencies
├── yarn.lock
└── package-lock.json

````

---

## ⚙️ Tools & Technologies

| 🧩 Category | 🛠️ Tool / Framework | 💡 Description |
|-------------|--------------------|----------------|
| **Frontend** | [React Native](https://reactnative.dev/) | Open-source framework by Meta for building cross-platform apps. |
| **Backend** | [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/) | Lightweight JavaScript runtime and API framework. |
| **Database** | [MongoDB](https://www.mongodb.com/) | NoSQL document-based database for flexible data storage. |
| **IDE / Editors** | [Android Studio](https://developer.android.com/studio), [VS Code](https://code.visualstudio.com/) | Used for mobile and web development. |
| **Package Manager** | [NPM](https://www.npmjs.com/) | Manages dependencies for JavaScript/Node.js. |

---

## 🚀 Installation & Setup

### **1️⃣ Backend Setup**
```bash
cd challenge_2020/Backend
npm install          # Install dependencies
node index.js        # Start backend server
````

Default backend URL:

```
http://localhost:5000
```

---

### **2️⃣ Frontend Setup**

```bash
cd challenge_2020/Frontend
npm install          # Install dependencies
npx react-native start
```

Then, to run on emulator or connected device:

```bash
npx react-native run-android
# or
npx react-native run-ios
```

---

## 📱 Key Features

✅ Secure user authentication (Signup, Login, Password Reset)
✅ Add and interact with posts (Books & Movies)
✅ User-friendly interface with dynamic feeds
✅ Leaderboard and feedback integration
✅ Guest user access
✅ Profile customization and password update

---

## 🌱 Future Enhancements

🚀 **Poll Creation:** Allow users to create and participate in polls.
💬 **Discussion Forums:** Introduce group discussion features for interactive engagement.
🏅 **Badges & Achievements:** Reward users for milestones like “20 Books Completed.”

---

## 📚 References

* *Roger S. Pressman – Software Engineering: A Practitioner’s Approach*
* *Ian Sommerville – Software Engineering*
* Official documentation for **React Native**, **Node.js**, and **MongoDB**
* GitHub & community tutorials on full-stack app development

---

## 🪄 License

This project is open for **educational and personal use**.
Attribution to the author is appreciated when reused or adapted.

---

> *“Read. Watch. Learn. Share. Challenge yourself every year!”* 🌟
