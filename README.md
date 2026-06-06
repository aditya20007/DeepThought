DeepThought AI

Business Analyst — Process Management Assignment
Submitted by: Aditya Singh | IIT Patna | singhadityakumar566@gmail.com



Executive Summary
After reading through the scenario a couple of times, my main takeaway is this: PharmaTech has done a great job setting up a reporting infrastructure, but they haven't built an execution culture to match it. The tools are there, the tracker is running, and the morning emails go out like clockwork. But nothing is actually moving.
The reason for this isn't a tech problem; it's a people problem. At its core, the organization hasn't figured out how to separate "highlighting a problem" from "punishing the person tied to that problem." Until they fix that, every new tool they introduce is going to underperform. It won't be because the tool is bad, but because the people using it are smartly trying to protect themselves.
All three situations in this scenario are just different symptoms of the same underlying issue. In my diagnosis below, I've tried to call out this issue clearly, and my proposed fixes focus on treating the root cause—starting with the people, not just adding more dashboards.
PART A — DIAGNOSIS
Situation A — The Alert Nobody Responds To
The Stated Problem: The CEO gets an automated email every day showing red and amber items across different departments. Those items stay red for days, but nobody escalates them or responds. Anil and Karthik think the system is working fine, but the CEO feels like he's still in the dark.
What Is Actually Going On: The alert system isn't really broken; it's just doing the wrong job.
It was built to give the CEO visibility, and it does that—he can see who is in the red. But having visibility without a clear plan of action is just standing around watching. It’s like installing a fire alarm in a building but never teaching anyone what to do when it goes off. The alarm works perfectly, but the evacuation is a disaster.
There are three main structural cracks here:
•	Accountability is tied to departments, not real people. The email says "Warehouse: RED," not "Rajesh Kumar: 3 tasks overdue." The advisor nailed this when he pointed out that nobody feels the pressure when a whole department is flagged. If a specific person's name is on it, they’ll show up prepared. When you anonymize accountability, people naturally diffuse the responsibility.
•	The alerts have no memory and show no urgency. An email on Day 1 showing "3 days overdue" looks exactly the same as an email on Day 6 showing "8 days overdue." Without trend signals or escalation history, everything feels equally urgent, which means nothing actually feels urgent. It’s like living next to a highway—eventually, you just tune out the noise.
•	Nobody defined what "taking action" actually looks like. When someone sees a red item, what are they supposed to do? Who handles it? Is there a 24-hour window to fix it? Anil and Karthik built the pipeline, but they never designed the rules for what should happen when the pipeline sends an alert.
Because of this, Anil spends his whole week manually chasing people down. He has essentially become a human band-aid for a broken escalation system. If Anil leaves, the whole thing stops.
Situation B — The Blank Root Cause Field
The Stated Problem: About 70% of the root cause fields in the deviation tracker are left blank or filled with vague filler like "under investigation." Anil and Karthik think the team just lacks discipline.
What Is Actually Going On: This is the most critical diagnostic moment in the whole scenario, and Anil and Karthik completely missed it. They were asking, "Why aren't people filling this out?" when they should have been asking, "What happens to someone when they actually tell the truth?"
Two supervisors gave us the real answer: if they write down what actually went wrong, they get interrogated in front of 12 people—including the CEO—in the morning meeting. It turns into a massive blame game.
This isn't a discipline issue at all. These are experienced professionals who have learned that being honest in this company leads to public embarrassment. So, they do the smart thing: they write nothing, keep their heads down, and fix the problem quietly.
The company accidentally created a culture that punishes transparency and rewards staying quiet. The 70% blank rate just proves that the team has a healthy instinct for self-preservation. You can't fix this with more training; you have to change what happens after someone reports an issue honestly.
Situation C — The Meeting That Eats the Day
The Stated Problem: The daily 30-minute status meeting routinely drags on for 60 to 90 minutes. Afterward, everyone’s day is totally derailed by random, unplanned work that got dumped on them during the call.
What Is Actually Going On: This is a mix of poor planning, bad meeting design, and hidden organizational issues all crashing into each other.
•	The root cause is a lack of planning. The department heads don't have daily micro-plans, and neither do Anil or Karthik. If you don't have a plan for the day, everything feels like an emergency. The meeting isn't creating the chaos; it's just exposing the chaos that's already there.
•	The meeting design is mathematically impossible. You can't fit 12 people giving updates into 30 minutes. It was doomed to run over from the start. On top of that, deep technical issues (like machine breakdowns) get discussed in front of everyone, dragging the whole room into a problem that only affects two people.
•	It's the only place the CEO gets real news. Because the automated emails aren't helpful, this meeting is likely the only time the CEO and COO actually find out what's happening on the floor. People subconsciously let the meeting drag on because it's serving a purpose the broken system isn't.
•	It creates ripple effects. When an issue gets announced to 12 people at once, everyone shifts their day around to react to it. A structured triage system would contain that noise to just the 2 or 3 people who actually need to fix it.
The Systemic Connection
These aren't three separate problems; they are the exact same problem wearing different hats.
The company has fused "making problems visible" with "blaming someone for the problem." Because of this fear, supervisors hide data (Situation B). Because data is hidden, the CEO has no visibility, so nobody acts on the tracker (Situation A). Because there’s no visibility, leadership relies heavily on the daily meeting to figure out the truth (Situation C). That high-pressure meeting generates more fear, which leads to more hidden data.
It's a toxic loop. You can't break it by adding software. You break it by changing how leadership reacts to the truth.
PART B — INTERVENTION DESIGN
Situation A — Making the Alert Drive Action
The First Conversation: I'd pull the COO aside informally—maybe in the hallway or over coffee—and ask one question: "When you see a red item in the morning email, what do you expect to happen next?" I genuinely want to know the answer. If he says Anil handles it, I know we have a bottleneck. If he admits he isn't sure, I've found my opening.
First Two Weeks (No Tech, Just Humans):
•	Week 1: I sit in the daily meeting and just observe. Who speaks up? Who hides? Do people volunteer, or do they wait for Anil to assign tasks? I also chat one-on-one with the department heads who have the most red items, strictly to understand their workflow blockers, not to scold them.
•	Week 2: I introduce one tiny change to the meeting. After a red item is discussed, someone has to ask, "Who owns this, and what's the next step before tomorrow?" That verbal, public commitment gets logged. I also agree on a simple rule with the COO: if an item is red for 3 days, it triggers a direct chat between the COO and the department head.
The Tool:
•	The WhatsApp Prompt: Every morning at 8:15 AM, department heads get a friendly, automated WhatsApp message with their name, listing their overdue items, and asking if they need help unblocking anything before the 9 AM meeting. It feels supportive, not like policing.
•	The Upgraded Email: The CEO's email gets revamped to show individual names, how many days an item has been red, a trend line (is it getting worse?), and the very next committed action.
•	The Tech Stack: I stick to Excel, Power Automate, and WhatsApp. No new software. It’s exactly what they already use, just connected smarter.
Getting the Veteran on Board: I sit down with a 15-year veteran and ask them to walk me through their exact process for a task. When they explain how many steps rely on other people, I frame the new system as a way to protect them: "Right now, the tracker makes you look slow. Let's make those dependencies visible so when Finance is holding you up, Finance looks like the blocker, not you."
Situation B — Making Root Cause Safe to Fill
The First Conversation: I find a mid-level supervisor, ask about a recent deviation, and just listen. Afterward, I ask if any of that real story made it into the official log. When they say no, I ask, "What would happen to you if you did write it down?" That’s the real root of the issue.
First Two Weeks (No Tech, Just Humans):
•	Week 1: I pitch the COO on moving deviation discussions out of the big daily meeting. We set up a separate, smaller 30-minute weekly technical review. No CEO present for the first month. The vibe is strictly problem-solving, not finger-pointing.
•	Week 2: In that new meeting, I model the right behavior. If someone gives a vague answer, I ask curious questions to dig deeper without interrogating them. I also enforce a hard rule: root cause discussions from this smaller room cannot be weaponized in the big daily meeting.
The Tool:
•	The Google Form: A super simple, mobile-friendly Google Form that asks "What did you observe?" instead of the intimidating "What is the root cause?" It includes an "Unknown" option so people don't feel forced to make something up.
•	The Workflow: Supervisors fill it out quickly on their phones. Every Friday, Anil runs the data through a quick AI prompt (like Claude) to spot recurring patterns. Those patterns form the agenda for the weekly technical meeting.
•	The Tech Stack: Google Forms, Google Sheets, and a 30-second weekly AI prompt.
Getting the Veteran on Board: I tell the veteran supervisor: "You've been fixing things quietly for years, but when you retire, all that knowledge leaves with you. I don't want you writing reports for management; I want you leaving notes for the next shift." It frames the tool as building institutional memory, which veterans deeply respect.
Situation C — Fixing the Meeting and Building Daily Planning
The First Conversation: A quick, 3-minute chat with the CEO. I explain that the meeting is trying to do three different jobs at once and failing. I ask for permission to come back with a structural redesign.
First Two Weeks (No Tech, Just Humans):
•	Week 1: Anil starts doing triage 30 minutes before the meeting. He categorizes tracker items into "quick status update" or "needs a longer discussion." The daily meeting is now strictly restricted to the quick updates.
•	Week 2: I introduce a 5-minute daily micro-planning habit for Anil and Karthik to map out their top 3 tasks and expected roadblocks. For the department heads, the COO simply asks them to come to the meeting with exactly one sentence prepared for each of their overdue items.
The Tool:
•	The Prep Message: The same 8:00 AM WhatsApp message asks department heads to prepare their one-liners.
•	Live MOM: A shared Google Doc for meeting minutes is updated live during the call, tracking the owner, the status, and the next deadline.
•	Unplanned Work Log: Department heads drop one line a week into a tracker about unexpected fires they had to put out. Anil aggregates this to help the COO spot trends (e.g., "Unit 2 broke down 4 times this week, we need maintenance").
Getting the Veteran on Board: I pitch it purely as a time-saver: "You're spending 90 minutes in a room where half the stuff doesn't apply to you. Let's get your part done in 5 minutes so you can have your morning back." Veterans love getting their time back.

