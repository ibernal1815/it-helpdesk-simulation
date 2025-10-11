# Phase 5 — User Experience & Integration

This final phase was about closing the feedback loop.  
The system was working fine, but I wanted to see how it *felt* to the people using it — and how well it connected with the rest of the tools around it.

---

## 💬 What I Added
- **Customer Satisfaction (CSAT) survey:**  
  Added a one-click rating link on ticket closure emails.
- **Feedback tracker:**  
  Logged survey responses into a simple spreadsheet.
- **Improved templates:**  
  Updated auto-reply wording based on survey comments (“less robotic, more direct”).
- **Slack test webhook:**  
  Sent new-ticket alerts to a dummy Slack channel — just enough to show integration potential.
- **Post-mortem notes:**  
  For any ticket rated below “Good,” I wrote a short reflection on what could’ve gone smoother.

---

## 📈 Results (Test Data)

| Metric | Before | After Feedback Loop |
|---------|--------|---------------------|
| Avg CSAT Score | 3.8 / 5 | 4.6 / 5 |
| Avg First Response Time | 9 min | 8 min |
| Tickets Reopened | 3 | 1 |

---

## 📸 Screenshots
Stored under `/assets/` for this phase:
1. `01_csat_email.png` — closure email with rating links  
2. `02_feedback_results.png` — sample CSAT response sheet  
3. `03_slack_integration.png` — new ticket notification in Slack  
4. `04_updated_template.png` — refined reply wording  

---

## 🧠 What Changed
Collecting even simple feedback changed how I thought about “done.”  
A resolved ticket isn’t really closed until the user confirms it solved their problem.

It also made me notice tone — the difference between a scripted message and a human one.  
Tiny tweaks to language built more trust than any automation rule.

---

## 🪴 Looking Ahead
If I keep building on this, I’d like to:
- Add a **Teams** integration for faster internal alerts  
- Store **CSAT results** in a lightweight database  
- Experiment with an **AI response suggestion** (just for fun)  
- Document this whole lab as a guided walkthrough for new IT students

---

**Reflection:**  
> “Automation made it efficient. Documentation made it consistent.  
> Feedback made it human. That’s the real finish line.”  
