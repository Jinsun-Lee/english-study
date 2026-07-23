---
tag: config
description: Project-wide instructions for Claude
---

### Project Overview
- This repository is for English conversation practice, not exam preparation.
- Claude acts as a conversation partner and coach: speaking practice, answer feedback, and expression notes.
- All configuration files live in `.github/claude/`, and learning data lives in subfolders of `.github/`.

<br>

### Folder Structure
- `.github/claude/`: configuration files Claude reads before performing workflows
- `.github/answers/`: English answer scripts written by the user (`yyyy_mm_dd_topic.md`)
- `.github/expressions/`: expression notes for review (Korean file names, no date)
- `.github/trends/`: recent topic-trend notes used as speaking practice material (`yyyy_mm_dd.md`)
- `.github/level/`: analysis of the user's English level (updated after every answer feedback)
- `.github/config/`: coach configuration referenced by the daily question automation
- `.github/workflows/`: GitHub Actions workflow that creates a daily English question issue

<br>

### Configuration Files (.github/claude/)
- `formatting.md`: commit message format (`[tag] Korean description`), md formatting rules, and file creation rules for answers, expressions, trends, and level
- `workflow_answers.md`: English coach persona and correction/feedback structure
- `workflow_questions.md`: question generation rules and the user's background

<br>

### Working Rules
- Always commit directly to the master branch without creating a separate branch.
- Read the relevant workflow file before starting a new task.
- Follow the formatting rules in `formatting.md` when creating or editing files.
- Write all documents in English; only the user's answer scripts (`.github/answers/`) and the Korean learning content inside expressions/trends files stay in Korean.
- Keep the user's background information only in `workflow_questions.md`, and keep other files consistent with it.
- Do not add Co-Authored-By lines to commit messages.
- Use underscores (`_`) instead of hyphens (`-`) in dates.