# PART C — SCALE THINKING

## What Breaks First at 8 CDMO Projects

**The single most dangerous failure point: the entire operational system currently runs on two people's personal effort, and this is invisible.**

Anil and Karthik are the de facto execution layer of this organization. Anil follows up with 12 departments personally. Karthik fixed the printer because it would otherwise stay broken. They attend every meeting, chase every commitment, and act as the human substitute for every escalation protocol that was never built.

At 2 projects, this works — barely. At 8 projects, with 3-4 new analysts hired, the organization will attempt to scale by adding more people doing the same thing. Each analyst becomes the personal glue for their project cluster. But now you have 4-6 people operating in parallel with no shared standard for how accountability is tracked, how deviations are routed, how escalations are triggered. The CEO goes from one morning email to four. Each analyst uses a slightly different version of the tracker. Root cause data is captured differently across projects. The unified tracker fragments.

More importantly: the new analysts will not have Anil and Karthik's relationship equity with the HODs. A 15-year veteran who grudgingly cooperates with Anil because they've been working together for months will have zero patience for a fresh analyst from IIT walking in and telling them to fill a form. Without a self-sustaining system — one that works because of its design, not because of the analyst's personal persistence — new analysts will spend their first three months rebuilding the same relationship groundwork from scratch, every time.

