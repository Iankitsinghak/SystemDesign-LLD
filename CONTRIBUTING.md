# 🤝 Contributing to System Design + LLD Hacktoberfest Repository

Thank you for your interest in contributing! 🎉  
This document provides clear guidelines and instructions for making valuable contributions to this project.

---

## 🎯 Getting Started

### Prerequisites
- A **GitHub account**
- **Git** installed locally
- Basic understanding of **OOP concepts**, **System Design**, or **Data Structures**
- Familiarity with **Git workflow** (fork, branch, commit, PR)

### For First-Time Contributors
If this is your first contribution to open source:
- Read this guide carefully 👇  
- Check out [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- Look for beginner-friendly issues (`good first issue`)
- You can start small — even a UML diagram or a minor doc update helps!

---

## 🔄 Contribution Workflow

### 1. Fork and Clone
```bash
# Fork this repo on GitHub, then clone your fork
git clone https://github.com/<your-username>/system-design-lld-hacktoberfest.git
cd system-design-lld-hacktoberfest

# Add upstream remote
git remote add upstream https://github.com/AnkitSinghXD/system-design-lld-hacktoberfest.git
```

### 2. Create a Branch
```bash
# Create and switch to a new branch
git checkout -b feature/<project-name>
```
**Example branch names:**
- feature/splitwise-lld
- add/netflix-system-design
- fix/uml-diagram-update

### 3. Make Your Changes

Navigate to the correct project folder:

**📁 For Low-Level Design (LLD)**
```bash
cd projects/lld/<project-name>
```
_Example:_
```
projects/lld/snake-and-ladder/
├── README.md
├── uml.png
├── code.cpp
└── notes.md
```

**📁 For System Design**
```bash
cd projects/system-design/<project-name>
```
_Example:_
```
projects/system-design/instagram/
├── README.md
├── architecture.md
└── diagram.png
```

Add one or more of the following:
- 💻 Code (.cpp, .java, .py, etc.)
- 🧩 UML or Architecture Diagram (.png / .drawio)
- 📝 Explanation or Notes (README.md / notes.md)

💡 You can contribute just one part (only UML or code) — no need to include everything!

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add LLD for Parking Lot in C++ with UML"
```

**Commit message format examples:**
- Add LLD for Splitwise in Java
- Add UML diagram for Snake and Ladder
- Fix incorrect relationship in Parking Lot UML

### 5. Keep Your Fork Updated
```bash
git fetch upstream
git merge upstream/main
```

### 6. Push and Create a Pull Request
```bash
git push origin feature/<project-name>
```
Then, go to your fork on GitHub and open a Pull Request.

---

## ✅ Ensure your PR:

- Follows the folder structure
- Includes a clear title & description
- Adds real value (no spam / duplicate content)

---

## ✅ Code & Design Quality Guidelines

### General Rules
- 🧠 **Original Work:** No plagiarism — write or explain in your own words.
- 💬 **Documentation:** Each design must have a short README or doc.
- 📊 **Complexity:** Mention time & space complexity where relevant.
- 🧪 **Testing:** Provide examples, sample runs, or use-cases.
- ✨ **Formatting:** Clean, consistent, and readable code.

### 📂 Folder and File Organization

**Structure:**
```
projects/
├── lld/
│   ├── parking-lot/
│   │   ├── README.md
│   │   ├── code.cpp
│   │   ├── uml.png
│   │   └── notes.md
│   └── splitwise/
│       ├── code.java
│       ├── uml.png
│       └── README.md
└── system-design/
    ├── instagram/
    │   ├── README.md
    │   ├── architecture.md
    │   └── diagram.png
    └── uber/
        ├── README.md
        └── diagram.png
```

**Naming Conventions**

| Language | Example Name             |
|----------|-------------------------|
| C++      | snake_and_ladder.cpp    |
| Java     | Splitwise.java          |
| Python   | snake_and_ladder.py     |
| UML      | uml.png / uml.drawio    |

---

## 🚫 What NOT to Do

❌ Don’t submit:
- Duplicate files or existing solutions
- Incomplete / non-compiling code
- Code copied from online sources
- PRs that only add whitespace, comments, or emojis
- Unrelated files like .DS_Store, .vscode/, or compiled binaries

---

## ✨ PR Review Process

- Automated checks and format validation
- Maintainers review your PR
- You might get suggestions or feedback
- Once approved → PR merged 🚀

If changes are requested:
```bash
git add .
git commit -m "Fix: updated UML naming"
git push origin feature/<project-name>
```

---

## 🏆 Recognition

Contributors will be:
- Added to the Contributors Section 🏅
- Credited in the commit history
- Eligible for Hacktoberfest Rewards 🎃

---

## 🎯 Hacktoberfest-Specific Guidelines

To qualify:
- Register on [hacktoberfest.com](https://hacktoberfest.com/)
- Submit quality PRs (no spam)
- 4 accepted PRs = 🎁 official swag

---

## 📜 CODE OF CONDUCT

**Our Standards**

We are committed to providing a friendly, inclusive environment for everyone.

**Be Respectful:**
- Welcome all skill levels
- Give constructive feedback
- Value all contributions

**Be Supportive:**
- Help others improve
- Encourage discussion, not criticism

**Unacceptable Behavior**
- 🚫 Harassment or discrimination
- 🚫 Trolling or insulting comments
- 🚫 Spam or self-promotion
- 🚫 Publishing private info without consent

Violations may result in PRs being closed or contributors being blocked.

**Reporting Issues**

If you witness or experience misconduct:
- Open an issue with the label `conduct-violation`, or
- Contact the maintainers privately through email (listed in repo description)

---

## 📚 Additional Resources

- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Writing Good Commit Messages](https://www.conventionalcommits.org/en/v1.0.0/)
- [How to Write a Good PR Description](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/)
- [Hacktoberfest Official Site](https://hacktoberfest.com/)

---

❤️ **Thank You for Contributing!**

Your efforts make this repo valuable for thousands of learners.  
Let’s make Hacktoberfest 2025 the biggest collab yet! 🚀  
Happy Coding 💻✨
