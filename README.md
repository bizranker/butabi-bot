# 🤖 ButabiBot

> _"You. Me. DevOps. Now."_

ButabiBot is an intelligent GitHub Actions bot built to announce code changes, issue real-time decrees, and bring the party straight to your Slack channels. Inspired by the legendary club kings from *A Night at the Roxbury*, ButabiBot transforms commits into divine proclamations.

---

## ⚙️ Features

- 🔔 **Commit Decrees**: Instantly notifies Slack when code is pushed to `main`
- 🎙️ **Slack Integration**: Posts rich, formatted messages with commit info
- 🧙 **GitHub Actions Automation**: All workflows managed via `.github/workflows`
- 🧞 **Manifesto-Ready**: Part of the Codex Manifestatio and the US Reliance automation doctrine
- 🪄 **Magic Touch**: Built to scale into predictive ops, welcome rituals, and decree pipelines

---

## 🗃️ Repo Structure

```bash
.
├── README.md
└── .github
    └── workflows
        ├── butabi.yml           # Core commit-to-Slack workflow
        ├── send-welcome.yml     # New member welcome messages
        └── slack-alert.yml      # General-purpose Slack alerts
