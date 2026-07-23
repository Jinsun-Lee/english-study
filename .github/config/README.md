---
tag: readme
description: OpenAI usage link and automation folder structure
---

# Description  
Link to check [OpenAI API usage](https://platform.openai.com/settings/organization/usage).
```
study-english/
 ├─ .github/
 │    ├─ workflows/                       # GitHub Actions automation
 │    │    ├─ daily-question.yml          # creates a daily English question issue
 │    │    ├─ issue-date.yml.disable      # (disabled) prefixes issue titles with the date
 │    │    └─ scripts/                    # Python scripts run by the workflows above
 │    │         └─ generate_question.py   # (currently unused) generates questions via OpenAI
 │    │
 │    └─ config/                          # coach configuration for the daily question automation
 │         ├─ README.md                   # this file
 │         └─ coach.md                    # coach persona + feedback rules + question generation rules
 │
 └─ README.md                             # repository overview
```