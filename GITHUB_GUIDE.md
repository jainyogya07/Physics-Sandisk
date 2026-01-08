# How to Push to GitHub

Since this is a "smart" single-file project, pushing it is simple, but here is the manual guide if the auto-push doesn't work.

### 1. Initialize Git (if not already done)
Open your terminal in this folder and run:
```bash
git init
```

### 2. Add Your Files
Stage all your changes for commit:
```bash
git add .
```

### 3. Commit Your Work
Save the current state with a message:
```bash
git commit -m "Initial commit: AI Physics Engine Single-File V2"
```

### 4. Link to GitHub Repo
Connect your local folder to your GitHub repository:
```bash
git branch -M main
git remote add origin https://github.com/jainyogya07/Physics-Sandisk
```
*(If it says "remote origin already exists", that's fine!)*

### 5. Push!
Upload your code to the cloud:
```bash
git push -u origin main
```

---
**Note**: If `git push` fails due to permissions, ensure you are logged into GitHub Desktop or have your SSH keys set up.
