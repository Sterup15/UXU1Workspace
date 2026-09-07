# Cognition

*Source: UXU 2 – Cognitive Aspects lecture (7 Sep 2026); Preece, Sharp & Rogers Ch.4.*

## Definition

> Cognitions are mental processes that deal with knowledge, involving the acquisition, transformation, storage, retrieval, and use of information.

In practice: thinking, remembering, learning, daydreaming, decision-making, seeing, reading, talking, writing. UX design constantly interacts with these processes — a good interface reduces unnecessary cognitive work; a bad one fights the user's brain.

## Two systems of thinking (Kahneman)

- **System 1** — intuition & instinct: unconscious, fast, associative, "automatic pilot." Runs ~95% of the time.
- **System 2** — rational thinking: effortful, slow, logical, but also lazy and indecisive.
The "bat and ball" puzzle (bat + ball = 110 kr, bat costs 100 kr more than ball) is used in class to demonstrate how System 1 jumps to a plausible-but-wrong answer (10 kr) unless System 2 is engaged.

## Two kinds of cognition (Norman, 1993)

- **Experiential cognition** — perceiving, acting, and reacting to events *effectively and effortlessly* (driving, reading, discussing).
- **Reflective cognition** — thinking, comparing, deciding (learning, writing, tutorial/analytical work).
Good UX design usually wants to keep routine tasks in *experiential* mode and reserve *reflective* effort for where it actually adds value.

## Attention

Focus vs. multitasking — people are worse at true multitasking than they believe (e.g., texting while driving).

**Design implications:**
- Make information *salient* exactly when it needs attention at that stage of a task (color, ordering, spacing, underlining, sequencing, animation).
- Avoid cluttering the interface with too much information at once.
- Support effective switching and *returning* to an interrupted task.
- Spacing/grouping matters even at equal information density — Tullis (1987) found grouped hotel listings were searched ~40% faster (3.2s vs. 5.5s) than bunched ones; Weller (2004) found bordered grouping beat color-contrast grouping for search speed.

## Memory

- **Encoding** is the first stage: what gets attended to and how it's interpreted determines what gets remembered. The more something is actively processed (reflected on, discussed, practiced) rather than passively read/watched, the more likely it sticks.
- **Recognition vs. recall**: recall (retrieving a name from memory unaided, e.g., command-line interfaces) is much harder than recognition (picking from a visible list, e.g., browser history, autocomplete).
- **Short-term memory is limited** — hence "The Magical Number Seven, Plus or Minus Two" (Miller, 1956), the classic paper this lecture opens with.

**Design implications:**
- Don't overload users' memory with complicated procedures.
- Design for *recognition over recall* (menus, lists, visible options).
- Provide multiple ways to encode information to aid memory: categories, color, flagging, timestamps.
- Design interfaces that encourage exploration but also constrain/guide learners; dynamically link related concepts/representations to support learning complex material.

## Reading, speaking, listening

These differ in cognitive cost: many people *prefer* listening to reading; reading is often quicker than speaking/listening; listening takes less cognitive effort than reading or speaking; dyslexic users struggle specifically with written-word recognition.

**Design implications:** keep speech-based menus/instructions short; artificial speech needs clearer intonation than human speech to be understood; offer large-text options.

## External cognition / cognitive offloading

People routinely offload memory and computation onto the environment rather than doing it all "in the head":

- **Externalizing to reduce memory load**: diaries, reminders, to-do lists, sticky notes, marked emails — these remind us *that* we need to do something, *what* to do, and *when*.
- **Computational offloading**: using an external tool/representation to do part of the thinking for you (pen and paper, a calculator, Arabic vs. Roman numerals for multiplication — the representation itself changes how hard the task is).
- This connects to the textbook's three "external" approaches to cognition: **distributed cognition** (cognition spread across people, artifacts, and environment — e.g., the cockpit example: clearance is propagated from air traffic controller → pilot → altitude dial → captain, verbally, physically, and visually), **external cognition**, and **embodied cognition**.

## Mental models

Users build an internal model of how a system works, which guides how they use it. Good UX design helps people build *better* mental models via:
- Clear, simple instructions
- Contextual tutorials/guidance, help videos, chatbots
- **Transparency** — making the interface intuitive
- **Affordances** — signaling what actions are possible (swipe, click, select)

## Summary (from the lecture's own closing slide)

- Cognition = attention + memory + perception + learning, among other processes.
- Interface design strongly affects how well users perceive, attend, learn, and remember while doing tasks.
- Frameworks like mental models and external cognition explain *why* people interact with products the way they do — and point toward how to design better ones.

## Key exam talking points

- Explain System 1/2 and experiential/reflective cognition, and connect them: fast, automatic experiential use maps onto System 1; deliberate, comparative reflective use maps onto System 2.
- Give a concrete design implication for at least attention, memory, and mental models.
- Use the cockpit or popcorn-app exercise as an example of distributed cognition / cognitive offloading in a design.
