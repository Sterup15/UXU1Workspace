# Social Interaction

*Sources: **UXU 3 – Social Interaction** lecture (14 Sep 2026); Preece, Sharp & Rogers Ch.5 "Social Interaction".*

## Lecture structure

The deck follows six steps, which is a good skeleton for an exam answer:

1. Being social
2. Face-to-face conversations
3. Remote conversations
4. Tele-presence
5. Co-presence
6. Shareable technologies

Course competency goal: *"Propose innovative solutions for enhancing social interactions in digital products."*

## 1. Being social

People are inherently social — we live, work, learn and play together. The lecture opens with provocations rather than answers:

- Are **face-to-face (F2F) conversations being superseded** by social media interactions?
- How many friends do you have on Facebook/LinkedIn **vs. real life** — and how much do the two sets overlap?
- How are the ways we live and interact with one another changing?
- Are established **rules and etiquette** still applicable both online and offline?

(The textbook adds the data behind this: people average a few hundred Facebook friends and often 1,000+ LinkedIn connections — far more than face-to-face networking ever produced — and Sherry Turkle's (2015) critique that convenience is displacing conversation and with it the practice of empathy.)

## 2. Face-to-face conversations: the social mechanisms

**Conversational rules** are the tacit machinery that makes conversation work:

- **Turn-taking** — used to coordinate conversation. The lecture demonstrates it by showing a dialogue where it *breaks*:
  > A: Shall we meet at 8?
  > B: Um, can we meet a bit later?
  >
  > A: Shall we meet at 8?
  > B: Wow, look at him?
  > A: Yes what a funny hairdo!
  > B: Um, can we meet a bit later?

  In the second version the answer arrives three turns late, after a digression — the thread still gets repaired, but only because both parties track who owes whom a response.
- **Back-channelling** — the small signals ("uh-uh", "umm", "ahh", nodding) that tell the speaker *keep going, I'm following*. Their absence is exactly what makes silent video calls and text chat feel awkward.
- Other mechanisms (textbook): adjacency pairs (question→answer), **repair** of misunderstandings, and non-verbal cues (eye contact, gesture, tone).

### Transactional Analysis (Eric Berne's P–A–C model)

The lecture introduces **Transactional Analysis** as a way of analysing *who is talking to whom* in a conversation. Every person operates from one of three ego states:

- **Parent (P)** — either **nurturing** (caring, supportive) or **controlling** (critical, commanding, "you should…").
- **Adult (A)** — rational, factual, problem-solving, peer-to-peer.
- **Child (C)** — either **adapted** (compliant, apologetic, rebellious — reacting to authority) or **natural** (spontaneous, playful, curious).

A conversation is a series of **transactions** between these states. **Complementary** transactions (Adult→Adult, or Parent→Child answered by Child→Parent) run smoothly; **crossed** transactions (you address someone Adult→Adult and get a Parent→Child reply) cause friction and breakdown.

**Why this matters for UX:** an interface has a "voice" and therefore an ego state.
- A system that scolds ("You have entered an invalid value!") speaks as a **controlling Parent** and pushes the user into an **adapted Child** state — defensive, anxious, feeling stupid. This is exactly the emotional failure mode described under *annoying interfaces* in [Emotional Design](01-Emotional-Design.md).
- A system that over-coddles ("Don't worry, I'll take care of everything for you!") speaks as a **nurturing Parent** — which is what made Microsoft Bob and Clippy feel patronizing to competent users.
- Most professional tools should aim for **Adult→Adult**: state what happened, state the options, respect the user's competence.
- **Natural Child** is the right register for games and playful products — which links to [Hedonics](05-Hedonics.md).

## 3. Remote conversations and social media

Much research has gone into supporting conversation "at a distance," producing email, videoconferencing, videophones, instant messaging and chatrooms. The lecture's framing question: **do they mimic, or move beyond, existing ways of conversing?** (The historical videophone slide makes the point that decades of designs simply tried to reproduce a face across a wire, whereas today's multi-screen telepresence rooms go further.)

For social media conversations specifically, the lecture asks:
- Do the **same conversational rules** apply?
- Are there **more breakdowns**?
- **How do people repair them** — and does the repair strategy differ for phone, email, instant messaging, texting, and video calls?

