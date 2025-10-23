# Python with AI — Class Materials

A hands-on, notebook-based curriculum for learning core Python concepts **and** how to apply them with modern LLMs. Lessons are sequenced and bite-sized, with labs to reinforce skills.

My Completion Certificate: https://www.coursera.org/account/accomplishments/verify/FZMUOOBUK248

> This repo consists primarily of Jupyter notebooks organized as short lessons (e.g., f-strings, variables, loops, files, APIs) plus a few labs and a small `helper_functions.py`.

---

## Who is this for?

- **Beginners** who want a practical Python foundation.  
- **Analysts / PMs / Builders** who want to pair Python basics with **LLM prompting and simple API usage**.  
- Anyone who prefers **interactive notebooks** over slides — you *run code as you learn*.

---

## What You’ll Learn

### Module 1: Python Basics with Strings
- `1.07 — f-string`: String formatting and interpolation  
- `1.08 — variables`: Naming, types, assignment  
- `1.09 — LLM prompts with variables`: Build prompts programmatically  

### Module 2: Collections & Logic
- `2.01 — Completing a task list with AI`  
- `2.02 — For loops + LLM`  
- `2.03 — Dictionaries + LLM`  
- `2.04 — Recipes with lists & dicts + AI`  
- `2.05 — Comparing data & booleans`  
- `2.06 — if/else: help AI make decisions`  
- `2.LAB — Book Tracker (project)`  

### Module 3: Files & Projects
- `3.01 — Using files`  
- `3.02 — Loading my own files`  
- `3.03 — Reading food journals`  
- `3.04 — Extracting restaurant info`  
- `3.05 — Vacation planning with CSVs`  
- `3.06 — Functions`  
- `3.07 — Itineraries for multiple cities`  
- `3.LAB — Poetry with LLM (project)`  

### Module 4: Packages & APIs
- `4.01 — Using functions from a local file`  
- `4.02 — Built-in packages`  
- `4.03 — Third-party packages`  
- `4.04 — Installing packages`  
- `4.05 — Work with APIs`  
- `4.06 — APIs to use AI models`  
- `4.LAB — Candy Analysis (project)`  
- `4.XX — Installing Python & adding OpenAI API keys`  

There are also two small HTML examples — `highlighted_text.html` and `highlighted_sydney.html` — which you can open directly in a browser.

---

## Quick Start

### 1. Prerequisites
- **Python 3.10+** — modern syntax and typing support  
- **Jupyter** — to run code interactively  
- **Virtual environment** — keeps dependencies isolated  

```bash
# From repo root
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install --upgrade pip

# Install core tools
pip install jupyter ipykernel
python -m ipykernel install --user --name ai-python-class
```

This repo is almost entirely notebooks, so there’s no heavy `requirements.txt`. You’ll install packages lesson-by-lesson (like `requests`, `pandas`, etc.) as you go.

---

### 2. (Optional) OpenAI Access
Some lessons use the OpenAI API.

```bash
export OPENAI_API_KEY="sk-..."     # PowerShell: $env:OPENAI_API_KEY="sk-..."
```

Then install the package when needed:

```bash
pip install openai
```

Using environment variables keeps secrets out of source control.

---

### 3. Launch the Notebooks

```bash
jupyter notebook
# or
jupyter lab
```

Open any `.ipynb` file and run the cells top to bottom.

---

## Suggested Learning Path

1. **Strings → variables → f-strings**: understand how data moves through code.  
2. **Lists/dicts → loops → conditionals**: express logic and patterns.  
3. **Files/CSV/project notebooks**: apply Python to real-world data tasks.  
4. **Packages & APIs**: connect Python to the wider ecosystem and AI tools.

This sequence mirrors how learners build durable intuition: concept → practice → project.

---

## Repository Structure

| File / Folder | Description |
|----------------|-------------|
| `Python with AI *.ipynb` | Individual lessons and labs |
| `helper_functions.py` | Utility functions for reuse |
| `highlighted_*.html` | Example HTML demos for visualization |

---

## Troubleshooting

| Issue | Fix |
|-------|-----|
| **Package not found** | `pip install <name>` and restart kernel |
| **API key errors** | Make sure `OPENAI_API_KEY` is set in your terminal |
| **Notebook won’t run in order** | Use “Kernel → Restart & Run All” |
| **File path errors** | Check working directory: `import os; os.getcwd()` |

---

## Contributing

- Keep lessons *atomic* (one concept per notebook).  
- Prefer clarity and print statements over clever tricks.  
- Use Markdown cells liberally for explanations.

---

## License

⚠️ No license file is currently included.  
If you plan to share or remix these materials, consider adding a license such as **MIT** (for code) or **CC BY-SA** (for educational content).  
Without one, the default is *All Rights Reserved*.

---

## Why It’s Structured This Way

- **Learner-first**: mirrors the lesson sequence in the repo.  
- **Minimal setup**: dependencies taught contextually, not preloaded.  
- **Best practice**: secure API key usage and environment isolation.  
- **Extendable**: easy to add future notebooks or labs.

---

Happy coding — and enjoy building Python + AI intuition, one notebook at a time!

