# Data Workshop Demo Repository

Welcome to the **Data Journey Kickstart Python** workshop practice repository!

This repository is designed for hands-on practice with Git workflows and collaborative development.

## 🎯 Purpose

This repository allows workshop participants to practice:
- Cloning a repository
- Creating branches
- Making changes
- Committing and pushing
- Creating Pull Requests
- Collaborating without conflicts

## 📁 Repository Structure

```
data-workshop-demo/
├── README.md                 # This file
├── .gitignore               # Git ignore rules
└── exercises/               # Each participant creates their own folder here
    ├── README.md
    ├── faiz/               # Example: Faiz's folder
    ├── john/               # Example: John's folder
    └── ...
```

## 🚀 Getting Started

### Step 1: Clone this Repository

```bash
cd C:\Projects
git clone https://github.com/YOUR-USERNAME/data-workshop-demo.git
cd data-workshop-demo
```

### Step 2: Create Your Branch

```bash
git checkout -b add-yourname-exercise
```
Replace `yourname` with your actual name (e.g., `add-faiz-exercise`)

### Step 3: Create Your Folder

```bash
mkdir exercises/yourname
```

### Step 4: Add Your Work

Create a simple Python file in your folder:

```bash
echo "print('Hello from Faiz')" > exercises/yourname/hello.py
```

Or create any file you want to practice with!

### Step 5: Commit and Push

```bash
git add exercises/yourname/
git commit -m "Add yourname's exercise folder"
git push -u origin add-yourname-exercise
```

### Step 6: Create a Pull Request

Go to the repository on GitHub and click "Compare & pull request"

## 📝 Exercise Instructions

### Exercise 1: Practice Git Workflow

1. Create your folder: `exercises/yourname/`
2. Add a simple Python file:
   ```bash
   echo "print('Hello from [Your Name]')" > exercises/yourname/hello.py
   ```
3. Stage, commit, and push your changes
4. Create a Pull Request

### Exercise 2: Add More Files (Optional)

1. Add a `.gitignore` file in your folder
2. Add a `README.md` with your notes
3. Commit and push the changes

## 🤝 Collaboration Guidelines

- **Each participant works in their own folder** under `exercises/`
- **Never edit files in other participants' folders**
- **Always pull before starting new work:** `git pull origin main`
- **Use descriptive commit messages**
- **Create Pull Requests for review**

## ⚠️ Important Notes

- This is a **Git practice repository** - focus is on the workflow, not running code
- Each participant works in their own folder to avoid conflicts
- The goal is to practice: branching, committing, pushing, and creating Pull Requests

## 🆘 Need Help?

- Check the workshop materials in Module 3D
- Ask your instructor
- Review GitHub's [Git Handbook](https://guides.github.com/introduction/git-handbook/)

## 📚 Resources

- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [VSCode Git Integration](https://code.visualstudio.com/docs/sourcecontrol/overview)
- [GitHub Pull Requests](https://docs.github.com/en/pull-requests)

---

**Happy coding! 🎉**
