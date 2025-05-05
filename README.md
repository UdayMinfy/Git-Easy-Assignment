# Git Easy Assignment

This repository demonstrates a basic Git workflow using a file named `Read.txt`, showcasing how changes evolve through multiple commits and how to inspect those changes using `git diff` and `git log`.

---

## 📁 Repository Initialization

The repository was initialized using the following command:

git init
This created a .git folder inside the project directory to start tracking versions.

📌 Files Involved
Read.txt – The main file used to track changes across commits.

✅ Git Workflow
🔹 First Commit

git add Read.txt
git commit -m "First commit"
Added the file Read.txt to the repository.

No content was added yet (0 insertions, 0 deletions).

🔹 Second Commit

git add Read.txt
git commit -m "Second commit"
Added 6 lines about a URL shortener system design.

🔹 Third Commit

git add Read.txt
git commit -m "Third commit"
Updated the file to replace previous content with more advanced system design practice examples.

13 insertions, 6 deletions.

🔍 Git Commands Used
1. View Git Log

git log
Shows commit history:

Third commit → HEAD (latest)

Second commit

First commit

2. Compare Changes Using git diff
🔸 Second vs. First Commit:

git diff 5928ca3 2b99658
Removed:

Initial 6 lines about the URL shortener design.

🔸 Third vs. Second Commit:

git diff 0970240 5928ca3
Replaced:

URL shortener design with a list of real-world system design examples like TinyURL, Google Drive, WhatsApp, etc.

📷 Screenshot of Git log 

![image](https://github.com/user-attachments/assets/d5453721-02c0-4bc5-880d-774091b33c5d)




🧠 Summary
This project helps you:

Understand the basic Git workflow (init, add, commit, diff, log)

Learn how to trace changes across versions

Practice reading and understanding diffs

Get familiar with organizing commits and messages properly

