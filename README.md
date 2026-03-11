# Clean Seas HK — Lesson 8: Stakeholder Meeting & Final Presentation

An interactive web-based lesson platform for primary school students investigating marine pollution in Hong Kong. Built with pure HTML, CSS, and JavaScript — no installation required.

---

## Pages Overview

| Page | File | Purpose |
|------|------|---------|
| Homepage | `index.html` | Main lesson hub — AI tools, submit links, exit ticket |
| Presentation Guide | `Presentation_Guide.html` | Slide-by-slide guide for the final presentation |
| Final Checklist | `Final_Checklist.html` | Live progress checklist before presenting |
| Peer Assessment | `Peer_Assessment.html` | Form for students to rate and give feedback on other groups |
| Personal Reflection | `Personal_Reflection.html` | Individual reflection form including AI use statement |
| Results Dashboard | `Results.html` | Teacher dashboard — view all submitted forms with charts |

---

## How to Use This Website

### For Students

#### 1. Homepage (`index.html`)
- Read the **Learning Objectives** and **Assessment Criteria** at the top.
- Use the **AI Tools** to practise and improve your work (see AI Tools section below).
- Under **Submit (Final)**:
  - Paste your **Google Classroom link** and enter your group name, then click **Submit Link**.
  - Click **Open Form** for **Peer Assessment** and **Personal Reflection** to complete those forms.
- Complete the **Exit Ticket** at the bottom before you leave.
- Click the green **View Results** button (bottom-right corner) to see all submitted responses.

#### 2. Presentation Guide (`Presentation_Guide.html`)
- Follow the **6 slide structure**: Title → Problem → Evidence → Solution → Stakeholders → Sources.
- Check the **Timing Guide** — aim for 2–3 minutes total.
- Read the **Role-Play Guide** to prepare for the stakeholder Q&A.
- Use the **Tips for Good Answers** during the Q&A session.

#### 3. Final Checklist (`Final_Checklist.html`)
- Tick each item as your group completes it.
- The **progress bar** at the top updates live as you check items.
- Make sure all items are ticked before you present.

#### 4. Peer Assessment (`Peer_Assessment.html`)
- Enter your name, class, and the group you are assessing.
- Rate the group on **5 criteria** (1–4 scale): Science Understanding, Solution Quality, Stakeholder Perspectives, Sources, Communication.
- Write one thing you liked, one suggestion, and one question.
- Click **Submit Assessment** — a success message will appear.

#### 5. Personal Reflection (`Personal_Reflection.html`)
- Fill in all required fields (marked with *).
- If you used AI tools, tick **Yes** to reveal the AI use statement fields — describe how you verified AI information and what you changed.
- Select your **team role** and describe your collaboration experience.
- Write your **Action Commitment** — one real thing you will do to help reduce marine pollution.
- Click **Submit Reflection**.

---

### AI Tools (on Homepage)

All three AI tools use the **Groq API (Llama model)** — free, no VPN needed.

Click **Show Example** on any tool to see a sample input before you start.

#### AI Rehearsal Partner
- Select a **Stakeholder Role** (Fisherman, Tourism, NGO, Government, Local Community).
- Describe your group's solution in 1–2 sentences.
- Click **Generate Stakeholder Questions** to get 5 realistic questions that stakeholder would ask.
- Use these to practise your Q&A before the real presentation.

#### AI CER Checker
- Fill in your **Claim**, **Evidence**, and **Reasoning** separately.
- Click **Check My CER** — AI will tell you:
  - Whether your Evidence supports your Claim.
  - Whether your Reasoning connects them properly.
  - One thing you did well and one tip to improve.

#### AI Peer Feedback Helper
- Name the group you are giving feedback to.
- Write your **rough feedback** freely — don't worry about wording.
- Click **Improve My Feedback** — AI rewrites it into the KIND / HELPFUL / HONEST format:
  - One thing I really liked
  - One suggestion
  - One question I have
- Copy the improved feedback into the Peer Assessment form.

---

### For Teachers

#### Viewing Results (`Results.html`)
- Click the green **View Results** button on the homepage (bottom-right).
- Switch between **Peer Assessments** and **Personal Reflections** tabs.
- Use the **search bar** to filter by student name or group.
- Click **View** on any row to see the full response in a detail modal.
- Click **Export CSV** to download all responses as a spreadsheet.
- Charts show: average scores per criterion, score distribution, AI usage, student roles, and more.

> **Note:** All data is stored in the browser's `localStorage`. Data is saved on the same device/browser only. Clear browser data will erase submissions. For a permanent record, use **Export CSV** regularly.

---

## Deployment

This site is deployed via **GitHub Pages** using GitHub Actions.

- Live URL: `https://csc-cmass.github.io/csc-cmass/`
- Entry point: `index.html`
- To deploy: push to `main` branch — GitHub Actions will build and publish automatically.
- Make sure **GitHub Pages** is enabled in repository Settings → Pages → Source: **GitHub Actions**.

---

## Technology

- Pure **HTML / CSS / JavaScript** — no frameworks, no build step
- **localStorage** for client-side data storage (no backend required)
- **Groq API** (`llama-3.1-8b-instant`) for AI features
- **Chart.js** (CDN) for results dashboard charts
