# Computer Network Exam HTML Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build two print-friendly HTML files: a computer-network interview exam and a separate answer/explanation sheet.

**Architecture:** Static HTML files live under the Obsidian vault's `试卷` folder. The exam file contains only questions and answer space; the answer file contains answers, scoring points, and detailed explanations.

**Tech Stack:** Plain HTML and CSS, no JavaScript, no external dependencies.

---

### Task 1: Create Static Print Files

**Files:**
- Create: `obsidian_ubuntu/试卷/计算机网络校招面试试卷.html`
- Create: `obsidian_ubuntu/试卷/计算机网络校招面试答案解析.html`

- [x] **Step 1: Create the target folder**

Run: `mkdir -p obsidian_ubuntu/试卷`

Expected: folder exists.

- [x] **Step 2: Write exam HTML**

Create a print-oriented A4 document with 20 multiple-choice questions, 8 short-answer questions, and 2 interview scenario questions.

- [x] **Step 3: Write answer HTML**

Create a matching answer and explanation document with correct options, key points, detailed analysis, and interview follow-up guidance.

- [x] **Step 4: Verify files are present**

Run: `ls -l obsidian_ubuntu/试卷`

Expected: both HTML files are listed.

- [x] **Step 5: Open or inspect files**

Run: `sed -n '1,40p' obsidian_ubuntu/试卷/计算机网络校招面试试卷.html`

Expected: HTML title and print CSS appear.
