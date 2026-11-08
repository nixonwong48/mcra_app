# Smaply AI prompt: rebuild the journey map (v2)

Paste everything inside the code block into Smaply's AI. The content is the v1 map's own wording, with these changes:

- Description box now covers all 12 steps.
- "over a week" is now "about a week" (matches the persona).
- A new **Opportunities** row is added.
- "Recruit more sponsors with hiring intent" stays under **Capstone showcase**, next to its pain point. (The team plan said Sponsor Review, but the pain point is on the showcase step.)
- Two opportunities are **proposed** (steps 5 and 11) and are marked in the table below. Confirm them with the team or delete them.

After generating, check three things by hand: the emotion curve values, the photos, and that there are exactly 12 steps.

```text
Create a customer journey map in English with the title "SCIS Student Journey: Final Year to Graduation and Employment".

PERSONA
Use the persona "Marcus Tan", a Year 4 Information Systems student at SMU SCIS. Scenario: from the start of final year to a job offer and graduation. Expectation: "SCIS gets me employed and graduates me on time."

RULES
- Use my wording exactly. Do not invent, merge, split, add or remove steps. Exactly 4 stages and exactly 12 steps.
- Keep every text short, in plain sentence case, no emojis.
- Leave a cell empty where I write "none". Do not fill it.
- Use these rows, in this order: Journey Stages, Journey Steps, Actions (with one thought bullet), Pain points, Opportunities, Journey Storyboard (one picture per step), Channels, Emotion chart.
- Emotion chart: scale from -2 to +2, one point per step, using the values below.

DESCRIPTION BOX (put this text in the description at the top)
Persona: Marcus Tan, Year 4 SMU SCIS Information Systems student. Scenario: from the start of final year to a job offer and graduation. Expectation: "SCIS gets me employed and graduates me on time." Channels: Email, Telegram, LinkedIn, Phone, Face to face.
Stage A, Set up final year (Jul-Sep): 1. Plan final year (emotion 0). 2. Form capstone team (0). 3. Capstone kickoff (+1).
Stage B, Job hunt (Sep-Nov): 4. Recruitment season (0). 5. Online assessments (-1). 6. Interviews vs coursework (-1).
Stage C, Prove it (Nov): 7. Capstone development (+1). 8. Sponsor review (+1). 9. Capstone showcase (+2, BEST experience).
Stage D, Finish and leave (Jan-mid-year): 10. Final term audit (-2, WORST experience). 11. Scramble for appeal (-1). 12. Graduate and become alumni (+1).
Behind the scenes: academic advising, registrar, capstone office, career centre, faculty, alumni office.

JOURNEY STAGES
A. Set up final year (Jul-Sep): steps 1-3
B. Job hunt (Sep-Nov): steps 4-6
C. Prove it (Nov): steps 7-9
D. Finish & leave (Jan-mid-year): steps 10-12

STEPS
Step 1: Plan final year
Action: Marcus runs a degree audit in the portal and bids for his final modules in the BOSS system.
Thought: "Do I actually have everything I need to graduate?"
Pain point: Audit info is spread across multiple portals and the academic advisor takes about a week to reply.
Opportunity: One audit checklist confirmed by Week 3.
Channels: BOSS Portal; Email
Emotion: 0
Picture: a student reading in a library aisle

Step 2: Form capstone team
Action: Marcus coordinates with classmates to form a capstone project team and align on system development interests.
Thought: "I need to find a team that is committed to the same technical stack."
Pain point: none
Opportunity: none
Channels: Telegram; In Person
Emotion: 0
Picture: students gathered around a table in a library

Step 3: Capstone kickoff
Action: The team is matched with an industry sponsor, scopes the problem, and requests project data.
Thought: "Finally, real work with a real company."
Pain point: The industry sponsor is slow to share data, causing two weeks of project time to be lost.
Opportunity: Sponsor data-readiness checklist.
Channels: Face to Face; Email
Emotion: +1
Picture: a team meeting an industry sponsor at a networking event

Step 4: Recruitment season
Action: Marcus attends the campus career fair and submits over 40 job applications online.
Thought: "Everyone here is hiring bankers, not PMs."
Pain point: There are very few product manager roles available at the career fair.
Opportunity: Product and analytics employer sessions.
Channels: Career Fair; LinkedIn
Emotion: 0
Picture: students at a campus career fair

Step 5: Online assessments
Action: Marcus sits for multiple online technical assessments and coding tests required by employers.
Thought: "These assessments are taking up all my project coding time."
Pain point: Online assessments pile up heavily during peak academic project deadlines.
Opportunity: One calendar that shows assessment and project deadlines together and flags clashes.
Channels: Web Portal; Email
Emotion: -1
Picture: a student taking an online test on a laptop

Step 6: Interviews vs coursework
Action: A final-round job interview clashes directly with a graded team presentation.
Thought: "Do I risk my grade or the job?"
Pain point: There is no clear school policy on interview absences, leaving decisions entirely to the professor.
Opportunity: Interview-leave form with a 48-hour reply.
Channels: Email; Phone Call
Emotion: -1
Picture: a worried student checking a phone and laptop

Step 7: Capstone development
Action: Marcus and his team build out the prototype and integrate feedback from the academic advisor.
Thought: "We need to make sure this solution actually works for their system."
Pain point: none
Opportunity: none
Channels: GitHub; Lab Meetings
Emotion: +1
Picture: a team working on laptops around a table

Step 8: Sponsor review
Action: The team presents their interim progress to the industry sponsor for validation.
Thought: "I hope the sponsor is satisfied with our progress so far."
Pain point: none
Opportunity: none
Channels: Face to Face; Email
Emotion: +1
Picture: a meeting around a conference table

Step 9: Capstone showcase (BEST experience)
Action: Marcus demos the completed solution to the sponsor and faculty, earning an immediate interview invite.
Thought: "This is why I came to SCIS."
Pain point: Many showcase sponsors attend only for grading rather than active talent recruitment.
Opportunity: Recruit more sponsors with hiring intent.
Channels: Face to Face; LinkedIn
Emotion: +2
Picture: a presentation in a lecture theatre

Step 10: Final term audit (WORST experience)
Action: A late graduation audit flags a missing requirement, while the needed module is already full in BOSS.
Thought: "My job offer depends on graduating. Why am I only finding out now?"
Pain point: Late audits flag missing requirements when the required module is already full in BOSS.
Opportunity: Early-warning audit and reserved seats for graduating students.
Channels: Email; Phone Call
Emotion: -2
Picture: a stressed student at a laptop

Step 11: Scramble for appeal
Action: Marcus files urgent appeals and contacts academic advisors to secure a module seat.
Thought: "I can't let a single module ruin my job offer."
Pain point: The manual appeal process is slow and lacks transparency during a high-stakes period.
Opportunity: Appeal tracking with a clear reply time.
Channels: Advising Office; Email
Emotion: -1
Picture: two people talking across a table in an advising office

Step 12: Graduate & become alumni
Action: Marcus attends commencement, starts his new job, and is added to the alumni mailing list.
Thought: "Relieved. Proud, mostly."
Pain point: Alumni emails are generic, unengaging, and quickly ignored by new graduates.
Opportunity: Alumni mentoring for Year 3-4s.
Channels: Commencement; Email; LinkedIn
Emotion: +1
Picture: a graduate throwing a cap
```

## Check after generating

| Check | What it should be |
|---|---|
| Stages | 4: Set up final year, Job hunt, Prove it, Finish & leave |
| Steps | Exactly 12, in the order above |
| Emotion curve | 0, 0, +1, 0, -1, -1, +1, +1, +2, -2, -1, +1 |
| Best / worst | Peak at step 9, lowest point at step 10 |
| Empty pain points | Steps 2, 7, 8 |
| Opportunities row | Filled for steps 1, 3, 4, 5, 6, 9, 10, 11, 12 |
| Proposed opportunities | Step 5 (shared calendar) and step 11 (appeal tracking): confirm with the team or delete |
| Wording | Step 1 pain point says "about a week" |
