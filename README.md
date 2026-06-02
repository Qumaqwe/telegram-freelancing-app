# CoreTalent — Telegram Mini App

Freelance exchange inside Telegram.

---

## Installation and launch

Follow these steps to run the project on your computer:

1. **Clone the repository:**
```bash
git clone https://github.com/Qumaqwe/telegram-freelancing-app.git
```

2. **Navigate to the project directory:**
```bash
cd telegram-freelancing-app
```

## 🛠 CI/CD and Automation

The project has automated security and testing workflows configured via GitHub Actions. The following checks run automatically on every push or Pull Request:
- **Dependency Check (`dependency-check.yml`):** Scans used dependencies and libraries for known vulnerabilities.
- **Gitleaks (`gitleaks.yml`):** Scans the repository to detect accidentally committed secrets, API tokens, and credentials.
- **Semgrep (`semgrep.yml`):** Static Application Security Testing (SAST) to find bugs and security vulnerabilities in the source code.
- **Smoke Tests (`smoke-test.yml`):** Runs a basic suite of tests to verify the core functionality of the application after code changes. 