# 🟢 Ultimate GitHub Streak Bot

![GitHub Actions](https://img.shields.io/badge/Status-Automated-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/ayushraistudio/daily-streak-bot?style=social)

A smart, fully automated bot that keeps your GitHub contribution graph active and green. Unlike simple bots, this one uses a **realistic 7-day cycle** to mimic human behavior.

## 🚀 Features

- **🤖 Fully Automated:** Runs on GitHub Actions (No server required).
- **📅 Realistic Pattern:** Different commit counts for every day of the week:
  - `Mon: 32` | `Tue: 28` | `Wed: 37` | `Thu: 26` | `Fri: 22` | `Sat: 47` | `Sun: 34`
- **🧹 Auto-Cleanup:** Automatically resets the log file at 10 PM to keep the repo size small.
- **🔒 Secure:** Uses GitHub Secrets so your email is never exposed in the code.
- **⚡ Zero Maintenance:** Set it once, and forget it.

---

## 🛠️ How to Use (For Your Own Profile)

Want this green graph for yourself? Follow these simple steps:

### 1. Fork this Repository
Click the **Fork** button at the top right corner of this page to create a copy in your own GitHub account.

### 2. Enable Permissions
Go to your forked repository:
1. Click on **Settings** > **Actions** > **General**.
2. Scroll down to **Workflow permissions**.
3. Select **"Read and write permissions"**.
4. Click **Save**.

### 3. Add Your Email Secret (Important!)
To make sure the commits count towards YOUR profile:
1. Go to **Settings** > **Secrets and variables** > **Actions**.
2. Click **New repository secret**.
3. **Name:** `USER_EMAIL`
4. **Value:** Your exact GitHub email address.
5. Click **Add secret**.

### 4. Activate the Bot
1. Go to the **Actions** tab.
2. Click on **"Ultimate Streak Bot"** in the left sidebar.
3. Click **Run workflow** to start it immediately.
4. After this, it will run automatically on the scheduled time!

---

## 🤝 Support

If this project helped you get a greener profile, please consider giving it a **Star ⭐**! It helps others find this repo.

---

## ⚠️ Disclaimer
This tool is for educational and testing purposes (testing CRON jobs and GitHub Actions). Use it responsibly.
