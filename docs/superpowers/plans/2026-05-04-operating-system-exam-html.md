# Operating System Exam HTML Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build two print-friendly HTML files for an operating-system interview exam and its answer/explanation sheet.

**Architecture:** Static HTML files live under the Obsidian vault's `试卷` folder. The exam file contains questions and answer areas; the answer file contains correct options, scoring points, explanations, and interview pitfalls.

**Tech Stack:** Plain HTML and CSS, no JavaScript, no external dependencies.

---

### Task 1: Create Static Print Files

**Files:**
- Create: `obsidian_ubuntu/试卷/操作系统校招面试试卷.html`
- Create: `obsidian_ubuntu/试卷/操作系统校招面试答案解析.html`

- [x] **Step 1: Create target folder**

Run: `mkdir -p obsidian_ubuntu/试卷`

Expected: folder exists.

- [x] **Step 2: Write exam HTML**

Create a print-oriented A4 document with 25 single-choice questions and 10 short-answer questions. Difficulty is higher than basic school recruitment material, with expanded operating-system topics beyond the existing notes.

- [x] **Step 3: Write answer HTML**

Create a matching answer and explanation document with correct options, scoring points, detailed analysis, and common interview pitfalls.

- [x] **Step 4: Verify files and counts**

Run `ls`, count choice answer blanks, count short-answer writing areas, and inspect answer entries.