The failure is not visible right now because Anil and Karthik are compensating so effectively. The moment you add complexity (8 projects) and dilute their personal coverage (3-4 more analysts), the absence of real systems becomes exposed simultaneously across the entire organization.

This is the one that breaks first because it is the most invisible risk today.

## The System to Build Now, at 2 Projects, That Holds at 8

**An Execution Standard Operating Procedure (SOP) — not for the HODs, for the analysts.**

In the first 3 months, I document: exactly what happens at each step of the accountability workflow. What is the tracker format? What are the field definitions? What is the escalation trigger rule? What is the MOM template? What is the deviation form? What does a "healthy" week look like versus a "at-risk" week?

This SOP is not a bureaucratic document. It is a 4-page Google Doc that a new analyst joining in Month 7 can read in 30 minutes and understand exactly what they're supposed to do, why each piece exists, and what failure looks like. It is written with specific examples from actual events at PharmaTech — real tracker entries, real MOM formats, real deviation categories.

At 2 projects, building this SOP takes me roughly 2 hours per week as a documentation habit. At 8 projects, it means the fourth analyst who joins doesn't spend 3 months reinventing the accountability system. They read the SOP, shadow Anil for one week, and start with a working foundation.

Alongside this, I build the daily self-report ritual at the HOD level — not just for project tracking but as a standard of how this organization communicates. Every HOD, every morning, answers three questions in under 3 minutes:

