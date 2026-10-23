# The Case Lab — Beta 1.1

**Make your case. Keep your integrity.**

A completely static, GitHub Pages-ready training site for human-service students, nonprofit staff, and emerging professionals who need to translate routine accomplishments into credible value, pitch themselves and their work, develop fundable grant proposals, and handle ethical tension in fundraising and professional self-advocacy.

The website generates **copy-and-paste prompts** for university Microsoft Copilot, Google Gemini, Claude, and ChatGPT. It does **not** call an API, store transcripts, assign numerical scores, or require a login. The *external AI platform* processes prompts after users paste them there.

## Five studios

| Studio | What learners practice | How the AI behaves |
|---|---|---|
| Jargon Gym | Quick, playful translation of everyday experiences into useful professional language and deliberately exaggerated corporate jargon; reverse translation and buzzword detection | A coach who asks for the learner’s attempt first, then supplies a grounded edit and clearly labeled humorous parody |
| Impact Language | Translating mundane work and invisible labor into credible, audience-specific professional language | A candid editor who requires the learner to draft first, then offers specific critique |
| The Pitch Room | Asking for support, making a donor or hiring pitch, responding to objections, and negotiating feasibility | A person with their own interests who may push back or decline |
| Proposal Workshop | Needs statements, logic models, outputs/outcomes, plans, evaluation, budgets, capacity and sustainability | An iterative reviewer who asks for the learner's first attempt rather than ghostwriting an entire proposal |
| Ethics & Power | Professional discomfort, donor influence, community voice, dignity, accurate credit, unfair burdens, and conflict with mission | A credible stakeholder who tests reasoning without imposing a single predetermined answer |

The case bank contains **72 fictional scenarios** (48 original studio situations plus 24 Jargon Gym examples). Practice emphases are selected *within* the chosen studio. Students can also bring **their own non-confidential facts**; the browser does not upload, retain, or verify these facts.

## Settings

- **Practice studio:** choose between five studios, including new **Jargon Gym** (the default for easy practice).
- **Practice emphasis:** specific communication or grant-writing skill.
- **Challenge:** moderate, challenging, or advanced. Changes scrutiny and ambiguity, not the counterpart's hostility.
- **Fictional situation:** pick a case or get a different one randomly. Random generation avoids repeating previously seen cases within the open page until that mode's bank is exhausted.
- **Starting material:** a fictional scenario or your own non-confidential facts.
- **Delivery (Pitch Room or Jargon Gym):** text or spoken voice practice; Pitch Room defaults to spoken. Spoken mode generates voice-friendly instructions and platform-specific handoff guidance.
- **Pitch format:** short opener (~30 seconds), elevator (~60 seconds), longer (~2 minutes), or an untimed Q&A. These are goals, not measured time.
- **Jargon practice pace:** one-line rapid-fire drills (say/type `NEXT` for another), or a slower workshop to compare registers.
- **AI platform and prompt length:** defaults to a shorter prompt for Copilot, portable for Gemini, expanded for Claude and ChatGPT. Length can be overridden. These are compatibility-oriented design choices, not guarantees of platform behavior or official character limits.
- **Support:** immersive roleplay, coaching by request (`COACH PAUSE` / `RESUME PRACTICE`), or occasional clearly labeled guidance.
- **Debrief:** balanced, direct critique, or brief recap; **never a score**.
- **Ethical lens:** integrated, or foreground ethical tradeoffs.

## Start and end

1. Open `index.html` or the GitHub Pages site.
2. Select a studio and options, then **Generate practice prompt**. For a first low-stakes exercise, try Jargon Gym with the default quick drill.
3. Click **Copy prompt** and paste the complete text into a *new conversation* with the chosen AI.
4. In Pitch Room with Spoken selected, activate your chosen AI platform’s **voice conversation** inside the prepared chat, if available. The site itself does not record or transmit audio. If the AI opens a fresh voice chat, try the separate **spoken kickoff** or return to the full prompt in text. Then speak or write as the learner. The AI should not generate a polished answer before you attempt the exercise (other than its roleplayed opening or brief).
5. Type or say **`END PRACTICE`** to stop and receive qualitative feedback. **`CHECK PROGRESS`** requests a brief non-scored process check while continuing.
6. If support was set to coaching by request, type **`COACH PAUSE`** and **`RESUME PRACTICE`**.

## Deploy to GitHub Pages

1. Create a **new public repository** (recommended; this does not replace your existing simulation sites).
2. Extract the *GitHub Pages ZIP* and upload its contents to the repository root: `index.html`, `style.css`, `cases.js`, `app.js`, and `README.md`.
3. In repository Settings → Pages, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. Visit `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/` once GitHub Pages is deployed.
5. To revise cases, edit `cases.js`. To revise prompting or settings, edit `app.js`. Layout and visual styles live in `index.html` and `style.css`.

