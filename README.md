# Note-Taking-App-Flask
# 📝 Note Taking App (Flask)

A simple and beginner-friendly **Note Taking Web Application** built using **Python Flask**.
This project allows users to add notes and display them on the same page.

---

## 🚀 Features

* Add notes using a text input field
* Display all notes dynamically
* Simple and clean UI
* Beginner-friendly Flask project

---

## 🛠️ Tech Stack

* Python 🐍
* Flask 🌐
* HTML (Jinja2 Templates)

---

## 📂 Project Structure

```
note_taking_app/
│
├── note_app.py
└── templates/
    └── home.html
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project on your system:

### 1️⃣ Clone the Repository

```
git clone https://github.com/kusuma990/Note-Taking-App-Flask-
cd note-taking-app
```

---

### 2️⃣ Install Dependencies

Make sure Python is installed, then run:

```
pip install flask
```

---

### 3️⃣ Run the Application

```
python note_app.py
```

---

### 4️⃣ Open in Browser

Go to:

```
http://127.0.0.1:5000/
```

---

## 🧠 How It Works

1. User enters a note in the input field
2. Clicks the **Add** button
3. The note is sent to the Flask backend
4. Backend stores it in a list
5. Notes are displayed using HTML (Jinja loop)

---

## 📝 Code Explanation

### 🔹 Backend (`note_app.py`)

* Flask handles routing (`/`)
* Supports both `GET` and `POST` requests
* Stores notes in a list
* Passes notes to HTML using `render_template`

---

### 🔹 Frontend (`home.html`)

* Contains a form to input notes
* Uses Jinja template to display notes
* Loops through notes and shows them as a list

---

## ⚠️ Limitations

* Notes are stored in memory (not permanent)
* Notes will be lost when server restarts

---

## 🚀 Future Improvements

* Add delete functionality
* Store notes in database (SQLite / MongoDB)
* Improve UI using CSS / Bootstrap

---

## 👩‍💻 Author

* Kusuma Kumari Bodduluri
  - 🔗 LinkedIn: www.linkedin.com/in/kusuma-kumari-bodduluri
  - 💻 GitHub: https://github.com/kusuma990
  - 🎓 Data Science Student
  - 🐍 Python Programmer
---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!

---
