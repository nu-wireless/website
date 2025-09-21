# Contributing to NU Wireless Club Website

Thanks for helping improve the NU Wireless Club website!
This document is meant to serve as a resource for the e-board, ensuring the site can live across different years of leadership and remain easy to maintain. The goal is to make conventions and quirks clear so that anyone can pick up and edit the repo at any time.

---

## Local Development

- Preview changes locally with:
```bash
  npx @11ty/eleventy --serve
  ```

* Open [http://localhost:8080](http://localhost:8080) in your browser.

---

## Commit Messages

* Use [Conventional Commits](https://www.conventionalcommits.org/):

  * `fix:` for bug fixes or formatting issues
  * `feat:` for new content/features
  * `docs:` for documentation updates
  * `chore:` for minor changes, housekeeping
  * See the link above for additional types and scopes.
* Example:

  ```
  fix: correct workshop time in Fall 2025 schedule
  ```

---

## Markdown + HTML Quirk (Important)

Some pages (e.g. `workshop.md`) place Markdown tables inside HTML `<details>` wrappers to create accordion sections, a feature not supported in plain Markdown.  

When combining Markdown tables with HTML in this way, the tables must stay **flush-left** (no extra indentation). If the file is treated as HTML (e.g. in VS Code with auto-format on save), the tables may be indented by 4 spaces. That indentation causes them to render as code blocks instead of tables, breaking the layout.

To avoid this issue:  
* Keep tables aligned flush-left. A little spacing is okay, but never let them be indented by 4 spaces.  
* Avoid auto-formatting these sections as HTML. The result may look cleaner in your editor, but it will usually break the tables. However, if you still choose to format as HTML, carefully de-indent the tables afterward and confirm the page still renders correctly.  
* Refer to the inline comments in `workshop.md` as reminders.  

---

## General Conventions

* Prefer Markdown over HTML where possible (easier to maintain).
* Use HTML only for features not supported in Markdown (e.g. `<details>`, custom classes, buttons).