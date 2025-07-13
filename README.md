# SSL Certificate Expiry Monitor with n8n 🔒

This project automates SSL certificate checks using [n8n](https://n8n.io). It monitors specified domains and alerts when their SSL certificates are nearing expiration — helping teams stay ahead of potential service disruptions.

## 🔧 What It Does
- Periodically checks SSL certificate expiry dates for one or more domains.
- Sends alerts (e.g. via email, Slack, or other channels) if a certificate is close to expiring.
- Easily customizable and extendable to suit your notification needs.

## 🛠️ Built With
- [n8n](https://n8n.io/) – Workflow automation tool
- HTTP Request Node – For querying SSL status
- (Optional) Email/Slack Node – For sending alerts

## 📦 Setup
1. Clone this repo or download `workflow.json`.
2. Import `workflow.json` into your n8n instance.
3. Update the domain list and alerting method in the workflow.
4. Set the workflow to run daily or at your preferred interval.

## 📸 Workflow Preview
![SSL Check Workflow](assets/workflow-screenshot.png)

## 💡 Customization Ideas
- Connect it with a Google Sheet for dynamic domain management
- Add Telegram, Discord, or Microsoft Teams notifications
- Expand it to include other health checks (e.g., uptime, WHOIS expiry)

## 🧠 Inspiration
SSL outages can disrupt trust and access. This automation ensures you're always ahead of certificate renewals — no more surprises.

---
