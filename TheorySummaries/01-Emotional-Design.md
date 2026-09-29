# Emotional Design

*Sources: **UXU 4 – Emotional Design** lecture (17 Sep 2026); **Donald A. Norman, _Emotional Design: Why We Love (or Hate) Everyday Things_ (Basic Books, 2004)** — now in `CourseMaterial`; Preece, Sharp & Rogers Ch.6 "Emotional Interaction".*

## Why emotion matters in UX

Course knowledge goals: *"Explain how sensed elements (colors, typography, imagery) evoke emotions"* and *"Explain emotional design using a 3 layer model."*

Norman's central claim: **everything we do has both a cognitive and an affective component** — cognition assigns *meaning*, affect assigns *value*. You cannot escape affect; it is always there, and the affective state changes how we think.

## The 3-level model (Norman)

The lecture presents it as a processing architecture, not just three labels:

```
                          ┌─────────────┐
                          │ REFLECTIVE  │  conscious thought, meaning,
                          │             │  self-image, cultural interpretation
                          └──────┬──────┘
                                 │ control
   Sensory input ──────►  ┌──────┴──────┐
   (see, hear, touch,     │ BEHAVIORAL  │  learned skills, routines,     ──►  Motor output
    taste, smell)         │             │  performance                        (actions and
                          └──────┬──────┘                                      responses)
                                 │ control
                     ──────►  ┌──┴──────────┐
                              │  VISCERAL   │  automatic, immediate        ──►
                              │             │  reactions (appearance,
                              └─────────────┘   feel, sound)
```

Key structural points from the lecture slide:
- **Sensory input feeds both the visceral and behavioral levels directly** — visceral reaction happens before/without conscious thought.
- **Control flows downward**: reflective controls behavioral, behavioral controls visceral. (Which is why you *can* consciously override a gut reaction — but it takes effort.)
- **Only behavioral and visceral produce motor output** — the reflective level doesn't act directly; it acts *through* the lower levels.

### The three levels

| Level | Lecture bullets | Norman's short definition |
|---|---|---|
| **Visceral** | Immediate emotional impact (touch and feel) · gets us excited or curious · attraction | *"Visceral design concerns itself with appearances"* — initial impact, look, touch, feel |
| **Behavioral** | Function comes first · understand how users will **use** the system | *"Behavioral design has to do with the pleasure and effectiveness of use"* — function, performance, usability |
| **Reflective** | Message · culture · meaning of the product · self image | *"Reflective design considers the rationalization and intellectualization of a product. Can I tell a story about it? Does it appeal to my self-image, to my pride?"* — self-image, personal satisfaction, memories |

The visceral level is pre-conscious, pre-thought — it works by **pattern matching**, is incapable of reasoning or comparing against past experience, and is genetically tuned (things that historically meant food, warmth, or protection produce positive affect). The behavioral level is where function, performance and usability live — "nobody is ever against usability." The reflective level is where story, brand, culture and pride live.

**Classic example (textbook):** a Swatch watch — wild colors grab attention at the visceral level, its affordances work at the behavioral level, and its cultural imagery/identity appeal works at the reflective level.

**Norman's own opening example — Three Teapots:** Carelman's "coffeepot for masochists" (handle on the same side as the spout — deliberately unusable, but a wonderful *story*, so it wins reflectively), the Nanna teapot (squat, chubby, charming — visceral), and the Ronnefeldt tilting teapot (a clever brewing mechanism — behavioral). One collection, three levels.

## "Attractive Things Work Better"

Norman's chapter 1, and the key empirical result behind emotional design:

- **Kurosu & Kashimura (1995)** tested ATM layouts that were *identical in function and number of buttons*, differing only in how attractively the controls and screens were arranged. The attractive ones were **perceived as easier to use**.
- **Tractinsky (1997; Tractinsky, Katz & Ikar, 2000)** was suspicious — he assumed aesthetic preference was culturally specific to Japan and that usability and aesthetics "were not expected to correlate." He translated the layouts into Hebrew and re-ran the study with rigorous controls in Israel. He not only replicated the result — it was **stronger** than in Japan.

**The mechanism** — why aesthetics changes usability:
- **Negative affect** (anxiety, feeling endangered) makes neurotransmitters **narrow and focus** brain processing: concentration on details, depth over breadth. Good for survival and for dealing with danger — "you see the trees before the forest."
- **Positive affect** **broadens** processing: muscles relax, curiosity is aroused, creativity is engaged, the brain becomes an effective learning organism — "you see the forest rather than the trees," and you become far more tolerant of minor problems and interruptions.

