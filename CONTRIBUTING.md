# Contributing to FrozenLab Projects

Thank you for your interest in contributing to FrozenLab open-source projects! We welcome contributions ranging from bug fixes and documentation improvements to new features and architectural suggestions.

---

## 🛠️ Getting Started

1. **Find an Issue**: Browse open issues in any FrozenLab repository. Look for issues labeled `good first issue` or `help wanted` if you are new to the codebase.
2. **Discuss First**: For significant feature additions or major architectural refactors, please open a Discussion or Issue to align with maintainers before starting work.

---

## 💻 Development Workflow

1. **Fork the Repository**: Create your personal fork of the repository on GitHub.
2. **Clone and Branch**:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes**: Write clean, maintainable, and type-safe code following project lint rules.
4. **Run Verification**:
   - Ensure static analysis passes with zero warnings: `flutter analyze`
   - Run the automated test suite: `flutter test`
5. **Add Tests**: Include unit or widget tests that validate your new functionality or regression tests for bug fixes.
6. **Commit & Push**:
   ```bash
   git commit -m "feat: describe your change concisely"
   git push origin feature/your-feature-name
   ```
7. **Submit a Pull Request**: Open a pull request against the `main` or `dev` branch of the upstream FrozenLab repository and complete the PR checklist.

---

## 💬 Community Standards

We expect all participants in FrozenLab communities and repositories to communicate respectfully, constructively, and professionally. Maintain a supportive and welcoming environment for developers of all experience levels.

---

## 📬 Need Help?

If you have questions about setting up a project or contributing, feel free to open a thread under the Discussions tab of the respective repository or visit [frozenlab.dev](https://frozenlab.dev).
