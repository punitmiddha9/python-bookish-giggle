# 🚀 Python Hands-on Bootcamp

Welcome to the **Python Hands-on Bootcamp** repository!
This bootcamp is designed to help you learn Python practically with hands-on exercises, projects, and Jupyter notebooks.

---

# 📥 Required Software Installation

## 1️⃣ Install Anaconda

Anaconda helps manage Python environments and packages easily.

### 🔗 Download Anaconda

* 🌐 Windows / macOS / Linux:
  https://www.anaconda.com/products/distribution

---

## 2️⃣ Install Visual Studio Code (VS Code)

VS Code is the recommended editor for this bootcamp.

### 🔗 Download VS Code

* 🌐 Official Website:
  https://code.visualstudio.com/

---

# 🧩 Recommended VS Code Extensions

Install these extensions for the best experience:

| Extension       | Description             |
| --------------- | ----------------------- |
| Python          | Python language support |
| Jupyter         | Run `.ipynb` notebooks  |
| Pylance         | Fast IntelliSense       |
| Python Debugger | Debug Python programs   |

### 🔗 VS Code Marketplace

https://marketplace.visualstudio.com/vscode

---

# ⚙️ Environment Setup

Open **Anaconda Prompt** or terminal inside the project folder.

---

## 📌 Create Virtual Environment

```bash
conda create -p venv python=3.10
```

---

## 📌 Activate Environment

### ▶️ Windows

```bash
conda activate .\venv\
```

### ▶️ macOS / Linux

```bash
conda activate ./venv/
```

---

## 📌 Install Required Packages

```bash
pip install -r requirements.txt
```

---

# 📘 Important Note

> ✅ Install `ipykernel` mandatory to run Jupyter Notebook (`.ipynb`) files.

Install using:

```bash
pip install ipykernel
```

Then register kernel:

```bash
python -m ipykernel install --user --name=venv
```

---

# ▶️ Running Jupyter Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Or open notebooks directly in **VS Code**.

---

# 🛠️ Verify Installation

Check Python version:

```bash
python --version
```

Expected Output:

```bash
Python 3.10.x
```

---

# 🎯 Learning Goals

✔ Python Basics <br>


---

# 🤝 Contributing

Feel free to fork this repository and contribute improvements.

---

# ⭐ Support

If you found this bootcamp helpful:

⭐ Star the repository <br>
🍴 Fork the project <br>
📢 Share with others

---

# Happy Coding!

Made with ❤️ for Python learners.
