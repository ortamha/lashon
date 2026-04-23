# Contributing to HaLev HaLashon

**First off — thank you for wanting to contribute.** This project exists to restore the original meaning of Hebrew Scripture, layer by layer. Every contribution brings us closer to that goal.

---

## Table of Contents

- [What We Do](#what-we-do)
- [How to Contribute](#how-to-contribute)
- [Contribution Guidelines](#contribution-guidelines)
- [Setting Up the Project Locally](#setting-up-the-project-locally)
- [What We Need Help With](#what-we-need-help-with)
- [Style Guide](#style-guide)
- [Code of Conduct](#code-of-conduct)
- [Questions?](#questions)

---

## What We Do

HaLev HaLashon (הלב הלשון) is an AI-powered project that:

1. Detects Greek, Latin, and Slavonic distortions in biblical translations
2. Restores Hebrew words to their original, concrete meaning
3. Provides tools (CLI, API, web interface) for anyone to analyze Scripture

We are not creating a "new translation." We are providing **a tool for discernment.**

---

## How to Contribute

You don't need to be a coder or a Hebrew scholar to help.

### For Everyone

| Contribution | Difficulty | Time |
|--------------|------------|------|
| ⭐ Star the repository | Beginner | 1 minute |
| 🐛 Report a bug (Issue) | Beginner | 5 minutes |
| 💡 Suggest a feature (Issue) | Beginner | 5 minutes |
| 📝 Fix a typo in docs | Beginner | 10 minutes |
| 🌐 Improve or translate documentation | Beginner | 30 minutes |
| 🔍 Test the CLI on different verses | Beginner | 15 minutes |

### For Hebrew Readers / Scholars

| Contribution | Difficulty | Time |
|--------------|------------|------|
| ✡️ Add new word to `patterns.json` | Intermediate | 20 minutes |
| 📚 Verify root meanings against BDB | Intermediate | 30 minutes |
| 🕯️ Write a full concept analysis (using the Seven Gates) | Advanced | 2-3 hours |
| 🗺️ Map a biblical theme across books | Advanced | 2-3 hours |

### For Developers / NLP Engineers

| Contribution | Difficulty | Time |
|--------------|------------|------|
| 🐍 Improve `sources.py` (Sefaria integration) | Intermediate | 1-2 hours |
| 🤖 Train the corruption detection model | Advanced | 1-2 days |
| 🖥️ Add features to CLI | Intermediate | 2-4 hours |
| 📡 Optimize API performance | Advanced | 2-4 hours |
| 🧪 Write unit tests | Intermediate | 1-2 hours |

### For Designers / Frontend

| Contribution | Difficulty | Time |
|--------------|------------|------|
| 🎨 Improve the web interface CSS | Beginner | 1-2 hours |
| 📱 Make the web interface mobile-friendly | Intermediate | 2-4 hours |
| 🖼️ Add visualizations for concept shifts | Advanced | 4-6 hours |

---

## Contribution Guidelines

### Issue First

Before opening a Pull Request, please open an Issue describing what you want to do. This prevents duplicate work and ensures your contribution fits the project's direction.

**Good Issue:**
> **Title:** Add analysis for the word "קָרְבָּן" (Korban)  
> **Body:** Seven Gates breakdown showing how "sacrifice" lost the meaning "drawing near." I have BDB and Tanakh references ready.

**Bad Issue:**
> "I want to add stuff"

### One Thing Per Pull Request

Keep PRs focused. One word analysis per PR. One bug fix per PR. One feature per PR. This makes review faster.

### Sign Your Commits (Optional but appreciated)

```bash
git commit -s -m "feat: add Chesed restoration analysis"
