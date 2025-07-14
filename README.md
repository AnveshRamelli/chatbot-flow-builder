# 🧠 Chatbot Flow Builder – BiteSpeed Frontend Assignment

A simple and extensible chatbot flow builder built using **React**, **React Flow**, and **Tailwind CSS**. Users can create and connect message nodes to define the chatbot's logic visually.

---

## 🚀 Features ✅

-  Drag-and-drop message nodes from a side panel
-  Connect nodes using edges (source → target)
-  Each node supports only **one outgoing** connection
-  Settings panel to edit node message content
-  Validation on Save:
  - Shows error if **more than one node has no outgoing connections**

---

## 🛠 Tech Stack

- [React](https://reactjs.org/)
- [React Flow](https://reactflow.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/) (for fast dev experience)

---

## 📦 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/chatbot-flow-builder.git

# Install dependencies
cd chatbot-flow-builder
npm install

# Start the dev server
npm run dev
