---
tag: config
description: Commit message and md formatting rules, plus creation rules for learning files
---

### Commit Message Rules
- Use the `[tag] Korean description` format.
- Tags: `docs` (add/edit documents), `chore` (move/delete/organize files), `feat` (add features), `fix` (bug fixes)
- Keep the description to one concise line.
- Do not add Co-Authored-By lines or unnecessary extra text.
- When amending or rebasing a commit, keep the original author date.

<br>

### md Formatting Rules
- These rules apply to every md file, including `.github/`, `.claude/`, and `README.md`.
- Write all documents in English; only the user's answer scripts (`.github/answers/`) and the Korean learning content inside expressions/trends files stay in Korean.
- Put an OKF-format frontmatter at the top of every md file, with only two fields: `tag` and `description`.
- Organize content as bullet points (`-`) under `###` headings.
- Separate `###` sections with a blank line + `<br>` + a blank line.
- Do not split paragraphs unnecessarily.
- Do not leave a blank line at the end of a file.
- Escape any tilde not meant as strikethrough with a backslash: `\~`.
- Describe files in the form ``- `filename`: description``.

<br>

### .github/trends File Rules
- When the user shares recent topic trends, create an md file in `.github/trends/`.
- Name the file `yyyy_mm_dd.md` (e.g. `2024_09_14.md`).
- Always write the year with 4 digits (yyyy).
- Use underscores (_) instead of hyphens (-) in dates.

<br>

### .github/answers File Rules
- When the user shares a full spoken script, create an md file in `.github/answers/`.
- Name the file `yyyy_mm_dd_short_topic.md` (e.g. `2024_08_20_디지털세상과필기.md`).
- Always write the year with 4 digits (yyyy).
- Use underscores (_) instead of hyphens (-) in dates.
- Separate the date and the topic with an underscore (_) as well.

<br>

### .github/level File Rules
- Manage the user's English level analysis in a single file: `.github/level/level_analysis.md`.
- Update the analysis and its date (`yyyy_mm_dd`) every time answer feedback is given.

<br>

### .github/expressions File Rules
- When the user asks to save something for review, create a separate file in `.github/expressions/` with a short description.
- Name the file in Korean without spaces and without a date (e.g. `피드백요청시.md`).
- Add the new entry to the bottom of the root `README.md`.