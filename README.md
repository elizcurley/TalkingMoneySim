# The Case Lab — Beta 1.2

**Make your case. Keep your integrity.**

A static, browser-only prompt generator for practicing corporate code-switching, accurate impact language, persuasive conversations, feasible nonprofit grant proposals, and ethical decision-making. There is **no scoring engine, backend, tracking, login, or API key** in the generator. Students paste a generated prompt into a new conversation with an AI provider of their choice. That provider's own data and voice policies apply.

## What's new in 1.2

The interface now starts with five understandable activities, not a settings matrix. A student chooses an activity card and reads a short "What you'll do" explanation. The only main choices are:

1. **Starting material:** a fictional scenario or the student's own non-confidential example.
2. **AI provider:** Gemini, Copilot, Claude, or ChatGPT. Selecting one sets a recommended prompt length automatically.
3. **Speak or type:** shown only for the two activities where it helps, Jargon Gym and Pitch Room.

The previous detailed selectors (skill emphasis, complexity, scenario, prompt detail, pitch length, jargon drill pace, coaching, debrief, and ethical emphasis) are preserved under the collapsed **Customize my practice (optional)** panel. **Jargon Gym is the default starting activity** and the core case bank has not been reduced.

## Five activities

- **Jargon Gym:** One everyday line at a time, the learner tries a professional rewrite and an intentionally ridiculous corporate version. In short reps, say `NEXT` to get another.
- **Impact Language:** Convert actual routine work and invisible labor into persuasive, evidence-proportionate descriptions without invented outcomes or stolen credit.
- **Pitch Room:** Pitch aloud or in text to a simulated decision-maker who can ask questions, have their own interests, and remain unconvinced.
- **Proposal Workshop:** Develop fundable plans with plausible resources, activities, deliverables, evaluation, and capacity constraints.
- **Ethics & Power:** Discuss ethical tensions involving money, mission, influence, labor, donor preferences, and professional representation.

## Quick start

1. Click an activity card. The builder below explains what will happen.
2. Keep "Surprise me with a fictional situation" or choose your own *non-confidential* example.
3. Choose the AI provider. For pitches or jargon drills, choose spoken or typed practice.
4. Click **Generate my exercise** and **Copy prompt**.
5. Paste the **complete** prompt into a new conversation in the selected AI provider. If practicing aloud, enable that provider's voice feature after sending the prompt, where available.
6. Type or say `END PRACTICE` for qualitative feedback. There are no points or grades.

### Optional controls

Expand **Customize my practice** to specify a particular skill, raise complexity, select a known scenario, choose a prompt length, change the amount of AI coaching, or alter the feedback style. For the least intimidating first practice, leave this panel closed.

## Voice compatibility

The generator is text-only and does not transmit or record audio. Voice availability and whether a platform carries pasted context into a voice session can vary by account and device. Pitch Room defaults to speaking, and a shorter spoken kickoff is available if the full prompt is not carried into voice. The kickoff alone cannot preserve every case fact: where possible, use the complete prompt in a continuous chat.

## Boundaries

- Facts stay facts; predictions are not outcomes.
- Ethical concerns are explored, not automatically resolved.
- Learners must attempt writing/pitching before the AI offers its polished solution.
- The AI is a rehearsal partner, not a verified ethics ruling, fidelity assessment, grant reviewer, or source of confidential storage.
- Never enter client identifiers or confidential agency material in the generator or an AI chat.

## GitHub Pages deployment

Upload `index.html`, `style.css`, `cases.js`, and `app.js` to the **root** of a new or existing GitHub Pages repository. Enable Pages from the default branch/root in repository settings. You may upload the text guides alongside them. No build step, packages, secrets, or external JavaScript libraries are needed.

For faculty: see `FACULTY_GUIDE.md`; for brief student instructions: see `STUDENT_QUICK_START.md`.
