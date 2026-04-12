

# Contributing to CodeVibe

Thank you for your interest in contributing to CodeVibe.
Please follow the steps and guidelines below to ensure a smooth contribution process.

---

## Getting Started

### 1. Fork the Repository

Create your own copy of the repository by clicking the **Fork** button.

---

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/CodeVibe.git   # Clone your fork
cd CodeVibe                                                 # Navigate into the project folder
```

---

### 3. Add Upstream Repository

```bash
git remote add upstream https://github.com/JiyaBatra/CODEVIBE-.git   # Link original repository
git remote -v                                                         # Verify remotes
```

---

### 4. Create a New Branch

```bash
git checkout -b feature/your-feature-name   # Create and switch to a new branch
```

---

## Sync Your Fork

Always sync your fork before starting any work:

```bash
git fetch upstream            # Fetch latest changes from original repository
git checkout main             # Switch to main branch
git merge upstream/main       # Merge updates into your local main
git push origin main          # Push updated main to your fork
```

---

## Making Changes

* Keep changes minimal and relevant
* Follow the existing project structure
* Avoid modifying unrelated files

---

## Commit and Push

```bash
git add .                                   # Stage changes
git commit -m "Add: meaningful message"     # Write a clear commit message
git push origin feature/your-feature-name  # Push your branch
```

After pushing, create a Pull Request.

---

## Contribution Rules

### Issues

* Issues are assigned on a **first come, first serve** basis
* Raising an issue does **not guarantee assignment**
* Maintainers will assign issues

---

### Code and Design

* Do not change styling unless necessary
* Do not break existing UI
* Only required changes should be made
* Maintain a professional coding approach

---

## Notes

* Some features (e.g., progress reports) may temporarily stop working during updates
* Do not modify core functionality without prior discussion
* Always check existing issues before creating a new one

---

## Communication

* Keep communication clear and concise
* Ask questions if you are stuck
* Stay relevant in discussions

---

## Best Practices

* Keep Pull Requests small and focused
* Sync your fork before starting work
* Write clean, readable, and maintainable code

---

