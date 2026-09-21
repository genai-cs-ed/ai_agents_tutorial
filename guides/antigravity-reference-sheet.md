# Antigravity AI Agent: Reference Sheet for Non-Coding Workflows

A practical guide for using Antigravity on your computer for **research, writing, policy review, academic advising, data analysis, and everyday knowledge work**.

---

## Before You Start

* **Antigravity is a separate download.** It is a free Google application and is not on WashU's approved AI tools list.
* **Use made-up data.** Do not put student records, health information, or other sensitive material into Antigravity.

---

## 1. Where to Provide Your Project Instructions

You do **not** need to re-explain your role, tone, or rules in every message. Place a **`GEMINI.md`** file directly in your project folder, and Antigravity will automatically discover and apply it:

| Scope | Location | What Goes Here |
| :--- | :--- | :--- |
| **Project Folder** *(Standard)* | **`GEMINI.md`** in your project folder | Persona, tone, writing style, formatting standards, source citation rules |
| **Subfolder** | `reports/GEMINI.md` or `drafts/GEMINI.md` | Guidelines that apply only to specific folders (e.g., final reports vs. brainstorming notes) |
| **Across Your Computer** | `~/.gemini/config/` or App Settings | Personal defaults (e.g., your bio, default reading level, preferred unit system) |
| **Live Learning** | Type **`/learn`** in chat | Saves a correction or rule permanently so the agent remembers it next time |

### Example Non-Coding `GEMINI.md`
```markdown
# Project Guidelines: Academic Research & Advising

## Role & Voice
- Act as an academic advisor and senior researcher.
- Tone: Professional, encouraging, objective, and clear.

## Rules & Constraints
- Always cite specific documents or page numbers when referencing requirements.
- Never modify or overwrite original files (e.g., `/raw_transcripts/`); always save outputs as new files in `/output/`.
- Format schedules, comparisons, and unit counts as Markdown tables.

## Workflow
- For documents longer than 2 pages, propose an outline and wait for my review before writing.
```

---

## 2. What Antigravity Can Do Beyond Coding

Antigravity operates directly on your computer's filesystem and tools:

* **Document & Transcript Analysis**: Reads PDFs, Word docs, text files, and transcripts to extract themes, find inconsistencies, or audit requirements.
* **Spreadsheets & Data**: Inspects CSVs/data files, computes totals, identifies outliers, and compiles summaries.
* **Live Web Research**: Searches the web, reads current articles, and synthesizes findings with source links.
* **Diagrams & Visuals**: Generates workflow diagrams, organizational charts, and custom images.
* **Interactive Previews**: Builds tabbed visual dashboards and interactive review widgets directly in the chat.
* **Automated Scheduling**: Sets reminders, timers, or recurring daily/weekly background tasks (`/schedule`).

---

## 3. Supplying Context with `@` Mentions

Direct the agent to your local files using `@` in the chat input:

* **`@transcript.txt`**: *"Extract the main action items and unresolved questions."*
* **`@policy.pdf`**: *"Audit our draft proposal in `@draft.md` against Section 4 of this policy."*
* **`@survey_results.csv`**: *"Summarize the top 3 complaints from participants."*
* **`@folder/`**: *"Review all documents in this folder and create an index table."*

---

## 4. The 3-Part Prompt Formula for Knowledge Work

**Deliverable + Source Context + Format / Constraints**

### Example Prompts:
* **Meeting / Interview Synthesis**:
  > *"Read `@sample-transcript.txt`. Extract action items, key decisions, and any unresolved questions into a markdown table with columns: 'Topic', 'Decision/Action', 'Owner', and 'Next Steps'."*

* **Grant / Proposal Writing**:
  > *"Using `@notes.txt` and `@grant_criteria.pdf`, draft the 'Project Methodology' section. Write in an authoritative academic tone, limit it to 800 words, and structure it with bolded subheadings."*

* **Curriculum / Project Planning**:
  > *"Review `@degree_requirements.pdf` and `@my_credits.txt`. Build a 4-semester graduation roadmap, ensuring all general education and major requirements are satisfied. Propose an outline first before writing the full document."*

---

## 5. Essential Slash Commands for Knowledge Work

| Slash Command | How to Use It for Non-Coding Work |
| :--- | :--- |
| **/goal** | Autonomous deep work *(e.g., "Read all 8 reports in this folder and compile a comprehensive 5-page synthesis")*. |
| **/grill-me** | The agent interviews you with targeted questions to flesh out an article outline, proposal, or strategy before writing. |
| **/schedule** | Runs a recurring task or reminder *(e.g., "Remind me in 2 hours to review the draft," or "Check this website every Monday morning")*. |
| **/browser** | Allows the agent to look up live websites, conference dates, or public documents. |
| **/learn** | Teaches the agent a persistent habit or rule based on recent feedback. |

---

## 6. Pro Tips for Daily Use

1. **Ask for Outlines First**: For long essays, articles, or reports, ask the agent: *"Give me an outline first, and wait for my feedback before writing the full draft."*
2. **Use Markdown Preview**: View documents in rendered visual mode by pressing Cmd + Shift + V (Mac) or clicking the Preview icon in the top right corner of your editor.
3. **Keep Raw Files Untouched**: Instruct the agent: *"Do not edit my original files; save all edits as `draft_v2.md` or in an `outputs/` folder."*
4. **Interactive Displays**: Ask the agent to *"Show this as an interactive preview or visual dashboard"* to turn static lists and tables into interactive widgets.
