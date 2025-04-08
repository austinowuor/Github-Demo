# 🚀 GitHub Push Demo

Welcome to the **GitHub Push Demo** – a simple Python script created to demonstrate pushing code to GitHub and writing clean, well-documented projects.

---

## 🧠 What It Does

This script:

- Greets the user with a welcome message
- Displays the **current date and time**
- Shows the **current working directory**
- Prints a **random motivational message** to keep you coding

Perfect for beginners exploring Git, Python, or just testing out their GitHub workflow.

---

## 📝 The Code

The script is called `demo_github_push.py`. It uses only Python’s built-in libraries:

```python
import datetime
import os
import random

def main():
    print("👋 Welcome to GitHub!")

    now = datetime.datetime.now()
    print("🕒 Current date and time:", now.strftime("%Y-%m-%d %H:%M:%S"))

    cwd = os.getcwd()
    print("📁 Current working directory:", cwd)

    messages = [
        "Keep pushing those commits!",
        "Code. Commit. Push. Repeat.",
        "You're doing great!",
        "Git it done! 😎",
        "Version control is under control."
    ]
    print("💡 Tip of the day:", random.choice(messages))

if __name__ == "__main__":
    main()
#running it locally
git clone https://github.com/your-username/github-push-demo.git
cd github-push-demo

python demo_github_push.py


🎯 Why This Exists
This mini project is a quick and friendly way to:

Practice basic Git commands (add, commit, push)

Learn how to document your code

Try pushing to GitHub with small, clean code

Add a README that actually makes sense 😉

🛠 Requirements
Python 3.x

Git (for pushing the code to GitHub)

No other dependencies — it's all standard library!

📄 License
This project is public domain. Fork it, copy it, remix it, or use it in your tutorials.


