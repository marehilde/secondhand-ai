# Product

## Register

brand

## Users

General readers first — anyone curious about how AI reshapes the people around its users, not just the users themselves. No prior familiarity with the research is assumed; the site has to work as a cold open. Academics and practitioners (HCI, medicine, education, policy) are a secondary audience who go deeper via the Research overview and per-paper detail pages, but the site is not written primarily for them.

The concept ("secondhand AI": the downstream effect of one person's AI use on what others receive, believe, and pass on) comes from an academic comment piece (see `uploads/secondhand-ai-extracted.txt`, likely destined for or accompanying a submission such as the NHB comment in `uploads/`). The site is the public-facing explainer companion to that piece, not the piece itself.

## Product Purpose

Make the concept of secondhand AI stick well enough that a reader can explain it to someone else afterward. The site teaches the idea through a guided scroll narrative (definition → concrete anecdote → three named mechanisms: content overload, illusory expertise, altered sender → why it matters → supporting research → real-world examples), then gives readers who want more a path into the underlying research and real-life cases.

Success looks like comprehension and retention (the concept transfers), not conversion, signup, or download — there is no product to adopt, only an idea to carry forward.

## Brand Personality

Rigorous but approachable · warm & humane · quietly urgent.

- Rigorous but approachable: credible enough to sit next to the cited PNAS/CHI/Nature Human Behaviour research, but never reads like a paper rendered as a webpage. Explanation before citation.
- Warm & humane: the subject is about people (Alice, Bob, a clinician, a patient, a student) affected by AI, not about AI itself. Keep the tone empathetic and concrete, not clinical or abstract.
- Quietly urgent: real stakes, understated delivery. No alarmism — the piece is explicit that secondhand AI can also benefit the recipient, not just harm them. Confidence without hype.

## Anti-references

- Generic SaaS/startup landing page: no hero-metric templates, gradient-text emphasis, or eyebrow-and-card scaffolding.
- Dry academic PDF/slide-deck look: should never read as a paper poured into HTML — it should feel designed, alive, and scroll-driven.
- Doom-y AI-panic clickbait: stay measured. The piece is deliberately two-sided (secondhand AI can help or harm); the design shouldn't tip it toward fear-mongering.

## Design Principles

1. **Concept before citation** — the mechanism is taught in plain language and a concrete anecdote (the AI scribe, Alice/Bob) before any paper is named; research backs up the idea, it doesn't introduce it.
2. **Show, don't summarize** — the three modes (content overload, illusory expertise, altered sender) are demonstrated through small scroll-driven scenes (sender → artifact → recipient), not just labeled.
3. **Depth is optional, never mandatory** — a reader can leave after the core narrative with the idea intact; the research drawer and real-life examples are for those who want to go further, not gates to understanding.
4. **Two-sided, not alarmist** — every mechanism section acknowledges secondhand AI can help as well as harm; urgency comes from stakes, not tone.
5. **One continuous visual world** — a single shared palette and type system carry across the index (which now also hosts the real-life examples gallery), the full explainer, and the research detail pages, so moving between them feels like one piece, not disconnected pages.

## Accessibility & Inclusion

Standard WCAG AA practice: sufficient color contrast for body text against the indigo/violet gradients, keyboard-operable modals and drawers, and a `prefers-reduced-motion` fallback for the scroll-jacked/pinned sections (the three-modes horizontal scroll and the sticky anecdote scenes) since those are the heaviest motion surfaces on the site. No other special requirements specified.
