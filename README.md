# 🚀 GitHub Actions Docker Template

A lightweight DevOps starter template for containerized services using GitHub Actions, Docker, and GitHub Container Registry (GHCR).

This template is designed to eliminate manual server builds and provide a fully automated CI/CD pipeline for modern service deployment.

---

## 🧱 Features

- ⚡ Automated CI/CD via GitHub Actions
- 🐳 Docker-based deployment
- 📦 Container publishing to GitHub Container Registry (GHCR)
- 🌿 Branch-based environments (`dev`, `latest-stable`)
- 🔁 Automatic image tagging based on branch name
- 🖥️ Server-only runtime (no build required on host)
- ♻️ Fully reusable template for multiple services

---

## 🌿 Branch Strategy

| Branch        | Purpose            | Image Tag |
|--------------|--------------------|----------|
| `dev`         | Development        | `dev`    |
| `latest-stable` | Stable production | `latest-stable` |

---

## 🚀 How to Use This Template

1. Click **"Use this template"** on GitHub
2. Create a new repository
3. Clone your new repo:

```bash
git clone https://github.com/TheMux-42/github-actions-docker-template.git
