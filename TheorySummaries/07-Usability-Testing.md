# Usability Testing (incl. Think Aloud & Biometrics)

*Sources:*
- ***UXU 5 – Usability testing I*** *(NeuroLab, user-centred approach, Think Aloud intro)*
- ***UXU 6 – Usability testing using Think Aloud*** *(4 Oct 2026)*
- ***Guest lecture: "Neuromarketing – Usability testing using biometric research methods and the iMotions platform"***, *Tine Juhl, VIA NeuroLab*
- ***Olmsted-Hawala, Murphy, Hawala & Ashenfelter (2010)***, *"Think-Aloud Protocols: A Comparison of Three Think-Aloud Protocols for use in Testing Data-Dissemination Web Sites for Usability", CHI 2010*
- ***Kjeldskov, Skov & Stage (2004)***, *"Instant Data Analysis: Conducting Usability Evaluations in a Day", NordiCHI 2004*
- *Preece, Sharp & Rogers Ch.8 "Data Gathering" and Ch.14–16 "Evaluation"*

*Note: the UXU 5 deck carries last year's dates (29 Sep 2025, assignment deadline "28 November 2025") and the guest-lecture slides are dated 23 Oct 2024, so these are reused decks. **Check WISEflow for this year's actual assignment deadline** rather than trusting the slide.*

## What usability testing is

Usability testing measures how well real users can use a product to achieve real tasks. It's one part of the broader discipline of **evaluation**, which also includes inspection methods (heuristic evaluation, walkthroughs) and analytics (A/B testing) — but usability testing specifically centers on **watching people use the thing**.

**Standard measures:** *accuracy* (did they complete the task correctly?), *efficiency* (time on task), errors, and *subjective satisfaction* via questionnaires and interviews.

## Why we test: the user-centred approach

UXU 5 frames testing within the course assignment's requirement to *"include needed disciplines within UX using a **user centered approach**."* That approach rests on three principles (originally Gould & Lewis, 1985):

1. **Early focus on users and tasks** — directly study users' cognitive, behavioral, anthropomorphic and attitudinal characteristics.
2. **Empirical measurement** — users' reactions and performance with scenarios, manuals, simulations and prototypes are *observed, recorded and analysed*.
3. **Iterative design** — when problems are found in user testing, fix them and **test again**.

Usability testing is how principles 2 and 3 actually happen. A user-centred project that tests only once at the end isn't really user-centred.

## The 5 key issues in data gathering

UXU 6's planning checklist — *"have this in mind when you plan the test"*:

1. **Setting goals** — why are you testing at all? The goal determines everything downstream. Lecture example: *"The purpose is to see how students find information on MyVia"* → therefore the test is a set of small tasks on MyVia.
2. **Identifying participants** — who, and *one or more at a time?* (Individuals need prompting to verbalise; pairs/co-discovery talk to each other naturally.)
3. **Relationship with participants** — see the ethics points below.
4. **Triangulation** — don't rely on a single data source or method. Combine observation + think-aloud + task outcomes + questionnaires — and, where available, biometrics (see below) — so findings corroborate one another.
5. **Pilot studies** — run the test on someone first. Tasks that read clearly on paper routinely turn out ambiguous, impossible, or far too long. Olmsted-Hawala et al. also included a **practice session** before every real session so participants could get used to thinking aloud.

## Settings: controlled vs. natural

Directly matches the course competency goal *"Compare different settings in usability testing."*

- **Controlled** — the classic **usability lab**: a *participant side* (desk, computer, camera) and an *observer side* behind a one-way/sliding glass door with camera controls, plus an extra observer area. VIA's **NeuroLab** is the course's own controlled setting (UXU 5 agenda: *"NeuroLab testing (controlled settings)"*). The Olmsted-Hawala study was likewise run in the US Census Bureau's usability lab. Controlled settings let you hold conditions constant and compare variables — an **experiment** manipulates an independent variable and measures dependent ones. Rigorous, but artificial: people behave differently when they know they're in a lab.
- **Natural** — testing where people actually are (homes, workplaces, campus, "in the wild"). Ecologically valid, surfaces real context and unexpected use — but messy and harder to control. The UXU 5/6 exercises were run this way: students testing students on MyVia around campus.
- **In between**: mobile "lab-in-a-box" kits and **living labs** (real environments permanently instrumented). Eye-tracking *glasses* are what let biometric testing leave the lab.