1. What is my one most critical open item right now?
2. What do I need from another department to move it forward?
3. Is anything today going to slip from its committed deadline?

At 2 projects, this builds the habit. At 8 projects, new analysts inherit HODs who already know the ritual — they don't need to teach it.

## What to Automate, What to Keep Human, and Why

This is a judgment question, so I'll give a direct answer with reasoning:

**Automate:**
- Morning HOD prompts (WhatsApp via Power Automate) — low-stakes, high-frequency, humans should not spend time on this
- CEO/COO alert emails — already automated, extend the pipeline
- Escalation flags (item RED 3+ days, no update → COO WhatsApp) — rule-based, no judgment required
- Weekly deviation pattern summary (Claude prompt on Google Sheet data) — data synthesis, not interpretation; Claude does this in 30 seconds

**Keep Human:**
- Root cause conversations — trust is the substrate; a form cannot replace a curious human asking "what actually happened?"
- Cross-department dependency resolution — when Warehouse is waiting on Purchase and neither moves, the analyst needs to understand the relationship dynamic, not just the task status
- First-time tool onboarding for any HOD — a veteran's first interaction with a new system requires a human sitting next to them, not a tutorial video
- Interpreting anomalies in the data — when the tracker shows Unit 2 has been amber for 10 days, an alert can flag it but a human needs to ask "is this a machine issue, a scheduling issue, or a conflict between two HODs that nobody wants to name in public?"
- The weekly technical deviation review — this meeting is where psychological safety is either built or destroyed; it must be facilitated by a human who can read the room

**The line I draw:** Automate the flow of information. Keep human the interpretation of information and the management of relationships. A manufacturing floor is a high-context environment where a "red item" can mean 50 different things depending on who's involved, what's happened before, and what the political dynamics are between departments. Automation that bypasses human judgment in this environment produces faster wrong answers, not better decisions.

The wrong answer is to automate everything and hope the HODs figure it out. The other wrong answer is to keep everything manual and hope Anil can scale to 8 projects. The right answer is: build automation for the routine, preserve human presence for the complex.

---

# PART D — HAND-DRAWN DIAGRAM INSTRUCTIONS

**Draw this on a single sheet of A4 paper. Use a pen or pencil. Photograph it clearly.**

Here is exactly what to draw:

---

**LAYOUT: Three concentric zones (draw three nested ovals or rings)**

**Outer ring — label it: BUSINESS**
**Middle ring — label it: TECHNOLOGY**
**Inner zone — label it: PSYCHOLOGY**

---

**INNER ZONE — PSYCHOLOGY (the core)**

Write in the center: **"Fear of blame"**

Draw three arrows radiating OUT from "Fear of blame":

Arrow 1 → label: "Suppress root cause data"
Arrow 2 → label: "Give vague timelines"
Arrow 3 → label: "Avoid escalating red items"

Draw a curved arrow that loops BACK from all three arrows into "Fear of blame" — label this loop: **"Blame in public meeting → more fear"**

This loop is the most important thing in the diagram. It shows the self-reinforcing nature of the problem.

---

**MIDDLE RING — TECHNOLOGY (the tools layer)**

Place these three boxes in the middle ring, connected by dotted lines to the inner arrows:

