<h1 align="center">ChatApp Frontend </h1> 

##  Project Overview
This is the **frontend** of the ChatApp project built using **React.js**.  
It provides:
- Modern Register & Login UI
- JWT-based authentication
- ChatGPT-like AI chat interface
- Streaming AI responses
- Clean UI with Markdown support

---

##  Technologies Used
- React.js (Vite)
- React Router DOM
- Axios
- Fetch API (for streaming)
- React Markdown
- CSS (Modern Dark UI)

---

## Folder Structure
```
src/
│
├── assets/
│
├── pages/
│   ├── Login.jsx
│   └── Register.jsx
│
├── services/
│   └── authService.js
│
├── ChatContainer.jsx
├── App.jsx
├── main.jsx
├── index.css
```

---

##  How to Run Frontend

```bash
npm install
npm run dev
```

App will run at:
```
http://localhost:5173
```

---

##  Backend Connection
Make sure backend is running at:
```
http://localhost:4000
```

Update API URLs in:
```
src/services/authService.js
```

---

##  Features
- Register & Login pages
- JWT token storage
- Protected AI chat
- Chat history UI
- Streaming AI response
- Markdown rendering

---

##  UI Highlights
- Dark modern theme
- Chat bubbles
- Auto-scroll
- Typing cursor effect

---

## 👨‍💻 Author
Built for MERN + AI Chat Application learning.
