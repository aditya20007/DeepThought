DeepThought AI
Business Analyst — Process Management Assignment

Submitted by: Aditya Singh | IIT Patna | singhadityakumar566@gmail.com

Executive Summary
After reading through the scenario a couple of times, my main takeaway is this: PharmaTech has done a great job setting up a reporting infrastructure, but they haven't built an execution culture to match it. The tools are there, the tracker is running, and the morning emails go out like clockwork. But nothing is actually moving.

The reason for this isn't a tech problem; it's a people problem. At its core, the organization hasn't figured out how to separate "highlighting a problem" from "punishing the person tied to that problem." Until they fix that, every new tool they introduce is going to underperform. It won't be because the tool is bad, but because the people using it are smartly trying to protect themselves.

All three situations in this scenario are just different symptoms of the same underlying issue. In my diagnosis below, I've tried to call out this issue clearly, and my proposed fixes focus on treating the root cause—starting with the people, not just adding more dashboards.

PART A — DIAGNOSIS
Situation A — The Alert Nobody Responds To
The Stated Problem:
The CEO gets an automated email every day showing red and amber items across different departments. Those items stay red for days, but nobody escalates them or responds. Anil and Karthik think the system is working fine, but the CEO feels like he's still in the dark.

What Is Actually Going On:
The alert system isn't really broken; it's just doing the wrong job.

It was built to give the CEO visibility, and it does that—he can see who is in the red. But having visibility without a clear plan of action is just standing around watching. It’s like installing a fire alarm in a building but never teaching anyone what to do when it goes off. The alarm works perfectly, but the evacuation is a disaster.

There are three main structural cracks here:

Accountability is tied to departments, not real people. The email says "Warehouse: RED," not "Rajesh Kumar: 3 tasks overdue." The advisor nailed this when he pointed out that nobody feels the pressure when a whole department is flagged. If a specific person's name is on it, they’ll show up prepared. When you anonymize accountability, people naturally diffuse the responsibility.

The alerts have no memory and show no urgency. An email on Day 1 showing "3 days overdue" looks exactly the same as an email on Day 6 showing "8 days overdue." Without trend signals or escalation history, everything feels equally urgent, which means nothing actually feels urgent. It’s like living next to a highway—eventually, you just tune out the noise.

Nobody defined what "taking action" actually looks like. When someone sees a red item, what are they supposed to do? Who handles it? Is there a 24-hour window to fix it? Anil and Karthik built the pipeline, but they never designed the rules for what should happen when the pipeline sends an alert.

Because of this, Anil spends his whole week manually chasing people down. He has essentially become a human band-aid for a broken escalation system. If Anil leaves, the whole thing stops.

Situation B — The Blank Root Cause Field
The Stated Problem:
About 70% of the root cause fields in the deviation tracker are left blank or filled with vague filler like "under investigation." Anil and Karthik think the team just lacks discipline.

What Is Actually Going On:
This is the most critical diagnostic moment in the whole scenario, and Anil and Karthik completely missed it. They were asking, "Why aren't people filling this out?" when they should have been asking, "What happens to someone when they actually tell the truth?"

Two supervisors gave us the real answer: if they write down what actually went wrong, they get interrogated in front of 12 people—including the CEO—in the morning meeting. It turns into a massive blame game.

This isn't a discipline issue at all. These are experienced professionals who have learned that being honest in this company leads to public embarrassment. So, they do the smart thing: they write nothing, keep their heads down, and fix the problem quietly.

The company accidentally created a culture that punishes transparency and rewards staying quiet. The 70% blank rate just proves that the team has a healthy instinct for self-preservation. You can't fix this with more training; you have to change what happens after someone reports an issue honestly.

Situation C — The Meeting That Eats the Day
The Stated Problem:
The daily 30-minute status meeting routinely drags on for 60 to 90 minutes. Afterward, everyone’s day is totally derailed by random, unplanned work that got dumped on them during the call.

What Is Actually Going On:
This is a mix of poor planning, bad meeting design, and hidden organizational issues all crashing into each other.

The root cause is a lack of planning. The department heads don't have daily micro-plans, and neither do Anil or Karthik. If you don't have a plan for the day, everything feels like an emergency. The meeting isn't creating the chaos; it's just exposing the chaos that's already there.

The meeting design is mathematically impossible. You can't fit 12 people giving updates into 30 minutes. It was doomed to run over from the start. On top of that, deep technical issues (like machine breakdowns) get discussed in front of everyone, dragging the whole room into a problem that only affects two people.

It's the only place the CEO gets real news. Because the automated emails aren't helpful, this meeting is likely the only time the CEO and COO actually find out what's happening on the floor. People subconsciously let the meeting drag on because it's serving a purpose the broken system isn't.

It creates ripple effects. When an issue gets announced to 12 people at once, everyone shifts their day around to react to it. A structured triage system would contain that noise to just the 2 or 3 people who actually need to fix it.

The Systemic Connection
These aren't three separate problems; they are the exact same problem wearing different hats.

