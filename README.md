# Daily Commit Bot

This repository uses a GitHub Action to automatically make a commit every day.  
Its purpose is to help developers maintain their GitHub contribution streak.

## 🔧 How It Works

- A GitHub Actions workflow runs every day at 00:00 UTC.
- It appends the current date and time to a file named daily-log.txt.
- If the file changes, it commits and pushes the update.
- If there are no changes, it does nothing (and won't break).

## 📁 Files

- .github/workflows/daily-commit.yml — The GitHub Actions workflow definition.
- daily-log.txt — The file that gets updated daily.
- README.md — This file.

## ✅ How to Use

1. Fork or clone this repo.
2. Push it to your own GitHub account.
3. Enable GitHub Actions (if not already enabled).
4. Done — the bot will now commit daily!

## 🧠 Why Use This?

- Maintain your green square streak 📅
- Test GitHub Actions and cron jobs ⏱️
- Keep an active-looking GitHub profile 🚀

## ⚠️ Notes

- Make sure the repo is public or you’ve enabled private contributions in GitHub settings.
- Don’t use this to fake real work — it's best as a learning tool or streak helper.

---

Created with ❤️ using GitHub Actions.