**Site privacy:** generation and scenario selection are local to the browser. This website makes no data-collection requests and does not save user content. Copying facts to an external AI platform is a separate decision subject to that platform's privacy terms. Do not paste identifying client data, confidential student information, private donor records, or employer-only information into an AI tool without authorization.

## Nonnegotiable instructional distinctions

- **Activity:** what staff or participants did.
- **Output:** what the program delivered or counted.
- **Outcome:** what changed for a defined person/group, as supported by evidence.
- **Impact:** a larger and often longer-term effect, usually harder to attribute and demonstrate.

Positive language should match the strength of the evidence. A participant count is not a retention rate, a referral is not successful service access, and an aspiration is not an achieved outcome. Do not claim all work as one's own, invent numbers, use clients as marketing props, or promise impossible capacity.

## Ethics and source links

The lab uses broad professional themes from the **NASW Code of Ethics**. The following references may be useful starting points for discussion, not automatic findings of an ethical violation:

- [Official NASW Code of Ethics](https://www.socialworkers.org/about/ethics/code-of-ethics)
- [Privacy and confidentiality (1.07)](https://www.socialworkers.org/About/Ethics/Code-of-Ethics/Code-of-Ethics-English/Social-Workers-Ethical-Responsibilities-to-Clients)
- [Administration and equitable resource allocation (3.07)](https://www.socialworkers.org/About/Ethics/Code-of-Ethics/Code-of-Ethics-English/Social-Workers-Ethical-Responsibilities-in-Practice-Settings)
- [Misrepresentation (4.06) and acknowledging credit (4.08)](https://www.socialworkers.org/About/Ethics/Code-of-Ethics/Code-of-Ethics-English/Social-Workers-Ethical-Responsibilities-as-Professionals)

Students should consult the current Code directly when referencing a particular standard. Ethics discussions should consider power, competing obligations and implementation context rather than using the Code as a simplistic answer key. The tool is educational and not a legal, financial, fundraising, or professional ethics determination.

## Tested for Beta 1

- 48 scenario anchors available, 12 per studio.
- 625 structured application-logic combinations checked, including all case anchors and custom source facts.
- 144 real-browser interaction combinations across four modes, four platforms, three difficulty levels, and three coaching states.
- No browser runtime errors or horizontal overflow at the tested 390px mobile width.
- In the tested fictional cases, the short prompt stayed under 3,100 characters and the portable prompt under 5,200 characters. User-written facts can increase length; the interface warns when its suggested length is exceeded, without silently deleting their source facts.

**Limit:** Model behavior across full-length conversations in every external AI product has **not** been validated. Early beta testing should compare whether the AI preserves facts, maintains skepticism without cruelty, makes the student do the work, and gives fair rather than flattering feedback.

## Voice practice: realistic compatibility notes

The website is a static **prompt generator**, not a voice-chat platform. Voice conversations happen inside the chosen AI application, subject to its subscription, admin, device, and regional settings. The preferred workflow is: **paste full prompt → send → activate voice in the same conversation → speak your pitch → debrief**.

- **Gemini:** Gemini Live is available in the eligible mobile app, not the standard web chat. Create/open the same Gemini chat in the mobile app and switch to Live if permitted.
- **Copilot:** Microsoft offers Copilot Voice for eligible personal and workplace/school accounts; availability and context handoff vary. Voice may use a different system than text. The site supplies a separate concise kickoff if the voice UI starts a different conversation.
- **Claude:** supports text/voice switching in the same conversation on supported web, desktop, and mobile clients.
- **ChatGPT:** supports Voice within an existing chat when enabled for the account and device.

The **voice kickoff is a fallback**, not a substitute for the full case packet. Models should not claim they measured vocal timing, pauses, volume, affect, eye contact, or nonverbal presence when they only have text/transcription. In voice mode the AI should use short, human-sounding replies, realistic objections, and one follow-up question at a time; it should not jump into feedback during a pitch.

## Jargon Gym: learn the dialect without losing the truth

The rapid drills give learners one everyday statement at a time. They attempt a professional rewrite; the AI helps distinguish **plain language**, **workplace-usable professional language**, and **deliberately ridiculous corporate jargon**. The comic version is explicitly a *parody*, not a recommended resume line.

Example: *“I cut off a toxic friend.”* → credible: *“Established and maintained boundaries in a difficult personal relationship.”* → comic: *“Implemented a values-aligned stakeholder disengagement strategy.”* These are ways of reframing the user's account, not proof of diagnoses, outcomes, or formally held responsibilities. Learners can also decode jargon back into plain English, compare audiences, and flag unsupported claims.
