## Contributing to NexusTek Workshop Repositories

Thank you for participating in NexusTek's technical workshops and community events! We appreciate your engagement with our repositories and materials.

---

## Repository Purpose & PR Guidelines

This repository is primarily maintained as a **read-only reference and instructional asset** for active workshops, community labs, and technical demonstrations.

* **During Live Workshops:** To ensure a consistent experience for all participants, we generally **do not accept pull requests** that alter core exercise code, step-by-step instructions, or lab schedules during active event windows.
* **Bug Fixes & Clarifications:** If you notice a typo, broken link, outdated dependency, or an error in our exercise instructions, pull requests and issue submissions are welcome! Please ensure PRs are concise and target the `main` branch.
* **Feature Requests & Enhancements:** Before opening a PR for new features or substantial structural changes, please open a GitHub Issue first to discuss the proposed update with the workshop facilitators.

---

## Getting Started

1. **Fork & Clone:** Fork this repository to your personal GitHub account and clone it locally to work through exercise modules at your own pace.
2. **Branching:** If submitting a fix, create a feature branch off `main`:
```bash
git checkout -b fix/typo-in-lab-1

```


3. **Commit Messages:** Keep commit messages clear and descriptive (e.g., `fix: update Azure SDK version in lab 2 setup`).

---

## Security & Sensitive Data

**Never commit sensitive data to a Pull Request.**

* Ensure all API keys, access tokens, credentials, connection strings, and internal infrastructure URLs are replaced with generic placeholders (e.g., `<YOUR_AZURE_KEY>`).
* Verify that `.env` files and local deployment outputs are included in your `.gitignore`.
* If you discover a security vulnerability, do **not** open a public PR or Issue. Please follow our [SECURITY.md](SECURITY.md) guidelines and report it directly to **SOC@nexustek.com**.

---

## Code of Conduct

By participating in issues, pull requests, or workshop discussions in this repository, you agree to abide by our community standards. Keep communications respectful, inclusive, and professional.