**Design implications Norman draws from this:**
1. A relaxed, happy user is **more creative and more able to overlook minor flaws** — "designers can get away with more if the product is fun and enjoyable."
2. Conversely, **anything used under stress needs much more care**: all required information continually at hand, readily visible, with clear unambiguous feedback. (Think control rooms, emergency systems — not the place for playful ambiguity.)
3. It also applies to the design *process*: brainstorming warms up with jokes and games and bans criticism precisely because creative thinking needs the relaxed state that positive affect produces.

## Expressive interfaces

Interfaces that communicate state or "feeling" expressively — the lecture's examples:
- The Windows **blue screen of death** with its `:(` sad face — an attempt to soften a catastrophic failure with an emotional signal.
- The **Skype error dialog** ("Skype has encountered a problem and needs to close. We are sorry for the inconvenience") — apologetic phrasing over a Debug/Close choice that most users can't act on.
- A **baby monitor** presenting status as expressive cards with faces and color coding: *"Austin is sleeping"* (calm teal), *"Loud Environment"* (amber warning), *"Unusually High Temperature"* (red alert), *"Austin is awake and upset"* (an unhappy face). Emotion is used here as an information channel — color and facial expression convey urgency faster than text alone.

This is also where **sensed elements evoke emotion** in practice:
- **Color** — mood, brand, urgency/safety coding (visceral, immediate).
- **Typography** — perceived formality, friendliness, trustworthiness; poor legibility creates frustration.
- **Imagery** — cultural symbols work reflectively (meaning); raw visual polish works viscerally.

## Annoying interfaces

Interfaces that *inadvertently* produce negative emotion — frustration, anger, feeling stupid or patronized. The lecture's example is **Microsoft Bob** (the cartoon living-room metaphor with the dog assistant), joined in the textbook by **Clippy** and IKEA's **Anna**. All tried to manufacture friendliness at the visceral level without a genuinely useful behavioral layer behind it — users read the mismatch as cute, childish, or intrusive.

Common triggers for negative emotional response (textbook):
- The app doesn't work properly or crashes
- The system doesn't do what the user wants
- Expectations are not met
- Insufficient information about what to do next
- Vague or obtuse error messages
- An appearance that is noisy, garish, gimmicky, or patronizing

## Persuasive — and deceptive — technologies

The lecture makes this a deliberate pair:
- **Persuasive technology** — design that nudges behavior, e.g. the **HAPIfork** (a smart fork that vibrates when you eat too fast), fitness trackers, habit apps.
- **Persuasive (deceptive) technology** — the same emotional/psychological levers used *against* the user: phishing emails, "Nigerian prince" scams, authentic-looking fake bank letters, dark patterns.

This is the course's ethics hook (*"Discuss ethical considerations in UX design"*): the techniques are identical; only the intent differs. See also [Authenticity](04-Authenticity.md).

## Anthropomorphism and zoomorphism

- **Anthropomorphism** — attributing **human qualities to animals or objects**. Lecture example: the CafeX robot-arm barista; textbook examples: Clippy, Anna, voice assistants. Powerful for engagement, risky when it over-promises or grates.
- **Zoomorphism** — giving an object the **shape/form of an animal**. (Think the Alessi "Juicy Salif" bird/spider-like citrus squeezer from the intro lecture, robot pets like AIBO, animal-shaped devices.)

Both work primarily at the visceral level (instant recognition, instant reaction) but carry reflective baggage — what does owning/using this say about me?

## Class exercise (UXU 4)

Design a **language-learning app** (or apply this to your own course assignment):
1. Briefly study existing apps.
2. Briefly define a user (**persona**).
3. Design + prototype the new app considering each layer explicitly: **Visceral Design / Behavioral Design / Reflective Design**.
4. **Peer review** your design with another group, explaining the emotional design.

This is the most likely bridge between this topic and your exam assignment — be able to walk through your own design one layer at a time.

## Key exam talking points

- Draw the 3-level model **with** sensory input, motor output and the downward control arrows — not just three boxes — and map a real product onto all three levels.
- Explain *why* attractive things work better: the Kurosu & Kashimura / Tractinsky ATM studies plus the affect→cognition mechanism (positive affect broadens and makes users tolerant; negative affect narrows and makes them rigid).
- Use Bob/Clippy to explain what happens when visceral charm isn't backed by behavioral substance.
- Distinguish anthropomorphism from zoomorphism with an example of each.
- Be ready to discuss the persuasive/deceptive boundary as an ethics question.
- Connect to [Hedonics](05-Hedonics.md) (pleasure/stimulation) and [Authenticity](04-Authenticity.md) (earned vs. manufactured emotional appeal).
