# Contributing to The GFG Open Source Forge

Welcome, and thanks for your interest in contributing! We’re building a friendly, beginner‑friendly open-source ecosystem for student projects.

---

## 📜 Table of Contents

* [Code of Conduct](#-code-of-conduct)
* [Ways to Contribute](#-ways-to-contribute)
* [How to Start](#-how-to-start)
* [Development Workflow](#-development-workflow)
* [Commit Guidelines](#-commit-guidelines)
* [Pull Request Checklist](#-pull-request-checklist)
* [Community](#-community)

---

## ✅ Code of Conduct

By contributing, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful and collaborative.

---

## 🛠 Ways to Contribute

* **Code:** Fix bugs, build features, improve performance.
* **Docs:** Improve README, write tutorials, update API docs.
* **Design:** UI/UX, logos, mockups.
* **Testing:** Write unit/integration tests.
* **Community:** Answer questions, mentor newcomers, review PRs.

---

## 🚀 How to Start

1. **Fork the repository** and clone your fork.

   ```bash
   git clone https://github.com/<your-username>/<forge-project>.git
   cd <forge-project>
   ```
2. **Check Issues** labeled `good first issue` or `help wanted`.
3. **Discuss** in the issue comments or Discord before starting.
4. **Create a branch** for your work:

   ```bash
   git checkout -b feat/<short-topic>
   ```

---

## 🔄 Development Workflow

* **Sync your fork:**

  ```bash
  git remote add upstream https://github.com/<org>/<forge-project>.git
  git fetch upstream
  git rebase upstream/main
  ```
* **Run locally:** Follow instructions in the project README.
* **Push changes:**

  ```bash
  git add .
  git commit -m "feat(auth): add JWT refresh tokens"
  git push origin feat/<short-topic>
  ```
* **Open a PR:** Use the PR template, link the issue (`Closes #<id>`).

---

## 🏷 Commit Guidelines (Conventional Commits)

Format:

```
type(scope): short description
```

**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.

Example:

```
feat(ui): add responsive navbar
fix(auth): resolve token refresh bug
```

---

## ✅ Pull Request Checklist

* [ ] My branch is rebased on `main`.
* [ ] I linked the issue in the PR (e.g., Closes #12).
* [ ] Code is formatted and linted.
* [ ] Tests added/updated where applicable.
* [ ] Documentation updated (README/docs).
* [ ] All CI checks pass.

---

## 💬 Community

* **Discord:** [Join Here](https://discord.gg/REPLACE)
* **GitHub Discussions:** Enabled in this repo.

Need help? Ask in the issue or on Discord! We’re here to support you.