## Think Aloud

**Think Aloud (TA)** = the participant verbalises their thoughts while performing the task, so the evaluator hears *why* they do what they do, not just what they click. Usability practitioners use it because they *cannot directly observe what a user is thinking*. The common form is **concurrent** TA — talking *while* working, as opposed to retrospectively afterwards.

### The four ways — as precisely defined in Olmsted-Hawala et al. (2010)

The lecture's "Think Aloud in 4 ways" is taken directly from this paper's experimental conditions:

| Variant | Origin | What the moderator does |
|---|---|---|
| **Traditional** | Ericsson & Simon | No probing beyond *"keep talking"* — and only after **15 seconds of silence**. Practice session first. |
| **Speech communication** | Boren & Ramey (2000) | Gives **back-channel** feedback ("um-hum") to show active listening; after 15 s of silence, **echoes the participant's last word** with a questioning tone — participant: *"that was odd…"*, moderator: *"Odd?"* |
| **Coaching** | Dumas & Redish's "active intervention" | Asks direct questions about areas where the user is pausing or confused, and **gives help when they struggle**. |
| **Silence** | (the experiment's control) | No thinking aloud, no probing, no prompting. |

The UXU 6 deck's examples ("Why did you click that button? What are you wondering about?") lean towards active probing; note that in the paper, speech communication is *much* subtler than that — mostly "um-hum" and echoing. Direct questions about the interface are closer to **coaching**.

**Why speech communication exists:** speech-communication theory holds that in natural conversation the listener constantly signals engagement through back channels. A moderator who sits in total silence, interrupting only with "keep talking", is *unnatural* — like a phone call where the other person goes quiet and you ask "hello, are you still there?" This is the same **back-channelling** mechanism from the Social Interaction lecture (see [Social Interaction](03-Social-Interaction.md)).

### What the experiment found

80 participants, randomly pre-assigned to one of the four conditions (20 each), double-blind, eight simple "find" tasks on census.gov, sessions video-coded by independent coders who didn't know the hypotheses. Satisfaction measured with a shortened **QUIS** questionnaire (16 items, total 16–112).

| Condition | Accuracy (tasks correct) | Time on task (mean, s) | Satisfaction (QUIS, 16–112) |
|---|---|---|---|
| Traditional | 40% | 243 | 73 |
| Speech communication | 30% | 270 | 73 |
| **Coaching** | **60%** | 268 | **85** |
| Silent control | 31% | 252 | 78 |

**Conclusions — the exam-relevant part:**

1. **Coaching significantly inflates accuracy and satisfaction.** That sounds good but is a **bias**: results are skewed towards better performance than the user would achieve alone. *If you want to know how users perform "in the field", don't coach.*
2. **Traditional and speech communication don't differ significantly** in accuracy or satisfaction — so a practitioner can pick either and still get results that reflect unaided use.
3. **Thinking aloud did not significantly change time on task** in this study — so it's legitimate to collect efficiency measures during a TA test. (The literature is mixed: Hertzum et al. and Rhenius & Deffner found TA tasks took *longer*; Wright & Converse found them *faster*. Mention that it's contested.)

**Choosing a variant follows from issue #1, setting goals:**
- Want realistic performance data? → **Traditional** or **speech communication**.
- Want to learn *what help people need* and get past blockers to test later parts of the flow? → **Coaching** — but never report its success rates as real-world success rates.
- Want the cleanest behavioral/timing baseline, or using biometrics where speech would interfere? → **Silence**.

## Biometric testing — VIA's NeuroLab

The guest lecture by Tine Juhl (NeuroLab coordinator) asks: *how do people experience our app or website — **visually and emotionally**?*

### Three types of research methods

| Type | Data | Examples |
|---|---|---|
| **Analytics methods** | Secondary | Insights from digital sources: Meta, Google, etc. |
| **Traditional "asking" methods** | Primary | Questionnaires, **Think Aloud tests**, focus groups |
| **Biometric methods** | Primary | **Eye tracking** (on-screen, glasses, VR), **facial expression analysis**, **galvanic skin response** (GSR — sensors on the fingers), **EEG** (sensors on the scalp) |