Box A: **"Deviation Tracker"** — connected by dotted line to "Suppress root cause data" — label the connection: "70% blank fields"

Box B: **"Alert Email / Unified Tracker"** — connected to "Avoid escalating red items" — label: "Dept names, not individual names → no ownership"

Box C: **"Daily Status Meeting"** — connected to "Give vague timelines" — label: "No daily micro-plan → everything is unplanned"

Draw a small X through a box labeled **"Monday.com"** somewhere in this ring — label it: "Failed adoption — tool before behavior"

---

**OUTER RING — BUSINESS (the consequence layer)**

Place three consequence nodes in the outer ring:

Node 1: **"CEO has no real visibility"** — draw an arrow FROM "Alert Email" box to this node — label: "Reports status, not causation"

Node 2: **"Organization cannot scale past 8 projects"** — draw an arrow from "Anil/Karthik = human glue" (write this phrase in the middle ring) to this node — label: "Remove humans → system collapses"

Node 3: **"No organizational learning from deviations"** — draw an arrow from "Deviation Tracker" to this node — label: "Blank fields = patterns invisible"

---

**THE KEY INSIGHT — draw this as a large arrow that pierces through all three rings from outside to inside:**

Label this arrow: **"Fix: Separate 'making problems visible' from 'punishing the person associated with the problem'"**

This arrow should visually cut through Business → Technology → Psychology, showing that the fix must operate at all three levels simultaneously.

---

**At the bottom of the page, write one sentence:**

*"All three problems are the same problem: the organization fused visibility with blame. Every tool built on top of this culture underperforms for the same reason."*

---

**Total elements on the page:**
- 3 concentric rings (Psychology / Technology / Business)
- 1 central concept (Fear of blame)
- 3 radiating arrows from center
- 1 feedback loop (curved arrow back to center)
- 3 technology boxes in middle ring
- 1 failed-tool marker (Monday.com with X)
- 3 business consequence nodes in outer ring
- 1 large cross-cutting arrow with the fix label
- 1 sentence at the bottom

This diagram will take approximately 20-25 minutes to draw carefully. Do not rush it. Label everything clearly. Use a ruler for the straight arrows if you have one. The diagram should look considered and deliberate — not a quick sketch.

---

# BONUS OBSERVATIONS

## 1. Role Drift of Anil and Karthik

Their mandate was to "introduce systems, improve departmental efficiency, and drive cultural change." What they actually do is attend every meeting, chase every action item, and fix printers. This is not a personal failure — it is what happens when you embed process specialists in an environment that has no self-sustaining accountability mechanisms. The urgent always crowds out the important. The solution is not to tell Anil and Karthik to "do less follow-up." It is to build systems that make follow-up unnecessary for routine items, so they can spend their capacity on observation and design — which is what they were hired for.

## 2. PDGMS Was Implemented and Abandoned

The structured daily planning tool was used for 3 months and then stopped. Karthik mentions they just restarted it this week. This is a significant signal — not about the tool, but about adoption design. A tool that gets adopted and then abandoned was not integrated into the daily workflow in a way that made it self-sustaining. It was running on Anil and Karthik's personal energy, and when that energy was directed elsewhere, it stopped. Any new system I build must be designed to survive without my daily intervention within 60 days. If it requires me to keep it alive, it is not a system — it is a project.

## 3. The SAP Vendor Claim Deserves Scrutiny

The organization is told "not possible in SAP" for most new requirements. This claim has never been independently verified. SAP is a comprehensive ERP — structured deviation logging, individual accountability tracking, and daily task planning are standard SAP PM and QM module functions. The vendor may be underresourced, commercially incentivized to keep the client dependent on workarounds, or simply not asked the right questions. In my first month, I would request a 45-minute technical call with the SAP implementation partner with a specific list of use cases — structured as "can SAP do X specifically?" not "can you help us do X?" The former gets a technical answer. The latter gets a sales answer. If SAP can support even 2-3 of the workflows currently being built in Excel, the organization should know that before building more Excel infrastructure.


