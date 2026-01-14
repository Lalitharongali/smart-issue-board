# 🧠 Smart Issue Board

Smart Issue Board is a web-based issue tracking application that allows users to report, view, and manage issues efficiently.  
The application also helps reduce duplicate issue submissions by detecting similar issues before they are created.

---

## 🚀 Live Demo

🔗 **Deployed URL:**  
https://smart-issue-board-ecru-seven.vercel.app/

---

## 📌 Project Overview

This project was developed as part of an academic assignment to demonstrate frontend development, authentication, database usage, and basic problem-solving skills.  
Users can sign up, log in, create issues, and view existing issues through a clean and responsive interface.

---

## 1️⃣ Why did you choose the frontend stack you used?

I chose **Next.js with React and TypeScript** for the following reasons:

- **Next.js (App Router)** provides file-based routing and eliminates the need for a separate `index.html`.
- **React** enables component-based development, making the UI reusable and maintainable.
- **TypeScript** improves code quality by catching errors during development.
- Next.js integrates seamlessly with **Firebase** and is easy to deploy using **Vercel**.

---

## 2️⃣ Explain your Firestore data structure

Firestore is used as a NoSQL database to store issue information.

### 📂 Collection: `issues`

Each issue is stored as a document with the following structure:

```json
{
  "title": "Internet not working",
  "description": "Wi-Fi is down in hostel block A",
  "priority": "High",
  "status": "Open",
  "createdBy": "user_uid",
  "createdAt": "timestamp"
}
