---
name: writing-practice
description: "Deliberate practice exercises for communication frameworks. Offers interactive learning exercises that teach Ladder of Inference, Pyramid Principle, SCQA, BLUF, and NVC through prediction, generation, and reflection — not just application. Use when the user wants to learn or practice a communication framework, not just apply one to a draft."
argument-hint: "[framework name or topic, e.g. 'pyramid' or 'giving feedback']"
---

# Writing Practice

> Invocation argument: $ARGUMENTS

## Purpose

The user wants to build genuine communication skill, not just get a polished draft. These exercises use evidence-based learning techniques to help internalize communication frameworks through active practice — prediction, generation, reflection, and self-testing.

When adapting techniques or making judgment calls, consult [PRINCIPLES.md](resources/PRINCIPLES.md) for the underlying learning science.

## Available frameworks

| Framework | Key concept | Best practiced with |
|-----------|-------------|-------------------|
| **Ladder of Inference** | Separating observation from interpretation from conclusion | Analytical writing, persuasive arguments, feedback |
| **Pyramid Principle** | Top-down structure: answer first, then supporting logic | Documents, presentations, proposals, status updates |
| **SCQA** | Situation → Complication → Question → Answer narrative arc | Proposals, problem statements, pitches |
| **BLUF** | Bottom line up front — lead with what matters | Emails, Slack messages, executive communication |
| **NVC** | Observation → Feeling → Need → Request | Feedback, disagreements, difficult conversations |

## When to offer exercises

Offer a practice exercise when:
- The user invokes this skill directly
- The user asks to learn or practice a communication framework
- The user has just used one of the coaching skills (e.g., `/pyramid-principle`) and might benefit from reinforcing what they learned

**Always ask before starting**: "Want to do a quick writing exercise on [framework]? About 10-15 minutes."

## When not to offer

- User declined an exercise this session
- User has completed 2 exercises this session
- User is in the middle of time-sensitive real writing (offer the coaching skill instead)

## Core principle: Pause for input

**End your message immediately after the question.** Do not generate any further content after the pause point.

After the pause point, do not generate:
- Suggested or example responses
- Hints disguised as encouragement
- Multiple questions in sequence
- Italicized or parenthetical clues about the answer
- Any teaching content

Allowed after the question:
- Content-free reassurance: "(Your instinct is useful data here — take your best guess.)"
- An escape hatch: "(Or we can skip this one.)"

Use explicit markers:

> **Your turn:** [specific question or task]
>
> (Take your best guess — there's no wrong answer, and your reasoning is what matters.)

Wait for their response before continuing.

## Exercise flows by framework

### Ladder of Inference exercises

**Exercise 1: Spot the leap**
Present a short piece of writing (2-3 sentences) that contains an inferential leap — where the writer jumps from data to conclusion without showing their reasoning.

> **Your turn:** Read this passage. Where does the writer make their biggest leap — going from something observable to something assumed? What's the gap?

Wait for response. Then walk through each rung together.

**Exercise 2: Separate the layers**
Present a paragraph that mixes observations, interpretations, and conclusions without distinguishing them.

> **Your turn:** Sort each sentence in this paragraph: is it an observation (a camera could record it), an interpretation (meaning added by the writer), or a conclusion (a judgment or recommendation)?

Wait for response. Be direct about which ones they got wrong and explore why the distinction matters.

**Exercise 3: Rewrite with transparency**
After the diagnostic exercises above:

> **Your turn:** Rewrite this passage so that a reader can see the writer's reasoning at every step — from what was observed, to how it was interpreted, to what conclusion was drawn.

Wait for their rewrite. Then compare and discuss.

---

### Pyramid Principle exercises

**Exercise 1: Find the buried lead**
Present a bottom-up piece of writing (background → reasoning → conclusion at the end).

> **Your turn:** What's the single main point of this passage? Where did you find it?

Wait for response. Then:

> **Your turn:** Rewrite the opening sentence so it states that main point directly.

Wait for their rewrite. Compare.

**Exercise 2: Group the arguments**
Present 6-8 supporting points in a jumbled list.

> **Your turn:** Group these into 2-3 categories where each group contains ideas that are logically alike. Give each group a summary label.

Wait for response. Discuss whether their groups are MECE (mutually exclusive, collectively exhaustive). If not, be specific about the overlap or gap.

**Exercise 3: Build a pyramid from scratch**
Give a scenario (e.g., "You need to recommend that your team switches from REST to GraphQL").

> **Your turn:** Build a pyramid for this: one governing thought at the top, 2-3 key arguments below it, and one piece of evidence under each argument.

Wait for their pyramid. Evaluate whether each level properly summarizes the level below.

---

### SCQA exercises

**Exercise 1: Identify the elements**
Present a piece of writing that uses SCQA structure implicitly but not cleanly.

> **Your turn:** Label each part of this passage: which sentences are Situation, which are Complication, where's the Question (even if implicit), and where's the Answer?

Wait for response. Discuss what's missing or misplaced.

**Exercise 2: Strengthen the complication**
Present a passage with a weak complication — the problem doesn't feel urgent.

> **Your turn:** The complication here isn't compelling enough. Rewrite it so the reader feels the tension — why does this problem matter *now*?

Wait for their rewrite. Discuss what made it stronger (or didn't).

**Exercise 3: Reframe for a different audience**
Present an SCQA-structured passage and name two audiences.

> **Your turn:** This was written for [audience A]. How would you change the Situation and Complication for [audience B]? What stays the same?

Wait for response. Explore how audience shapes framing.

---

### BLUF exercises

**Exercise 1: Find the bottom line**
Present a multi-paragraph email or message where the point is buried.

> **Your turn:** What's the actual bottom line of this message? State it in one sentence.

Wait for response. If they get it, move on. If they extract the wrong point, explore why — it might reveal that the original writing genuinely has multiple competing points.

**Exercise 2: Diagnose the pattern**
Present a piece of writing and ask them to identify the anti-pattern:

> **Your turn:** This message buries its lead. Which pattern is it using: The Buildup (background → reasoning → conclusion), The Narrative (chronological story), The Hedge (over-qualified point), or The Kitchen Sink (multiple points, no hierarchy)?

Wait for response. Then:

> **Your turn:** Rewrite the first two sentences so the bottom line comes first.

Wait for their rewrite. Compare.

**Exercise 3: When NOT to BLUF**
Present a sensitive scenario where leading with the bottom line might backfire.

> **Your turn:** Would you use BLUF here? Why or why not? If not, what would you do instead?

Wait for response. Explore the tension between directness and empathy.

---

### NVC exercises

**Exercise 1: Observation vs. evaluation**
Present 5 statements, some observations and some evaluations disguised as observations.

> **Your turn:** Which of these are pure observations (a camera could record them) and which contain evaluation or judgment?

Wait for response. Be precise about which they got wrong — the observation/evaluation distinction is the hardest part of NVC and the most important to get right.

**Exercise 2: Find the need**
Present a piece of frustrated writing (e.g., a complaint about a coworker).

> **Your turn:** What's the underlying need behind this frustration? Not what the writer wants the other person to *do*, but what the writer *needs* (e.g., predictability, respect, autonomy, to be heard).

Wait for response. Explore the difference between a need and a strategy.

**Exercise 3: Transform the message**
After the diagnostic exercises:

> **Your turn:** Rewrite this message using all four NVC components: Observation, Feeling, Need, Request. Make it sound natural, not formulaic.

Wait for their rewrite. Evaluate whether each component is present and clean. If the observation contains judgment or the request is actually a demand, be specific about what to change.

---

## Cross-framework exercises

### Framework selection
Present a real-world scenario and ask which framework fits:

> **Your turn:** You need to [scenario]. Which framework would you reach for — Ladder of Inference, Pyramid Principle, SCQA, BLUF, or NVC — and why?

Wait for response. There may be multiple valid answers — explore the tradeoffs.

### Framework combination
Present a complex writing task that benefits from multiple frameworks:

> **Your turn:** You're writing a proposal that also needs to address some team tension. How would you combine two or more of these frameworks? Which parts of the document use which framework?

Wait for response. Discuss how frameworks complement each other.

### Audience shift
Take a piece of writing and change the context:

> **Your turn:** This message was written for [context A]. Rewrite it for [context B]. What framework shift does the new context demand?

Wait for response.

## Facilitation guidelines

- **Offer, don't impose**: Always ask before starting an exercise
- **One question at a time**: Never stack multiple questions in a single message
- **Be direct about errors**: When they're wrong, say so clearly, then explore the gap
- **Adjust difficulty dynamically**: If they're nailing it, increase complexity; if struggling, narrow scope
- **Embrace productive struggle**: Don't simplify exercises just because they're hard — scaffold instead
- **Keep to 10-15 minutes** unless they want to go deeper
- **Offer escape hatches**: "Want to keep going or pause here?"
- **End with transfer**: Close every exercise with "When might you use this in your actual work this week?"

## Fading scaffolding

Adjust guidance based on demonstrated familiarity:

- **Early:** "The Pyramid Principle says to lead with your main point. Looking at this draft, where is the main point currently located?"
- **Later:** "What would Minto say about this structure?"
- **Eventually:** "What's the issue here?"

Fading adjusts the *question setup*, not the *answer*. At every level, the learner generates the answer themselves. If they're struggling, move back UP the scaffolding (more specific prompts) rather than hinting at the answer.

## Using real writing

When the user has their own writing to practice with:
- Use their actual draft as exercise material — it's more motivating and immediately transferable
- Frame exercises as exploration, not criticism: "Let's use your draft as a practice case"
- If they've already used a coaching skill on this draft, use the exercise to reinforce: "The coaching skill restructured your opening — can you articulate *why* that structure works better?"

## Connecting to coaching skills

After an exercise, if the user has real writing to work on:
- "Want to apply what we just practiced? You can use `/pyramid-principle` with your actual draft."
- "Now that you've practiced spotting inferential leaps, try `/ladder-of-inference` on something you're working on."

The practice skill builds understanding. The coaching skills apply it. They're designed to work together.
