# Wizard of Oz Testing

*Not yet covered in a dedicated lecture as of 2026-09-07. Grounded directly in the course textbook (Preece, Sharp & Rogers, Ch.12 "Design, Prototyping, and Construction"). Update once the professor's own slides exist.*

## What it is

**Wizard of Oz (WoZ) testing** is a low-fidelity prototyping / evaluation technique in which a user interacts with what they believe is a working piece of software, but a **hidden human operator** ("the wizard") is actually generating some or all of the system's responses in real time, out of sight.

The name comes from L. Frank Baum's 1900 story: the "Wizard" is a small, ordinary man secretly operating an imposing artificial image of himself from behind a curtain, so onlookers believe they're dealing with a powerful autonomous entity. In UX terms: the user believes they're dealing with a finished autonomous system; in fact a person is puppeteering it.

## Why/when it's used

Wizard of Oz is used when the **real system doesn't exist yet, is too expensive/complex to build a working version of, or would take too long to implement** — but you still need to learn how real users would react to it. Rather than guessing, you simulate the intended behavior with a human standing in for the not-yet-built AI/logic. Common applications:

- **Conversational agents / chatbots** — a human types responses that appear to come from an automated assistant, to study how children (or any users) hold dialogues with virtual agents.
- **Gestural interfaces** — a hidden operator interprets a user's gestures and triggers the corresponding system response, to study gestural behavior before building real gesture recognition.
- **Human–robot interaction** — e.g., *Marionette*, a Wizard of Oz system used to study on-road interactions with autonomous vehicles: a hidden driver/operator controls the "self-driving" car's behavior so researchers can study how pedestrians/other drivers react to an apparently autonomous vehicle.
- **AI system prototyping more broadly** — a designer manually plays the role of the AI early on; as the design matures, real implementations of the AI can progressively replace the human "wizard."

## How it works, in practice

1. Design the intended interaction as if the system were real (what should it say/do in response to X?).
2. Hide the human operator from the participant (behind a screen, in another room, remote).
3. The operator observes the user's input and produces the system's output according to a script or their judgment, simulating the intended (not-yet-built) functionality.
4. Debrief and gain informed consent about the deception *after* the session, per standard ethics practice — participants must be told afterward that a human was operating the system.

## Strengths and limitations

**Strengths:**
- Lets you test user reactions to a system concept *before* investing in building the real (often technically hard, e.g., AI/NLP/robotics) functionality.
- Captures rich, natural user behavior because participants believe they're interacting with a real, complete system rather than a rough mockup.

**Limitations:**
- Requires a skilled, consistent "wizard" — human response time/consistency may not match what the eventual real system could deliver (faster or slower, more/less capable).
- Ethical care is needed around the deception involved (must debrief afterward).
- Findings may not fully transfer if the real system, once built, behaves noticeably differently from how the human wizard simulated it.

## Design implications

- Use WoZ specifically to de-risk features that are expensive/uncertain to build (a proposed AI feature, a new gesture vocabulary, an autonomous behavior) before committing engineering resources.
- Script the wizard's responses as consistently as possible across participants to reduce bias/variability in results.
- Treat it as a **low-fidelity prototyping** method (per the textbook's classification, alongside paper prototypes and storyboards) — it's about testing the *concept and interaction flow*, not final performance.

## Key exam talking points

- Explain the name's origin and what it signals about the technique (hidden human, apparent autonomy).
- Give at least one concrete use case (conversational agent, gestural interface, or autonomous vehicle) and explain what question it lets you answer that you couldn't answer by just asking users hypothetically.
- Connect it to [Usability Testing](07-Usability-Testing.md) as a technique used *before* a real system exists, versus the instrumented (eye-tracking/physiological) methods used to test systems that already exist.
