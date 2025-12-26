# 🚀 FlowForge – Visual AI Pipeline Builder

FlowForge is an interactive, node-based pipeline editor that lets users visually design, connect, and validate AI-style workflows using a clean drag-and-drop interface.

✨ Built to demonstrate modern frontend engineering, graph logic, and backend validation.

---

## 🎯 What Does FlowForge Do?

🔹 Create pipelines using visual nodes
🔹 Connect nodes to define data flow
🔹 Dynamically detect variables inside text
🔹 Validate pipelines using backend logic
🔹 Ensure pipelines follow **DAG (Directed Acyclic Graph)** rules

---

## 🧩 Key Features

✅ Drag-and-drop canvas using **React Flow**

✅ Custom node abstractions:

* 📥 Input Node
* 🧠 LLM Node
* 📤 Output Node
* 📝 Text Node

✅ Dynamic Text Node:

* Supports `{{variables}}`
* Auto-creates input handles
* Auto-resizes based on content ✨

✅ Backend validation:

* 🔢 Counts nodes & edges
* 🔁 Detects cycles
* ✅ Confirms DAG validity

---

## 🛠️ Tech Stack

### 🌐 Frontend

* ⚛️ React
* 🧭 React Flow
* 🐻 Zustand (state management)
* 🎨 CSS

### ⚙️ Backend

* 🐍 Python
* 🚀 FastAPI
* 🌬️ Uvicorn

---

## 🔄 How It Works (Simple Flow)

1️⃣ Drag nodes onto the canvas
2️⃣ Connect nodes visually
3️⃣ Write text with `{{variables}}` inside Text nodes
4️⃣ Click **Submit**
5️⃣ Backend analyzes the pipeline
6️⃣ Result is shown instantly via alert 🎉

---

## ▶️ Run the Project Locally

### 🔹 Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

📍 Backend runs at:

```
http://127.0.0.1:8000
```

---

### 🔹 Frontend Setup

```bash
cd frontend
npm install
npm start
```

📍 Frontend runs at:

```
http://localhost:3000
```

---

## 📊 Example Output

After clicking **Submit**:

```
Nodes: 3
Edges: 2
Is DAG: true
```

✔ Valid pipeline
✔ No cycles detected

---

## 🗂️ Project Structure

```
FlowForge/
├── frontend/   # React Flow UI
├── backend/    # FastAPI DAG validator
└── README.md
```

---

## 💡 Use Cases

✨ Visual AI / ML pipeline design
✨ DAG-based workflow validation
✨ Learning graph theory concepts
✨ Rapid prototyping tools

---

## 🧠 Why FlowForge?

🚀 Modern UI
🧩 Clean architecture
⚡ Real-time validation
🎯 Interview-ready project

---

## 👩‍💻 Author

**Sanya** 💙
Computer Science Student | Frontend Developer

---

## ⭐ Final Note

If you like this project, feel free to ⭐ the repository and share feedback!
