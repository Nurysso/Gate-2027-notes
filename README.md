<!-- This file was written for github and not for Obsidian -->

<div align="center">

# 📚 GATE 2027 Study Notes

**Data Science & Artificial Intelligence (DA)** · with extra notes on programming and CS

Written in [Obsidian](https://obsidian.md), shared publicly, and updated as I learn.

[Goal](#goal) · [Syllabus Map](#syllabus-map) · [Daily Updates](#daily-updates) · [Programming and CS Notes](#programming-and-cs-notes) · [Use in Obsidian](#using-these-notes) · [Plugins](#obsidian-plugins) · [Contribute](#contributing) [![CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

</div>

---

> [!NOTE]
> This repo is **mainly for the GATE DA paper**. I may also add notes for the **GATE CS paper** along the way. Anything outside the syllabus (programming deep-dives, side topics) lives in `99 Extras` and is there for fun and extra knowledge, **not** as exam material.

> [!WARNING]
> These are my own study notes, so they may contain mistakes. Always cross-check with textbooks, lectures, and the official syllabus. If you spot an error, please open an issue or a PR.

---

## Table of contents

1. [Goal](#goal)
2. [Syllabus map](#syllabus-map)
3. [Daily updates](#daily-updates)
4. [Programming and CS notes](#programming-and-cs-notes)
5. [Repository structure](#repository-structure)
6. [What is inside a topic note](#what-is-inside-a-topic-note)
7. [Using these notes](#using-these-notes)
8. [Obsidian plugins](#obsidian-plugins)
9. [Optional: progress dashboard](#optional-progress-dashboard)
10. [GitHub rendering notes](#github-rendering-notes)
11. [Credits and copyright](#credits-and-copyright)
12. [Contributing](#contributing)
13. [License](#license)

---

## Goal

|                         |                                   |
| ----------------------- | --------------------------------- |
| **Exam**                | GATE 2027, Data Science & AI (DA) |
| **Expected date**       | 14 Feb 2027                       |
| **Portion complete by** | 31 Dec 2026                       |
| **Revision phase**      | 1 Jan → 13 Feb                    |

The master checklist of every syllabus topic is in [GATE-DA-2027.md](./GATE%202027.md).

[⬆ Back to top](#-gate-2027-study-notes)

---

## Syllabus map

Click a subject to jump to its notes. Status is updated as I finish each section.

### GATE DA

| #   | Subject                                     | Notes                                                                       | Status         |
| --- | ------------------------------------------- | --------------------------------------------------------------------------- | -------------- |
| 01  | Probability and Statistics                  | [Open folder](./01%20Probability%20and%20Statistics)                        | ⬜ Not started |
| 02  | Linear Algebra                              | [Open folder](./02%20Linear%20Algebra)                                      | ⬜ Not started |
| 03  | Calculus and Optimization                   | [Open folder](./03%20Calculus%20and%20Optimization)                         | ⬜ Not started |
| 04  | Programming, Data Structures and Algorithms | [Open folder](./04%20Programming%2C%20Data%20Structures%20and%20Algorithms) | ⬜ Not started |
| 05  | Database Management and Warehousing         | [Open folder](./05%20Database%20Management%20and%20Warehousing)             | ⬜ Not started |
| 06  | Machine Learning                            | [Open folder](./06%20Machine%20Learning)                                    | ⬜ Not started |
| 07  | Artificial Intelligence                     | [Open folder](./07%20AI)                                                    | ⬜ Not started |

### General Aptitude

| #   | Section               | Notes                                                  | Status         |
| --- | --------------------- | ------------------------------------------------------ | -------------- |
| 08  | Verbal Aptitude       | [Open folder](./08%20GA%20-%20Verbal%20Aptitude)       | ⬜ Not started |
| 09  | Quantitative Aptitude | [Open folder](./09%20GA%20-%20Quantitative%20Aptitude) | ⬜ Not started |
| 10  | Analytical Aptitude   | [Open folder](./10%20GA%20-%20Analytical%20Aptitude)   | ⬜ Not started |
| 11  | Spatial Aptitude      | [Open folder](./11%20GA%20-%20Spatial%20Aptitude)      | ⬜ Not started |

### Beyond the DA syllabus

| #   | Section                      | Notes                            | Status     |
| --- | ---------------------------- | -------------------------------- | ---------- |
| 12  | GATE CS paper (maybe)        | [Open folder](./12%20CS%20Paper) | 🔜 Planned |
| 99  | Extras: programming and more | [Open folder](./99%20Extras)     | 🔜 Ongoing |

_Legend: ⬜ Not started · 🟨 In progress · ✅ Done · 🔁 Revising · 🔜 Planned_

[⬆ Back to top](#-gate-2027-study-notes)

---

## Daily updates

I'm aiming to **push updates daily (or close to it)**, based on whatever I'm studying that day. Expect notes to appear in the order I learn things, not in syllabus order, and expect earlier notes to be tidied up as I revise.

**Watch** or **star** the repo to follow along. Commit messages follow this pattern so the history stays readable:

```
notes(<subject>): <topic>      e.g. notes(prob): add Bayes theorem
fix(<subject>): <what>         e.g. fix(la): correct rank-nullity example
extras(<area>): <topic>        e.g. extras(python): add decorators
```

### Recent updates

| Date          | What was added        |
| ------------- | --------------------- |
| _coming soon_ | First notes land here |

[⬆ Back to top](#-gate-2027-study-notes)

---

## Programming and CS notes

Programming is my main area, so beyond the syllabus you'll find extra notes in [`99 Extras`](./99%20Extras). These are written for curiosity and depth, not for the exam. Planned areas include:

- **Python:** internals, idioms, and tricks beyond what GATE asks
- **Data structures and algorithms:** deeper implementations and write-ups
- **Systems and tooling:** Git, the command line, and development workflows
- **Databases and SQL:** practical queries and design notes
- **GATE CS topics:** operating systems, computer networks, computer organization, theory of computation, and compilers, _if_ I get to the CS paper

Code snippets in these notes are written to be run and tinkered with. Nothing here is a promise or a fixed schedule; the list grows as I learn.

[⬆ Back to top](#-gate-2027-study-notes)

---

## Repository structure

```
.
├── 01 Probability and Statistics/
├── 02 Linear Algebra/
├── 03 Calculus and Optimization/
├── 04 Programming, Data Structures and Algorithms/
├── 05 Database Management and Warehousing/
├── 06 Machine Learning/
├── 07 AI/
├── 08 GA - Verbal Aptitude/
├── 09 GA - Quantitative Aptitude/
├── 10 GA - Analytical Aptitude/
├── 11 GA - Spatial Aptitude/
├── 12 CS Paper/                    ← optional, GATE CS topics
├── 99 Extras/                      ← programming and non-syllabus topics
├── _attachments/                   ← images used in notes
├── _templates/                     ← note templates
├── GATE-DA-2027-Tracker.md         ← master syllabus checklist
└── README.md
```

Each subject folder contains **one note per topic**, numbered in syllabus order, for example `01 Probability and Statistics/17 Binomial distribution.md`.

[⬆ Back to top](#-gate-2027-study-notes)

---

## What is inside a topic note

Every note follows the same template, so they're quick to scan:

- **Summary** in my own words
- **Video resources**, with links to the lectures I used
- **Key concepts and formulas**, written in LaTeX
- **Diagrams and images**
- **Worked examples** and **previous year questions (PYQs)**
- **Common mistakes**, **doubts**, and a **revision log**

[⬆ Back to top](#-gate-2027-study-notes)

---

## Using these notes

### Reading on GitHub

Browse the folders from the [syllabus map](#syllabus-map) and open any `.md` file. Most of it renders fine, including math and tables. A few Obsidian-only features won't show up (see [GitHub rendering notes](#github-rendering-notes)).

### Using them in Obsidian (recommended)

1. Install [Obsidian](https://obsidian.md).
2. Clone the repo:

   ```bash
   git clone https://github.com/nurysso/Gate-2027-notes.git
   ```

3. In Obsidian, choose **Open folder as vault** and select the cloned folder.
4. If prompted about community plugins, enable them only if you've reviewed them. Otherwise skip and install manually (see [plugins](#obsidian-plugins)).

[⬆ Back to top](#-gate-2027-study-notes)

---

## Obsidian plugins

The notes are plain Markdown, so everything reads fine without community plugins. You only lose the auto-generated dashboards.

### Built-in (just switch on)

| Plugin                                  | Why                                                                      |
| --------------------------------------- | ------------------------------------------------------------------------ |
| **Templates** (Settings → Core plugins) | Insert the topic-note template. Set the template folder to `_templates`. |
| **Properties, Backlinks, Graph view**   | Metadata and navigation between topics.                                  |

### Community plugins

| Plugin                                                                    | Required?              | Used for                                                            |
| ------------------------------------------------------------------------- | ---------------------- | ------------------------------------------------------------------- |
| [Dataview](https://github.com/blacksmithgu/obsidian-dataview)             | Optional (recommended) | Auto-generated progress tables from each note's `status` field.     |
| [Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks)           | Optional               | Counting and querying checkboxes across notes.                      |
| [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)     | Optional               | Hand-drawn diagrams (export as PNG or SVG so GitHub can show them). |
| [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian) | Optional               | Easier Markdown table editing.                                      |

### Recommended settings

Open **Settings → Files and links** and set:

- **Use [[Wikilinks]]** → **Off** (standard Markdown links render on GitHub)
- **New link format** → **Relative path to file**
- **Default location for new attachments** → _In the folder specified below_ → `_attachments`

[⬆ Back to top](#-gate-2027-study-notes)

---

## Optional: progress dashboard

Requires the **Dataview** plugin. Create a note called `Dashboard.md` and paste:

````markdown
## Status by subject

```dataview
TABLE WITHOUT ID
  subject AS "Subject",
  length(filter(rows, (r) => r.status = "done")) AS "Done",
  length(rows) AS "Total"
FROM #gate-da
WHERE topic
GROUP BY subject
```

## Topics still to start

```dataview
LIST
FROM #gate-da
WHERE status = "not-started"
SORT file.folder ASC
```
````

`status` can be: `not-started` · `in-progress` · `done` · `revising`.

[⬆ Back to top](#-gate-2027-study-notes)

---

## GitHub rendering notes

| Feature                     | On GitHub                                             |
| --------------------------- | ----------------------------------------------------- |
| Math (`$...$`, `$$...$$`)   | ✅ Renders                                            |
| Tables, task lists, Mermaid | ✅ Renders                                            |
| Frontmatter                 | ✅ Shown as a small table                             |
| Dataview queries            | ❌ Shown as code blocks (Obsidian only)               |
| `[[Wikilinks]]`             | ❌ Not clickable (relative links are used instead)    |
| Callouts like `[!tip]`      | ⚠️ Only NOTE, TIP, IMPORTANT, WARNING, CAUTION render |

[⬆ Back to top](#-gate-2027-study-notes)

---

## Credits and copyright

- Video links point to the original creators. All credit goes to them; I don't re-host any videos.
- Images are either drawn by me or credited in the note. If something here is yours and you'd like it removed or credited, open an issue and I'll fix it right away.
- Notes are summarised in my own words from lectures, textbooks, and official GATE material.

---

## Contributing

Corrections, better explanations, and extra PYQ solutions are welcome:

1. Fork the repo
2. Create a branch (for example `fix/bayes-theorem-typo`)
3. Open a pull request

---

## License

Notes are shared under **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)**. Share and adapt with credit, non-commercially, under the same license.

---

<div align="center">

⭐ If these notes helped you, a star on the repo is appreciated. All the best for GATE! 🚀

[⬆ Back to top](#-gate-2027-study-notes)

</div>
