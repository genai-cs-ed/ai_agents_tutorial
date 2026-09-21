# Claude Cowork: Reference Sheet for Non-Coding Workflows

A practical guide for using Claude Cowork on your computer for **research, writing, policy review, academic advising, data analysis, and everyday knowledge work**.

---

## Before You Start

* **Sign in** at claude.ai with your WashU email and WashU Key. Look at the top of the left sidebar: it should say **Claude Edu**. Cowork is available in Claude Edu, not in Claude Secure.
* **Use the Claude desktop app.** Cowork can only read and write files on your computer through the desktop app, and the app must stay open and connected while a task that uses your files or the browser is running.
* **Check your plan.** Cowork is offered on paid plans (Pro, Max, Team, Enterprise). WashU faculty and staff use a paid Claude Edu plan; students get Claude Edu free after completing the AI Literacy module. If you do not see Cowork in the message box, ask your department or WashU IT.
* **Mind your data.** Claude Edu is not approved for protected health information. If you are unsure what you may share, use made-up data.

---

## 1. Where to Provide Your Instructions

You do **not** need to re-explain your role, tone, or rules in every message. Cowork reads saved instructions at several levels:

| Scope | Where to Set It | What Goes Here |
| :--- | :--- | :--- |
| **Global Instructions** | **Settings > Cowork > Edit** next to Global instructions (in the newer app layout: **Instructions for Claude** under **Settings > General**) | Personal defaults for every task: your role, default reading level, preferred tone |
| **Folder Instructions** | Added when you select a local folder on the desktop app | Guidelines for one project folder: writing style, formatting standards, source citation rules |
| **Project Instructions** | **Projects** in the left sidebar | A project's own files, context, instructions, and memory, kept together |
| **Live Learning** | Tell Claude in chat: *"Add this rule to my folder instructions."* | Saves a correction so it is applied next time. Claude can also update folder instructions on its own during a session. |

### Example Non-Coding Instructions

```markdown
# Project Guidelines: Academic Research & Advising

## Role & Voice
- Act as an academic advisor and senior researcher.
- Tone: Professional, encouraging, objective, and clear.

## Rules & Constraints
- Always cite specific documents or page numbers when referencing requirements.
- Never modify or overwrite original files (for example, the raw_transcripts folder); always save outputs as new files in the output folder.
- Format schedules, comparisons, and unit counts as tables.

## Workflow
- For documents longer than 2 pages, propose an outline and wait for my review before writing.
```

---

## 2. What Cowork Can Do Beyond Coding

Cowork works on your files, in a browser, and across your connected apps:

* **Document and Transcript Analysis**: Reads files in your selected folder to extract themes, find inconsistencies, or audit requirements.
* **Spreadsheets and Data**: Creates Excel files with working formulas, conditional formatting, and multiple tabs, and summarizes data files.
* **Presentations and Reports**: Builds slide decks from rough notes or meeting transcripts, and drafts reports and summaries.
* **Web Research**: Combines web searches, articles, papers, and your own notes into a report with sources.
* **Browser Actions**: Opens sites, reads pages, clicks, types, and fills in forms, using the browser built into the Claude desktop app.
* **Connected Apps**: Uses connectors (add them from the **+** menu in the chat box or under **Customize > Connectors**) to work across the apps you already use.
* **Scheduled Tasks**: Runs a task on demand or automatically on a schedule (see Section 5).

---

## 3. Supplying Context: Folders and Files

Cowork does not use `@` mentions. Instead, you give it context in two ways:

* **Select a folder** on the desktop app. Claude can read from and write to that folder without you uploading or downloading anything. Put the files for one job in one folder.
* **Refer to files by name** in your message. Claude will find them in the folder.

Examples:

* **transcript.txt**: *"Extract the main action items and unresolved questions."*
* **policy.pdf**: *"Audit our draft proposal in draft.md against Section 4 of this policy."*
* **survey_results.csv**: *"Summarize the top 3 complaints from participants."*
* **The whole folder**: *"Review all documents in this folder and create an index table."*

Cowork will ask your permission before permanently deleting any file.

---

## 4. The 3-Part Prompt Formula for Knowledge Work

**Deliverable + Source Context + Format / Constraints**

### Example Prompts

* **Meeting / Interview Synthesis**:
  > *"Read sample-transcript.txt. Extract action items, key decisions, and any unresolved questions into a table with columns: 'Topic', 'Decision/Action', 'Owner', and 'Next Steps'."*

* **Grant / Proposal Writing**:
  > *"Using notes.txt and grant_criteria.pdf, draft the 'Project Methodology' section. Write in an authoritative academic tone, limit it to 800 words, and structure it with bolded subheadings."*

* **Curriculum / Project Planning**:
  > *"Review degree_requirements.pdf and my_credits.txt. Build a 4-semester graduation roadmap, ensuring all general education and major requirements are satisfied. Propose an outline first before writing the full document."*

---

## 5. Essential Controls and Features for Knowledge Work

| Feature | How to Use It for Non-Coding Work |
| :--- | :--- |
| **/schedule** | Type it in chat to set up a recurring task *(for example, "Check this website every Monday morning and summarize what changed")*. You can also click **Scheduled** in the left sidebar, then create a new task with Claude or set it up manually. Schedules can be hourly, daily, weekly, weekdays, or manual. |
| **Approval mode** | The mode selector in the chat box controls when Claude asks first. **Manual**: you approve each action. **Auto**: Claude works without pausing and reviews each action for safety. **Skip**: no pausing and no automatic checks. Use Manual while you are learning. |
| **Projects** | Keep a task's files, instructions, scheduled tasks, and memory together. Start one from **Projects** in the left sidebar. |
| **Connectors** | Let Claude read from and act in your other apps. Add them under **Customize > Connectors**. |
| **Plugins and Skills** | Bundles of instructions and tools that teach Claude a repeatable workflow, such as an advising checklist. |
| **Interview me (a prompt, not a command)** | Ask: *"Before you write anything, interview me with questions to flesh out this outline."* |

---

## 6. Pro Tips for Daily Use

1. **Ask for Outlines First**: For long essays, articles, or reports, ask Claude: *"Give me an outline first, and wait for my feedback before writing the full draft."*
2. **Review Before You Approve**: Stay in Manual mode until you trust a workflow, and do not use Skip mode with files you cannot replace.
3. **Keep Raw Files Untouched**: Instruct Claude: *"Do not edit my original files; save all edits as draft_v2.md or in an outputs folder."*
4. **Group Related Work into One Task**: A single well-described task uses less of your usage limit than many small ones.
5. **Keep the App Open**: Tasks that use your files or the browser need the Claude desktop app open and connected.
6. **Check the Result**: Read what Claude produced against your source files before you use it. You are accountable for the final work.
