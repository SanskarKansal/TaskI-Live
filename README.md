# 🐝 TaskHive

TaskHive is a minimal, responsive task management web app built with **React.js** and **Tailwind CSS**. It allows users to add, edit, complete, and delete their daily todos, with persistent storage using the browser’s **Local Storage**.

---

## 🚀 Features

- ✅ Add new todos quickly
- ✏️ Edit tasks before completion
- ❌ Delete unwanted tasks
- 📁 Save edits seamlessly
- ✅ Mark tasks as completed
- 🔁 Persistent state with local storage
- 🧼 Clean and responsive UI with Tailwind CSS

---

## 🛠️ Tech Stack

- **React.js** – UI logic and component structure
- **Tailwind CSS** – Styling and layout
- **Local Storage** – Data persistence across sessions

---

## 📂 Project Structure

src/
├── App.jsx
├── index.css
├── main.jsx
├── components/
│ ├── TodoForm.jsx
│ └── TodoItem.jsx
├── contexts/
│ └── TodoContext.jsx


---

## 🧠 How It Works

- **Context API** manages global todo state (add, delete, update, toggle).
- **TodoForm** handles adding tasks with controlled input.
- **TodoItem** handles individual todo display, editing, and completion toggles.
- **LocalStorage** syncs todos to persist state on page reload.

---

## 🧪 Getting Started

### Prerequisites

- npm installed

### Installation

```bash
git clone https://github.com/SanskarKansal/TaskHive.git
cd TaskHive
npm install
npm run dev

👨‍💻 Author
Sanskar Kansal