This is a strong exam angle: repair on the phone is immediate and verbal ("sorry, say again?"); in email it costs a whole round-trip and often a re-read of the thread; in texting it produces the familiar follow-up correction message; on video it is complicated by lag, which destroys turn-taking because the usual timing cues no longer line up.

## 4. Tele-presence

**Telepresence** = technology that makes a person feel present in another physical location (and appear present to the people there).

**Hypermirror (Morikawa & Maesako, 1998)** — the lecture's key case. People in physically different rooms are **superimposed onto the same screen** so they appear to occupy one shared virtual space. The revealing part is what the participants then did spontaneously:

1. Everyone appears together in one "virtual room."
2. Two people who were physically in the same room ended up appearing to stand **on top of** the woman in the other room — **invading her virtual personal space**.
3. Noticing this, the two **moved physically apart** to give her more **virtual** personal space — and everyone was comfortable again.

The lesson: **real-world social norms (like personal space) carry straight over into virtual space**, and people will adapt their physical behavior to repair a virtual social violation — even though nobody was ever physically close to anyone.

Related textbook distinction worth keeping straight:
- **Telepresence** — one party projected into another's *physical* space (telepresence robot, videoconference room).
- **Social presence** — the degree of awareness of, feeling for, and reaction to *other people* who are virtually present (e.g. avatars in VR). Still limited today by cartoon-like facial expressions and skin tone.

## 5. Co-presence

**Co-presence** = supporting people who *are* in the same physical space to collaborate better — via shared/multi-user technologies (Smartboards, interactive tabletops and surfaces, gesture recognition). The design task is to understand the coordination and awareness mechanisms people already use face-to-face, then see how the technology adapts or replaces them.

**Sococo** — the lecture's example of awareness at a distance: a **virtual office floor plan** showing *who is where and who is meeting with whom*. Rather than mimicking a conversation, it recreates the ambient awareness you get from walking past someone's open office door.

## 6. Shareable technologies

Technologies explicitly designed for more than one person to use at once (multitouch tables, shared displays, smart speakers). The textbook's observation is that **physical placement carries social meaning**: a smart speaker on a kitchen counter affords joint, family ownership and use — like the old radio or TV — whereas the same assistant on a personal phone affords solo use.

## Lecture summary (the deck's own closing slide)

- **Social mechanisms** — turn-taking, conventions, etc. — are what enable us to collaborate and coordinate our activities.
- **Keeping aware of what others are doing, and letting others know what you are doing**, are important aspects of collaborative working and socialising. *(This "awareness" theme is the thread linking Hypermirror, Sococo and co-presence technologies.)*
- Many technology systems have been built to support **telepresence and co-presence**.

## Class exercise (UXU 3)

Take the interactive recipe app from the Cognition lecture and **make it social**:
- Divide tasks among different people
- Announce that dinner is ready
- Send a shopping list
- Ask for comments or changes

Then **test the system**, per the lecture's checklist:
1. **Specify your target** (who is this for?)
2. **Set the situation** — are friends gathered? where? how many? when? how long?
3. **Prepare the test**
4. As testers: **perform the test as specified**
5. **Give feedback and suggestions for improvements**

This mirrors the general design cycle in [Interaction Design](06-Interaction-Design.md) and feeds directly into [Usability Testing](07-Usability-Testing.md).

## Key exam talking points

- Name the social mechanisms (turn-taking, back-channelling, repair) and show what goes wrong when technology strips them out — video-call lag destroying turn-taking is the cleanest example.
- Explain **Transactional Analysis** (Parent nurturing/controlling – Adult – Child adapted/natural) and apply it to an interface's tone of voice; connect controlling-Parent error messages to annoying interfaces.
- Tell the **Hypermirror** personal-space story — it's the single best illustration that social norms transfer into virtual space.
- Distinguish **telepresence / social presence / co-presence** with one example each (telepresence room · VR avatars · Smartboard or Sococo).
- Use **awareness** as the unifying concept: most social technology is really about knowing what others are doing and signalling what you are doing.
