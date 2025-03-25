# 🔄 Resource Allocation Graph Visualizer

A sleek, interactive web application for visualizing **Resource Allocation Graphs (RAGs)** and understanding **deadlock detection** in Operating Systems — built with 💙 and powered by **D3.js**.

---

## 🌟 Features

- 🎯 **Add Nodes:** Create Process (🔵) and Resource (🟢) nodes.
- 🔗 **Draw Edges:** Visualize Requests (P → R) and Allocations (R → P).
- 🚨 **Deadlock Detection:** Instantly check for cycles (deadlocks) in the graph.
- ⚙️ **Auto Example:** Generate a pre-built deadlock scenario with a single click.
- 💡 **Interactive UI:** Select, connect, and remove nodes/edges effortlessly.
- 🧰 **Tooltips & Feedback:** Real-time hover info and alerts.

---

## 🎓 Why Use This?

Understanding deadlocks is a key topic in OS. This tool helps:

- 👩‍🏫 **Students:** Learn visually and interactively.
- 👨‍🏫 **Educators:** Demonstrate deadlock scenarios live in class.
- 👨‍💻 **Developers:** Simulate RAGs for system analysis or teaching.

---

## 📸 Demo Snapshot

![RAG Screenshot](./screenshot.png)  
> 💥 Deadlock Detected: Cycle found in the graph!

---

## 🧠 How It Works

- A **Process → Resource** edge means the process **requests** the resource.
- A **Resource → Process** edge means the resource is **allocated** to that process.
- A **Cycle in the graph = Deadlock**.
