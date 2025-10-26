<h1 align="center">n8n</h1>

<p align="center">
  <strong>Personal collection of n8n workflows & templates</strong><br>
  Designed & maintained by <strong>Abhiman G S (abhimangs)</strong>
</p>

<p align="center">
  <a href="https://github.com/abhimangs/n8n/releases"><img src="https://img.shields.io/github/v/release/abhimangs/n8n?style=flat" alt="release"></a>
  <a href="https://github.com/abhimangs/n8n/stargazers"><img src="https://img.shields.io/github/stars/abhimangs/n8n?style=flat" alt="stars"></a>
  <a href="https://github.com/abhimangs/n8n/actions"><img src="https://img.shields.io/github/actions/workflow/status/abhimangs/n8n/ci.yml?style=flat" alt="ci"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-brightgreen?style=flat" alt="MIT"></a>
</p>

## 🚀 What is this repo
My personal collection of n8n workflows and templates. Each JSON file is ready to be imported into your n8n instance.

## ✨ Features
- Clean, import-ready JSON workflows.
- Reusable templates for common tasks (Notion, Telegram, YouTube).
- Simple docs and screenshots for each workflow.
- Clear guidance on credentials. **Never commit secrets!**

## ⚙️ Quick Start
1.  Clone this repo: `git clone https://github.com/abhimangs/n8n.git`
2.  In your n8n instance: `Import` → `File` → Choose a `.json` file from the `workflows/` folder.
3.  Configure your credentials (e.g., API keys) as noted in the `docs/` folder.

## 🧾 How Workflows Are Organized
Each `.json` workflow has a matching `.md` file in the `docs/` folder. This doc explains what it does, the nodes used, and the credentials or environment variables required.

## 🔒 Secrets & Safety
- **Never** store API keys or secrets directly in this repo.
- Use n8n Credentials or environment variables.
- Document the *required keys* (not the values) in `docs/env-variables.md`.

## 🧩 Example Workflows
(See `workflows/` for all files and `docs/` for setup details.)

| File | Purpose |
| :--- | :--- |
| `001-notion-sync.json` | Sync new Notion DB rows to Google Sheets |
| `002-youtube-notifier.json` | Notify Telegram when a channel uploads |
| `003-discord-reminder.json` | Scheduled reminders to a Discord channel |

## 🛠️ Contributing
Contributions are welcome!
1.  Open an issue to discuss your idea.
2.  Create a PR with your new workflow `.json` and its matching `.md` doc.
3.  Please ensure no secrets are included in your PR.

## 🤝 License & Support
This project is licensed under the **MIT License**. If you need help, feel free to open an issue.

## 🌐 Connect
- **LinkedIn:** https://www.linkedin.com/in/abhimangs
- **Email:** theabhimangs@gmail.com
- **n8n Creator:** https://n8n.io/creators/<your-creator-slug>

## 🧠 Pro Tips
- Use `.env` files for local development.
- Back up your n8n instance regularly.
- Link to a short video demo for complex workflows.

## 🙏 Credits
Made with care by **Abhiman G S (abhimangs)**.
