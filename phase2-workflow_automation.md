# Phase 2 — Workflow Automation

After getting the basics down in Phase 1, this step was about working *smarter*.  
I focused on automating the small stuff — ticket routing, responses, and timing — to make the system feel like it could actually support a small team.

---

## ⚙️ What I Built
- **Routing rules:** tickets mentioning "VPN" or "Network" get tagged as *High* and assigned to the Network queue.  
- **Auto-replies:** set up a polite “We got your request” message for new tickets.  
- **SLA timers:** created response and resolution targets  
  - First response ≤ 30 minutes  
  - Resolution ≤ 1 day  
- **Escalation rule:** if a High-priority ticket goes 30 minutes without an agent reply, it pings a test mailbox (simulating an on-call alert).

---

## 🧠 Why It Matters
This phase made me think about *predictable response*.  
Automations aren’t about replacing humans — they just take the friction out of routine cases so agents can focus on weird ones.

It also showed me the importance of **clear triggers**.  
One bad condition in a rule can misroute half your queue.

---

## 🧩 Example Rules

| Rule Name | Condition | Action |
|------------|------------|---------|
| VPN High Priority | Subject contains “VPN” | Set Priority = High, Assign to Network Queue |
| Password Reset Auto-Reply | Category = Accounts | Send template reply: “Here’s how to reset your password” |
| SLA Escalation | Priority = High + No reply ≥ 30 min | Send email alert to On-Call |

---

## 📸 Screenshots
Screenshots stored under `/assets/` for this phase:
1. `01_automation_rules.png` — Full list of automation rules  
2. `02_auto_reply_template.png` — Preview of password reset message  
3. `03_sla_config.png` — SLA timer setup screen  
4. `04_escalation_alert.png` — Example escalation email  

(Private data blurred or replaced with test domains.)

---

## 📈 What Improved
- Manual triage dropped from every ticket to maybe one in five  
- Average response time (from test data) improved from **22 min → 9 min**  
- Fewer forgotten tickets thanks to SLA timers

---

## 🪴 Next Steps
Phase 3 will shift focus from workflow to **knowledge sharing**:  
- Building a small internal knowledge base  
- Linking articles to recurring issues  
- Creating reply templates that pull from KB content  

---

**Reflection:**  
> “This phase felt like cleaning a messy kitchen.  
> Once the automations clicked, I realized how much time gets lost in little hand-offs.”  
