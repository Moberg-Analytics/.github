# 📄 CONTRIBUTING.md

### Contributing to Neuromonitoring Analytics

Thank you for your interest in contributing to **Neuromonitoring Analytics**!
This project thrives when clinicians, engineers, and researchers collaborate to build high-quality tools for neuromonitoring and critical-care data analysis.

We welcome contributions of all kinds — code, documentation, notebooks, testing, clinical insight, feedback, and issue triage. No contribution is too small.

---

# 🧭 Table of Contents

1. [Ways to Contribute](#ways-to-contribute)
2. [Before You Begin](#before-you-begin)
3. [Getting Started](#getting-started)
4. [Development Workflow](#development-workflow)
5. [Style Guidelines](#style-guidelines)
6. [Submitting Pull Requests](#submitting-pull-requests)
7. [Reporting Issues](#reporting-issues)
8. [Community & Support](#community--support)

---

# 🌟 Ways to Contribute

You can contribute by:

* Adding new analysis utilities or algorithms
* Submitting bug fixes
* Improving documentation or examples
* Contributing notebooks or tutorials
* Expanding tests or validation suites
* Providing clinical domain insight
* Proposing new features or enhancements
* Reviewing PRs
* Helping shape the roadmap

All skill levels are welcome.

---

# 🛠 Before You Begin

## **1. Join the community**

We coordinate through Discord — please join:
👉 **https://neuromonitoring.com/discord**

## **2. Read the Code of Conduct**

We expect all contributors to follow the
📜 **CODE_OF_CONDUCT.md**

## **3. Check existing Issues & Discussions**

Your idea or bug may already be tracked.
Look for issues labeled:

* `help wanted`
* `good first issue`
* `enhancement`
* `discussion`

If unsure, ask in Discord or open a new issue.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Neuromonitoring-Analytics/<repo-name>.git
cd <repo-name>
```

Install dependencies (example for Python repos):

```bash
pip install -r requirements.txt
```

Or for editable installs:

```bash
pip install -e .
```

Some repos may include additional setup steps — refer to their README.

---

# 🔄 Development Workflow

We use a simple branch flow:

* `main`
  Stable, production-ready code.

* `dev`
  Active development branch.

* **Feature branches**
  Name them like:

  ```
  feature/icp-event-detection
  fix/spectral-leakage-bug
  docs/add-conversion-examples
  ```

### Workflow summary:

1. Create a new branch off `dev`
2. Develop your changes
3. Write or update tests
4. Update documentation or notebooks if needed
5. Submit a Pull Request into `dev`
6. The maintainers will review, request changes, and merge

PRs to `main` are only made by maintainers.

---

# ✏️ Style Guidelines

To keep the codebase clean and professional:

### **Python**

* Follow **PEP8**
* Use type hints
* Prefer functional clarity over cleverness
* Use docstrings (`Google` or `NumPy` style)
* Keep functions small and testable

### **Notebooks**

* Use clear headers
* Include minimal necessary narrative
* Avoid storing large data
* Use relative imports where possible

### **Commits**

Use descriptive messages, e.g.:

```
Add ICP event detector and example notebook
Fix off-by-one error in EDF converter
Improve PRx validation and update tests
```

Avoid vague messages like “update” or “fix stuff”.

---

# 📬 Submitting Pull Requests

A good pull request includes:

* Clear explanation of the change
* Relevant issue number (e.g., “Fixes #42”)
* Before/after examples if UI or visual
* Tests covering the new behavior
* Documentation or notebook updates

PR Template prompts will guide you.

We prefer **small, focused PRs** over giant multi-feature changes.

---

# 🐛 Reporting Issues

When filing an issue, please include:

* **Clear title**
* **Description of the problem or request**
* Steps to reproduce (for bugs)
* Expected vs actual behavior
* Minimal example if possible
* Environment info (OS, Python version, etc.)

For clinical/physiologic algorithms, include any contextual assumptions.

---

# 💬 Community & Support

The best place to ask questions, propose ideas, or collaborate is Discord:

👉 **https://neuromonitoring.com/discord**

You can also use GitHub Discussions for longer-form threads.

Together, we can build tools that accelerate neuromonitoring research and improve patient care.
Thank you for contributing!
— *The Neuromonitoring Analytics Maintainers*
