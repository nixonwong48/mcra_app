# Grad Ready app prototype (owner: Eryn)

This is an extra deliverable with about 30 seconds of the presentation, so it only needs to work and show how it solves the persona's needs and pain points.

## Current prototype (original starter by Nixon)

`index.html` is a single-file, clickable prototype. Open it by downloading the file and double-clicking it (it runs in any browser, with no install). Everything on screen is **sample data** and says so.

| View | What it does | Pain point it fixes |
|---|---|---|
| Student, Graduation tab | All requirements on one page (done / in progress / missing), early-warning banner, **Request seat** with a 48-hour reply clock | Requirements spread across 5 portals; late audit; needed module full in BOSS |
| Student, Career tab | 3 employer intros (incl. a hiring capstone sponsor), a one-week calendar with clashes flagged, interview-leave request with a 48-hour clock | Career fair mostly banks; assessments clash with project deadlines; no rule on interview absences |
| Advisor | Pending requests with countdowns, students at risk first, Approve / Decline / Confirm audit | Advisor replies take about a week |
| SCIS management | Students at risk, audits confirmed, average reply time, requirements on track, suggested owners | Gives us our success metrics |

The layout adapts to phone, tablet and laptop. On a laptop, a **Phone / Laptop** switch in the top bar shows any view (student, advisor or management) inside a phone frame or at full width. The student view opens in the phone frame by default, which suits the 30-second demo.

The views are linked: a seat request made as the student shows up in the advisor view, and approving it updates the student view and the management tiles. Expand **Presenter guide & demo controls** beside or below the app to access **Skip 24 hours (demo)** and **Reset demo**.

## Try the complete flow

1. Open `index.html` in your browser; no install or build is needed.
2. In **Student → Graduation**, click **Request seat**.
3. Switch to **Advisor**, approve the seat, then **Confirm audit** for Marcus.
4. Open **Management** to see the updated metrics.
5. Return to **Student → Career**. Request an employer intro, then use **Request leave** on Friday’s interview clash.
6. Submit the leave form, approve it in **Advisor**, and return to **Career** to see the result.

All state is kept in browser memory. Refresh or **Reset demo** to start again; requests do not reach real advisors or employers. Google Fonts requires internet access, with system fonts as a fallback.

## Presentation checklist

1. **Own it.** Change anything you like in `index.html`: wording, layout, or rebuild it in Figma if you prefer. The brief accepts Figma or a simple web page.
2. **Backup screen recording** of the demo path, in case the live demo fails. Save it here as `Grad_Ready_demo_v1.mp4`.
3. **Demo path (about 30 seconds):** Student, request a seat → Advisor, approve the seat and confirm Marcus’s audit → Management, point at the updated tiles → Student Career, show the interview clash. Practise it until it takes under 30 seconds.
4. **Test with 3-5 seniors or an advisor** so we can say something like "4 of 5 said they'd use it weekly". This must be real feedback, not invented.
5. **Q&A prep (you answer the app and launch-plan questions):**
   - *Who uses the app?* Students, advisors and SCIS management.
   - *Is it feasible?* This is a prototype. We show the idea and the metrics it would give us.
   - *How will students hear about it?* Through Telegram and seniors first (Marcus trusts them more than official announcements), then the advisor at the first Year 4 meeting.
   - *SMU already has a career portal, so why build this?* We don't replace it. We bring the relevant jobs into one place and line them up with academic deadlines, which no portal does today.

## Rules

- Save new versions with a number (`index_v2.html`) if you want to keep the old one.
- Keep all data labelled as sample or illustrative. Don't invent real statistics.
- If time runs short, show 3 static screens instead of a live demo.

## Current interaction details

- Graduation opens in Term 1, Week 1, with audit confirmation due by Week 3.
- Seat approval resolves the missing requirement; audit confirmation is a separate advisor action. Both are needed to remove Marcus from the at-risk count.
- Career has exactly three features: employer introductions (including a hiring capstone sponsor and alumni mentor support), a combined deadline calendar, and interview leave.
- The calendar distinguishes workload clashes from overlapping appointments. The interview clash button opens the leave form with the matching activity selected.
- Interview requests retain the employer and activity for the advisor and student status screens. Introduction requests show “Intro pending with SCIS” and can be cancelled.
- Management uses average reply time consistently. “Requirements on track” counts students without missing requirements; it is not an actual graduation rate.
- White surfaces and charcoal actions stay light regardless of system theme. All records and metrics are sample data; refreshing resets the demo.

## Phone layout

Graduation separates the next action, active requirements and audit status into cards. Completed requirements expand on tap. Career has three numbered sections, separate employer cards and one card per calendar day. Presenter notes and demo controls are inside the expandable presenter guide below the app.
