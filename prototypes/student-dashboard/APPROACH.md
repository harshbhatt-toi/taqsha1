# Taqsha student home: rework approach

Prototype: `index.html` in this folder (an artifact page fragment; the full write-up is on its **Approach** tab).

## Inputs
- `Taqsha_Features_by_Role` (Drive): student, mentor, facilitator and admin features with P0/P1/P2 priorities.
- `Taqsha_Final_Program_User_Journey` (Drive): the weekly loop (Steps 1–9), Week 4 presentation and skill profile, and open questions.
- Notion `Migration` doc: what the current platform runs on.
- Mobbin references (Coursera, Preply, Mercor, Contra, Codecademy, Uxcel, ClassDojo).

The live student dashboard wasn't available to review, so the "current state" is reconstructed from those docs.

## What the dashboard is for
1. Keep a solo, online student inside the weekly loop: Learn → Live session → Submit → Self-assess → Mentor feedback.
2. Make improvement visible: rubric trend, self-vs-mentor gap, and the Week 4 skill profile.

## Principles
- **The week is the unit.** A week header, the 4-week journey and the 5-step loop are always visible.
- **One next action, chosen by state.** The hero card changes with the day, deadlines, posted feedback and inactivity.
- **Only this week's content.** The library is filtered to the current milestone, with must-reads tagged.
- **Visible growth.** Students see their self-assessment next to the mentor's score, only after the mentor scores.
- **Recover without guilt.** The at-risk signal becomes a 25-minute catch-up plan, and streaks pause rather than reset.
- **Cohort as presence.** P2 social features sit in a rail pulse and don't take over the home screen.

## States designed
Start of week · Deadline (submit → self-assess → lock) · Feedback in · Week 4 final stretch · Drifting

## Phasing
- **v1 (P0):** week header and loop, hero rules, inline daily prompt, filtered library, live session hub, upload.
- **v1.1 (P1):** self-assessment lock, rubric trend, gap view, skill profile.
- **v2 (P2):** AI coach, cohort feed, badges, chat, countdown, all behind flags and A/B tested.

## Metrics
- **North star:** weekly loop completion.
- **Inputs:** prompt response rate, on-time submission, live attendance, time to first action.
- **Outcomes:** completion and certification, W1→W3 rubric growth, a shrinking self-vs-mentor gap.
- **Guardrail:** nudge opt-outs.

## Decisions needed
Nudge channel · late-submission rule · at-risk rule · whether students see the self-vs-mentor gap · certification trigger.
