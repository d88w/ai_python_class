# Python with AI — Class Materials

A hands-on, notebook-based curriculum for learning core Python concepts **and** how to apply them with modern LLMs. Lessons are sequenced and bite-sized, with labs to reinforce skills.
Completion Certificate: https://www.coursera.org/account/accomplishments/verify/FZMUOOBUK248

> This repo consists primarily of Jupyter notebooks organized as short lessons (e.g., f-strings, variables, loops, files, APIs) plus a few labs and a small `helper_functions.py`.  [oai_citation:1‡GitHub](https://github.com/d88w/ai_python_class)

---

## Who is this for?

- **Beginners** who want a practical Python foundation.
- **Analysts/PMs/Builders** who want to pair Python basics with **LLM prompting and simple API usage**.
- Anyone who prefers **interactive notebooks** over slide decks (you run code as you learn).

---

## What you’ll learn (high-level map)

> Lesson titles come from the notebooks in this repo. Exact names may vary slightly in GitHub UI.  [oai_citation:2‡GitHub](https://github.com/d88w/ai_python_class)

**Module 1: Python Basics with Strings**
- *1.07 — f-string*: String formatting and interpolation.
- *1.08 — variables*: Naming, types, assignment.
- *1.09 — LLM prompts with variables*: Build prompts programmatically.

**Module 2: Collections & Logic**
- *2.01 — Completing a task list with AI*
- *2.02 — For loops + LLM*
- *2.03 — Dictionaries + LLM*
- *2.04 — Recipes with lists & dicts + AI*
- *2.05 — Comparing data & booleans*
- *2.06 — `if/else`: help AI make decisions*
- *2.LAB — Book Tracker (project)*

**Module 3: Files & Projects**
- *3.01 — Using files*
- *3.02 — Loading my own files*
- *3.03 — Reading food journals*
- *3.04 — Extracting restaurant info*
- *3.05 — Vacation planning with CSVs*
- *3.06 — Functions*
- *3.07 — Itineraries for multiple cities*
- *3.LAB — Poetry with LLM (project)*

**Module 4: Packages & APIs**
- *4.01 — Using functions from a local file*
- *4.02 — Built-in packages*
- *4.03 — Third-party packages*
- *4.04 — Installing packages*
- *4.05 — Work with APIs*
- *4.06 — APIs to use AI models*
- *4.LAB — Candy Analysis (project)*
- *4.XX — Installing Python & adding OpenAI API keys* (setup walkthrough)

> There are also two small HTML examples (`highlighted_text.html`, `highlighted_sydney.html`) you can open in a browser to see simple rendering demos.  [oai_citation:3‡GitHub](https://github.com/d88w/ai_python_class)

---

## Quick start

### 1) Prereqs (why these?)
- **Python 3.10+** — modern syntax and typing; avoids older package issues.
- **Jupyter** — lets you *run cells inline*, perfect for step-by-step learning.
- **Virtual environment** — keeps your class packages isolated from the rest of your machine.

```bash
# From repo root
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install --upgrade pip

# Minimal tools for this course
pip install jupyter ipykernel
python -m ipykernel install --user --name ai-python-class