The company has fused "making problems visible" with "blaming someone for the problem." Because of this fear, supervisors hide data (Situation B). Because data is hidden, the CEO has no visibility, so nobody acts on the tracker (Situation A). Because there’s no visibility, leadership relies heavily on the daily meeting to figure out the truth (Situation C). That high-pressure meeting generates more fear, which leads to more hidden data.

It's a toxic loop. You can't break it by adding software. You break it by changing how leadership reacts to the truth.

PART B — INTERVENTION DESIGN
Situation A — Making the Alert Drive Action
The First Conversation:
I'd pull the COO aside informally—maybe in the hallway or over coffee—and ask one question: "When you see a red item in the morning email, what do you expect to happen next?" I genuinely want to know the answer. If he says Anil handles it, I know we have a bottleneck. If he admits he isn't sure, I've found my opening.

First Two Weeks (No Tech, Just Humans):

Week 1: I sit in the daily meeting and just observe. Who speaks up? Who hides? Do people volunteer, or do they wait for Anil to assign tasks? I also chat one-on-one with the department heads who have the most red items, strictly to understand their workflow blockers, not to scold them.

Week 2: I introduce one tiny change to the meeting. After a red item is discussed, someone has to ask, "Who owns this, and what's the next step before tomorrow?" That verbal, public commitment gets logged. I also agree on a simple rule with the COO: if an item is red for 3 days, it triggers a direct chat between the COO and the department head.

The Tool:

The WhatsApp Prompt: Every morning at 8:15 AM, department heads get a friendly, automated WhatsApp message with their name, listing their overdue items, and asking if they need help unblocking anything before the 9 AM meeting. It feels supportive, not like policing.

The Upgraded Email: The CEO's email gets revamped to show individual names, how many days an item has been red, a trend line (is it getting worse?), and the very next committed action.

The Tech Stack: I stick to Excel, Power Automate, and WhatsApp. No new software. It’s exactly what they already use, just connected smarter.

Getting the Veteran on Board:
I sit down with a 15-year veteran and ask them to walk me through their exact process for a task. When they explain how many steps rely on other people, I frame the new system as a way to protect them: "Right now, the tracker makes you look slow. Let's make those dependencies visible so when Finance is holding you up, Finance looks like the blocker, not you."

Situation B — Making Root Cause Safe to Fill
The First Conversation:
I find a mid-level supervisor, ask about a recent deviation, and just listen. Afterward, I ask if any of that real story made it into the official log. When they say no, I ask, "What would happen to you if you did write it down?" That’s the real root of the issue.

First Two Weeks (No Tech, Just Humans):

Week 1: I pitch the COO on moving deviation discussions out of the big daily meeting. We set up a separate, smaller 30-minute weekly technical review. No CEO present for the first month. The vibe is strictly problem-solving, not finger-pointing.

Week 2: In that new meeting, I model the right behavior. If someone gives a vague answer, I ask curious questions to dig deeper without interrogating them. I also enforce a hard rule: root cause discussions from this smaller room cannot be weaponized in the big daily meeting.

The Tool:

The Google Form: A super simple, mobile-friendly Google Form that asks "What did you observe?" instead of the intimidating "What is the root cause?" It includes an "Unknown" option so people don't feel forced to make something up.

The Workflow: Supervisors fill it out quickly on their phones. Every Friday, Anil runs the data through a quick AI prompt (like Claude) to spot recurring patterns. Those patterns form the agenda for the weekly technical meeting.

The Tech Stack: Google Forms, Google Sheets, and a 30-second weekly AI prompt.

Getting the Veteran on Board:
I tell the veteran supervisor: "You've been fixing things quietly for years, but when you retire, all that knowledge leaves with you. I don't want you writing reports for management; I want you leaving notes for the next shift." It frames the tool as building institutional memory, which veterans deeply respect.

Situation C — Fixing the Meeting and Building Daily Planning
The First Conversation:
A quick, 3-minute chat with the CEO. I explain that the meeting is trying to do three different jobs at once and failing. I ask for permission to come back with a structural redesign.

First Two Weeks (No Tech, Just Humans):

Week 1: Anil starts doing triage 30 minutes before the meeting. He categorizes tracker items into "quick status update" or "needs a longer discussion." The daily meeting is now strictly restricted to the quick updates.

Week 2: I introduce a 5-minute daily micro-planning habit for Anil and Karthik to map out their top 3 tasks and expected roadblocks. For the department heads, the COO simply asks them to come to the meeting with exactly one sentence prepared for each of their overdue items.

The Tool:

The Prep Message: The same 8:00 AM WhatsApp message asks department heads to prepare their one-liners.

Live MOM: A shared Google Doc for meeting minutes is updated live during the call, tracking the owner, the status, and the next deadline.

Unplanned Work Log: Department heads drop one line a week into a tracker about unexpected fires they had to put out. Anil aggregates this to help the COO spot trends (e.g., "Unit 2 broke down 4 times this week, we need maintenance").

Getting the Veteran on Board:
I pitch it purely as a time-saver: "You're spending 90 minutes in a room where half the stuff doesn't apply to you. Let's get your part done in 5 minutes so you can have your morning back." Veterans love getting their time back.
