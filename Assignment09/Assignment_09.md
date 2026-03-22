# MIS312 Assignment 9 — Automating Tedious Tasks

**Book Alignment:** Chapter 9  
**Primary Goal:** Automate a repetitive text/file task  
**Environment:** JupyterLab + VS Code (`.ipynb`)  
**Submission:** OneNote Artifact (PDF)

---

## Learning Objectives
- Read a text file
- Loop over lines
- Write results to a new file

---

## Student Tasks
1. Create `names.txt` (8–12 names, one per line).
2. Write a notebook that:
   - reads names
   - ignores blank lines
   - prints a numbered list
   - writes `names_report.txt`

### AI improvement (required)
Ask how to ignore blank lines while numbering correctly; implement it.

---

## VS Code Exercise — File Automation as a Script (.py)

### Task 4 — Create a script version
1. In VS Code, create: `C:\Users\<StarID>\MIS312\assignment09\`
2. Create: `names_automation.py`
3. The script must:
   - Read `names.txt`
   - Ignore blank lines
   - Print a numbered list
   - Write `names_report.txt`

### Task 5 — Run it and verify file output
Run:
```powershell
python names_automation.py
```
Then open `names_report.txt` in VS Code and confirm it looks correct.

### Task 6 — Troubleshooting (required)
Create a deliberate issue and fix it:
- Example: rename `names.txt` to `Names.txt` and see the file-not-found error
- Fix the filename, re-run successfully

### Add to OneNote Artifact
- Screenshot: successful VS Code terminal run
- Screenshot: file-not-found error + your fix
- Screenshot: `names_report.txt` contents


## OneNote Artifact Requirements
- Code snippets
- Output screenshot
- Screenshot of `names_report.txt`
- AI prompt + summary
- Reflection: One business task this could automate