Note that **Think Aloud is classed as an "asking" method** — it relies on what the person chooses and is able to say.

The lab uses the **iMotions** platform, which puts data from several sensors on **one shared timeline**, with validated algorithms, visualisation and quantification — so you can see e.g. that a frown occurred at the moment the user's gaze reached a particular button.

### What each kind of method can uncover

**Asking methods** reveal:
1. What the person *remembers clearly* from the experience
2. Their *strong and conscious* emotions
3. **Underlying reasons — why** they believe (or want us to believe) they prefer something or behaved a certain way

**Biometric methods** reveal:
1. How the person *actually reacted during* the experience
2. Their **sub-conscious** experience — which emotions, and how intense
3. What attracted **visual attention** — what they saw and *didn't* see, what they looked at most, for how long, in which order

### Limitations of each

**Asking methods:**
1. The person may not be 100% honest, articulate, or have a perfect memory
2. **Bias** — they may say or do things to please or impress us, or avoid looking bad
3. They can't express **micro-emotions** (e.g. slight frustration)

**Biometric methods:**
1. Expertise is needed — both to run the research and to analyse the data
2. Hardware and software are needed
3. **They can't uncover *why*** the person reacted as they did (though eye tracking can give hints)

### The iceberg — the key idea

Asking methods capture what's **visible on the surface**: *conscious* behaviour. Biometric methods capture what's **under the surface**: the otherwise invisible, *unconscious* behaviour.

The limitations mirror each other exactly — biometrics give **what and how intense** but not **why**; asking gives **why** but is filtered through memory, honesty and articulacy. That's the strongest argument for **triangulation**: combine Think Aloud with eye tracking and you get both. It also links to [Cognition](02-Cognition.md) (System 1 reactions are largely unconscious, so users literally can't report them) and [Emotional Design](01-Emotional-Design.md) (visceral reactions happen before conscious thought — biometrics are one of the few ways to measure the visceral level directly).

### Eye-tracking outputs

- **Heatmaps** — aggregate where attention landed across participants.
- **AOIs (Areas of Interest)** — regions you define in advance, so you can measure e.g. *which element was seen first* (time to first fixation) and *which was looked at longest* (dwell time).

### Example studies from the lecture

- **Chocolate "shop" test** — eye tracking on a shelf display. The heatmap showed the *lowest shelf* got the most attention, and AOI metrics distinguished the shelf seen *first* from the shelf looked at *longest* — not necessarily the same one.
- **UX test of a website's floor-plan filtration tool** (Juhl's MA dissertation, 2020) — eye tracking + facial expression analysis. Objectives: engage and keep customer attention, make it easier to navigate many floor plans. Findings: the tool was effectively **"invisible"** and the page hard to find. Users who **found and used** it showed *less* negative emotion/frustration and spent *longer* on the page; users who didn't showed *more* frustration and left sooner. Eye tracking answered *did they see it?*; facial expression answered *how did that feel?*
- **Terms & Conditions** — the Danish Competition and Consumer Authority used facial expression analysis ("brow furrow") to study whether people actually read T&Cs.
- **MythBusters, hands-free vs. handheld phone while driving** — eye tracking in a driving simulator; a nice link to the attention/multitasking material in [Cognition](02-Cognition.md).

## Data recording

Three levels, in increasing richness and cost:

- **Notes and pictures** — cheapest, immediate, but selective.
- **Sound** — captures everything said, including tone and hesitation.
- **Video** — the fullest record, but expensive to analyse. In the Kjeldskov study a full video analysis of just five sessions took **~40 man-hours**.

## Analysing the results: Instant Data Analysis

Kjeldskov, Skov & Stage (2004) — from the Danish Aalborg University HCI group — developed **Instant Data Analysis (IDA)** to make it possible to **conduct, analyse and report a usability evaluation in one day**. It is the natural partner to a Think Aloud test:

- **4–6 think-aloud sessions** in a day.
- Roles: a **test monitor** (runs the sessions), a **data logger** (writes down incidents/problems during the sessions), and a **facilitator** (runs the analysis).
- Straight after the sessions: a **1-hour brainstorm** where the test monitor and data logger articulate the most critical problems and rate severity (**critical / serious / cosmetic**), aided by printed screenshots and the logger's notes. The facilitator writes problems on a **whiteboard**, asks clarifying questions, groups them into themes and removes duplicates.
- The facilitator then spends **1–1½ hours** writing up a ranked problem list; finally all three run through it together to reach **consensus**.

Results vs. full video analysis on a hospital booking system: IDA found **85% of the critical** problems (11 of 13) and **68% of the serious** ones, in **~10% of the time** (4 vs. 40 man-hours). It also **filtered out noise** — most problems found only by video analysis were experienced by just one test subject — and tended to surface higher-level design problems rather than many instances of the same issue.

See [Instant Data Analysis](09-Instant-Data-Analysis.md) for the full topic.

## Running the test — roles and ethics

**Roles (from the in-class exercise):** **groups of 2** — one **test person** and one **moderator (the tester)**. With three people, add a **data logger**, matching the IDA setup above.

**Relationship with the participant** — the lecture's three rules, which are also the course's ethics content:

1. **Make sure it is OK to conduct the test** — informed consent, including consent to record (Olmsted-Hawala's participants signed a consent form before every session).
2. **Explain the purpose of the test** — and make it explicit that *the system is being tested, not the participant*. Participants who feel judged go quiet and blame themselves.
3. **Thank your participant afterwards** — and debrief them if anything was withheld. (Olmsted-Hawala's participants were told they were evaluating the website when the real subject was the TA protocol itself — a legitimate deception only because the purpose was disclosed afterwards.)

## Writing good test tasks

Each lecture task is a **realistic goal to achieve**, verifiable, small, and phrased *without telling the user which UI elements to use*:

- **MyVia task set 1:** find the photographer in tomorrow's "Wonders in the Shadows"; find the last day of tuition this semester; can you get special exam conditions with a broken leg?
- **MyVia task set 2:** find your student counsellor's name and contact info; how many minutes is the UXU1 exam? how can you join the Drama Community?
- **Colourbox task:** find Colourbox on MyVia (the access key is on the exercise slide), create an account, and download a picture of virtual reality without a watermark.
- **Extra test — IKEA "Billie" chatbot:** IKEA wants to know how customers find information *beyond* product info using the chatbot. Enter the IKEA website, open the chat in the bottom-right corner, and find the guarantee period for the SINNERLIG pendant lamp.

Olmsted-Hawala et al. add two good practices: tasks were drawn from **what real users actually search for** (search logs, FAQ queries, usage statistics), and **task order was randomised** to control for learning effects.

## Good practice summary

- Start from a **user-centred** stance: test early, measure empirically, iterate.
- Match the setting and the think-aloud variant to your stated goal — decide *before* writing tasks.
- **Don't coach if you want realistic success rates.**
- **Triangulate**: asking methods for *why*, biometrics for *what and how intense*, task outcomes for *how well*.
- **Always pilot**, and give participants a practice round of thinking aloud.
- Phrase tasks as goals, base them on real user needs, and randomise their order.
- Record at the lowest richness that answers your question — and consider IDA instead of full video analysis.

## Key exam talking points

- Explain the **user-centred approach** (early focus, empirical measurement, iterative design) and where usability testing fits in it.
- Name and contrast the **four think-aloud variants** with their precise definitions, and cite the **Olmsted-Hawala** result: coaching inflates accuracy (60% vs. 30–40%) and satisfaction, so it biases results; traditional ≈ speech communication; time on task unaffected (but contested in the literature).
- Explain the **asking vs. biometric** distinction, the **iceberg**, and why each method's weakness is the other's strength — then argue for triangulation.
- Name the biometric tools (**eye tracking, facial expression analysis, GSR, EEG**) and eye-tracking outputs (**heatmaps, AOIs**); use the filtration-tool study as your example.
- Compare **controlled vs. natural** settings (NeuroLab vs. the MyVia-around-campus exercise).
- Walk through the **5 key issues in data gathering** as a test plan for your own course assignment.
- Describe how you'd analyse the results with **IDA**, citing 85% of critical problems in 10% of the time.
- Link to [Wizard of Oz Testing](08-Wizard-of-Oz-Testing.md) (testing a system that doesn't exist yet).
