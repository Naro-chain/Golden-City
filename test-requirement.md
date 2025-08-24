# 🛕 Token Estate – Developer & Designer Test Suite

This repository contains technical test descriptions for different roles at **GoldenCity**. Each candidate may select one or more test items that are appropriate for him and is required to complete their assigned task using this project.

---

---

## 🖥 Frontend Developer Test (60 mins)

**Task:**  
Update the landing page with:

-   ✅ New background image & updated animation
-   ✅ Dark/Light mode toggle in the navbar
-   ✅ Smooth transitions between modes

**Requirements:**

-   Must be fully responsive (desktop, tablet, mobile)

**Deliverables:**

-   🎥 Short video demo of the updated landing page and toggle feature

---

---

## ⚙️ Backend Developer Test (60 mins)

**Task:**  
Implement a basic **CRUD API** for a Notes feature.

**Endpoints:**

-   `POST /notes` – Create a new note
-   `GET /notes` – Retrieve all notes
-   `GET /notes/:id` – Retrieve a specific note
-   `PUT /notes/:id` – Update a note
-   `DELETE /notes/:id` – Delete a note

**Notes Storage:** Use in-memory array (no DB required)

**Deliverables:**

-   🎥 Short video demonstrating the API
-   Display output in console or simple frontend

---

---

## 🌐 Web3 Developer Test (60 mins)

**Task:**  
Integrate **MetaMask wallet** with the project

**Features:**

-   Prompt user to connect MetaMask
-   Display connected wallet address
-   Handle account & network changes

**Deliverables:**

-   🎥 Short video showing wallet connection & address display

---

---

## ⛓ Blockchain Developer Test (60 mins)

**Task:**  
Build a decentralized **Voting System** using Solidity + Node.js

### 🔐 Smart Contract: `Voting.sol`

-   `addCandidate(string name)` – Only owner
-   `vote(uint candidateIndex)` – One vote per user
-   `getCandidates()` – Returns all candidates & vote counts
-   `getWinner()` – Returns winner’s name

### 🌐 Backend (Node.js + Web3.js)

-   `POST /candidates` – Add candidate (owner only)
-   `GET /candidates` – List all candidates
-   `POST /vote` – Cast a vote
-   `GET /winner` – Get winner’s name

**Deliverables:**

-   `Voting.sol`, ABI, contract address
-   🎥 Video showing working API + integration

---

---

## 🎨 Designer Test (60 mins)

**Task:**  
Redesign the current landing page

**Requirements:**

-   New layout or style direction
-   Submit:
    -   Before/after comparison
    -   Screens of the redesign
    -   2–4 paragraph write-up explaining UX improvements

**Deliverables:**

-   🎥 Short video walk-through of the design
-   Clear explanation of design decisions

---

---

## 🧪 QA Engineer Test (50–60 mins)

**Task:**

-   Set up the project locally
-   Manually test key features (e.g. wallet, UI, forms)

**Requirements:**

1. Identify at least 5 critical issues
2. Log each bug with:
    - Steps to reproduce
    - Expected vs. actual result
    - Severity level
3. Create 5 detailed test cases with:
    - Test Case ID, Scenario, Steps, Expected/Actual Result, Status
4. (Optional) Write a basic automation script (e.g. Selenium, Postman)

**Deliverables:**

-   🐛 Bug Report (Google Docs or Notion)
-   ✅ Test cases (Excel or Google Sheets)
-   🤖 Optional automation script (GitHub or ZIP)
-   🎥 3–5 min video explaining key findings

---

---

## ⏱ Submission Note

All candidates must complete the assessment within **24 hours** and submit their deliverables including the **video demonstration**.

---
