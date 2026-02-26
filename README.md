# Droopie's Umbrel App Store

A custom community app store for [Umbrel](https://umbrel.com).

## Apps Included

| App | Description | Category |
|-----|-------------|----------|
| **Whoami** | Simple web server that exposes OS information | Utilities |
| **Plane** | Open Source JIRA, Linear, Monday, and Asana Alternative | Productivity |
| **DeerFlow** | Community-driven Deep Research framework | AI |
| **Twenty** | #1 Open-Source CRM — alternative to Salesforce | Business |
| **Crawl4AI** | Open-source LLM Friendly Web Crawler & Scraper | Development |
| **NocoBase** | Extensible AI-powered no-code platform | Business |
| **Open Notebook** | AI-powered note-taking & research platform | Productivity |

## How to Use

1. Open your **Umbrel dashboard**.
2. Go to the **App Store**.
3. Click the three dots (⋮) in the top-right corner.
4. Select **Community App Stores**.
5. Paste this repository's GitHub URL and click **Add**.

You'll then see **Droopie's App Store** alongside the official Umbrel store.

## Adding Your Own Apps

Create a new directory named `droopie-<app-name>` and add:
- `umbrel-app.yml` — App metadata (name, description, icon, etc.)
- `docker-compose.yml` — Docker service definitions

Commit, push, and your Umbrel will automatically pick up the changes.
