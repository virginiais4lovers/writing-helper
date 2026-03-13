# Writing Helper

Claude Code skills that help you communicate more effectively using established communication frameworks.

Two modes: **coaching** (apply a framework to your draft right now) and **practice** (learn frameworks through deliberate exercises so you can apply them yourself).

## Quick Start

Clone this repo and open it with [Claude Code](https://claude.ai/claude-code):

```bash
git clone https://github.com/virginiais4lovers/writing-helper.git
cd writing-helper
claude
```

The skills are automatically available as slash commands.

## Coaching Skills

Apply a framework directly to a piece of writing you're working on:

| Skill | Framework | Best for |
|-------|-----------|----------|
| `/ladder-of-inference` | Chris Argyris' Ladder of Inference | Examining assumptions, making reasoning transparent |
| `/pyramid-principle` | Barbara Minto's Pyramid Principle | Structuring documents and presentations logically |
| `/scqa` | Situation-Complication-Question-Answer | Framing problems, writing proposals, creating buy-in |
| `/bluf` | Bottom Line Up Front | Making writing direct for busy/senior audiences |
| `/nvc` | Marshall Rosenberg's Nonviolent Communication | Feedback, disagreements, difficult conversations |

### Examples

```
/pyramid-principle Here's my draft email to the VP about the Q2 roadmap...
/nvc I need to give feedback to a teammate who keeps missing deadlines
/bluf [paste your draft]
/scqa I'm writing a proposal to switch our deployment process
/ladder-of-inference [paste an argument you're making]
```

Each skill analyzes your writing through the framework's lens, diagnoses specific issues, and suggests concrete revisions with before/after examples. If you invoke a skill without a draft, it guides you interactively.

## Practice Skill

Learn and internalize the frameworks through interactive exercises grounded in learning science:

```
/writing-practice pyramid
/writing-practice nvc
/writing-practice bluf
```

The practice skill uses evidence-based learning techniques adapted from Dr. Cat Hicks' [Learning Opportunities](https://github.com/DrCatHicks/learning-opportunities) framework (CC-BY-4.0). Instead of just applying frameworks *for* you, it builds genuine communication skill through:

- **Prediction** -- "What do you think the main issue is?" (then analyze together)
- **Generation** -- "Try rewriting this yourself first" (then compare)
- **Reflection** -- "What surprised you? What matched your intuition?"
- **Self-testing** -- "Explain this framework as if I'm a colleague who's never heard of it"

### Why practice matters

AI tools can rewrite your text to be clearer, but that creates a fluency illusion -- the polished output *feels* like understanding, but you may not be able to produce it yourself next time. The practice skill addresses this by making you do the thinking, with feedback that helps you improve.

## How Coaching and Practice Work Together

```
You have writing to improve
        |
        v
  Coaching Skill (/bluf, /pyramid-principle, etc.)
  Applies framework, suggests revisions
        |
        v
  "Want to practice what we just used?"
        |
        v
  Practice Skill (/writing-practice)
  Exercises build understanding of WHY the revisions work
        |
        v
  Next time: you apply the framework independently
```

- **Coaching skills** are for when you have real writing to improve *right now*
- **Practice skill** is for when you want to *learn* the frameworks so you can apply them yourself
- After a coaching session, use practice to reinforce why the changes worked
- After a practice exercise, use the coaching skill on real work to apply what you learned

## Framework Selection Guide

Not sure which framework to use?

| You're writing... | Use |
|-------------------|-----|
| A quick email or Slack message | `/bluf` |
| A long document or presentation | `/pyramid-principle` |
| A proposal that needs buy-in | `/scqa` |
| An argument that needs transparent reasoning | `/ladder-of-inference` |
| Feedback or a difficult conversation | `/nvc` |

Frameworks combine well: SCQA opening + Pyramid Principle body for proposals, NVC tone + BLUF structure for feedback that's both direct and empathetic.

## Project Structure

```
writing-helper/
├── .claude/skills/
│   ├── ladder-of-inference/SKILL.md      # Coaching: reasoning transparency
│   ├── pyramid-principle/SKILL.md        # Coaching: top-down structure
│   ├── scqa/SKILL.md                     # Coaching: narrative framing
│   ├── bluf/SKILL.md                     # Coaching: direct communication
│   ├── nvc/SKILL.md                      # Coaching: difficult conversations
│   └── writing-practice/                 # Practice: deliberate learning
│       ├── SKILL.md
│       └── resources/
│           └── PRINCIPLES.md             # Learning science foundation
├── images/                               # Mermaid-generated SVG diagrams
├── writing-helper-spec.ipynb             # Full spec & documentation
├── CLAUDE.md                             # Project instructions for Claude
└── README.md                             # This file
```

## Acknowledgments

### Communication Frameworks
- **Chris Argyris** -- Ladder of Inference
- **Barbara Minto** -- Pyramid Principle, SCQA
- **Marshall Rosenberg** -- Nonviolent Communication
- **U.S. Military / business writing tradition** -- BLUF

### Learning Science
- **Dr. Cat Hicks** -- [Learning Opportunities](https://github.com/DrCatHicks/learning-opportunities) framework and the learning science principles adapted here (CC-BY-4.0)
- The underlying research by Bjork, Dunlosky, Roediger, Karpicke, and others cited in [PRINCIPLES.md](.claude/skills/writing-practice/resources/PRINCIPLES.md)

## License

Learning science adaptations are based on work licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) by Dr. Cat Hicks.
