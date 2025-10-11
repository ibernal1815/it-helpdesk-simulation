# Phase 4 — Analytics & Reporting

By this stage, the help desk was running smoothly enough to start asking better questions:
- How fast are we responding?
- What issues keep coming back?
- Where are we spending the most time?

This phase was about turning day-to-day activity into numbers I could actually learn from.

---

## 📊 What I Tracked
- **Tickets by category:** Hardware, Network, Accounts, Software  
- **Average first response time**  
- **Average resolution time**  
- **Open vs. closed ticket ratio**  
- **SLA compliance rate**

I exported data from Spiceworks (CSV) and used Google Sheets to chart trends.  
Later I pulled the same CSV into Python just to practice basic visualization with `matplotlib`.

---

## 🧩 Example Metrics

| Metric | Before Automation | After Automation | Change |
|--------|------------------|-----------------|---------|
| Avg First Response Time | 22 min | 9 min | ↓ 59 % |
| Avg Resolution Time | 7 h 40 m | 4 h 15 m | ↓ 44 % |
| SLA Met % | 82 % | 95 % | +13 pts |
| Tickets / Week | 20 | 24 | +4 (new visibility) |

---

## 📈 Visuals
Screenshots in `/assets/` for this phase:
1. `01_dashboard_overview.png` — built-in Spiceworks dashboard  
2. `02_csv_export.png` — ticket export preview  
3. `03_metrics_chart.png` — chart made from test data  
4. `04_trends_over_time.png` — open vs. resolved tickets over a week

---

## 🔍 What I Learned
Reporting forces you to look beyond “Was the ticket fixed?”  
Patterns start showing up — like 70 % of delays coming from one category or certain times of day.

It also helped me explain improvements in a clear way.  
Instead of “I made things faster,” I had graphs and numbers to back it up.

---

## 🪴 Next Steps
Phase 5 will be about **user experience and feedback loops**:
- Add short satisfaction surveys at closure  
- Use responses to tweak templates  
- Explore simple integrations (Slack notifications, CSAT logging)

---

**Reflection:**  
> “Metrics don’t fix problems, but they make them impossible to ignore.  
> Once you start measuring, improvement stops being optional.”  
