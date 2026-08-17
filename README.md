# The AI Assessment Framework for Enterprise Adoption

**Five assessments for adopting AI in an enterprise. Three altitudes. Decide well about AI.**

Most AI programmes do not fail on the technology. They fail because nobody could say whether the work should have been automated at all, what "correct" meant, or who was accountable when it was wrong.

This is the framework we use to answer those questions — distilled from production deployment, including an engagement processing 15,000 documents a month under regulatory conditions. Published openly, free to use and adapt.

**Read it on the web:** https://beta.syntropik.co/framework/

---

## The five assessments

| | Assessment | The question |
|---|---|---|
| 1 | **[Spot](framework/1-spot.md)** | Where does AI belong in this work at all? |
| 2 | **[Judge](framework/2-judge.md)** | AI, plain automation, or neither — and is it worth it? |
| 3 | **[Specify](framework/3-specify.md)** | What does "correct" mean here, and what must never happen? |
| 4 | **[Govern](framework/4-govern.md)** | What controls does this need, and who answers for it? |
| 5 | **[Improve](framework/5-improve.md)** | Is it working, and what is the evidence telling us? |

They are ordered because each depends on the last. You cannot specify what you have not judged worth doing, and you cannot govern what you have not specified.

## Three altitudes

The same five assessments are answered by different people at different heights, and the answers differ.

| | Leadership & governance | Business teams | Engineers |
|---|---|---|---|
| **Altitude** | The portfolio | Their own process | The system |
| **Spot** | Which functions are candidates at all | Which of my recurring work | Which behaviours a system must support |
| **Judge** | What each option costs, and what it risks | Whether it is worth it here | Whether the architecture earns its complexity |
| **Specify** | What standard we hold suppliers and teams to | What "correct" means in this process | Acceptance criteria and refusals, in code |
| **Govern** | What governance posture we require, and who is accountable | What controls the process needs, and who answers for it | How the controls are implemented — gate, audit, access, cost |
| **Improve** | Whether to continue, expand or stop | What the corrections are telling us | What the evidence says, in evals |

**This is the part most organisations miss.** Train one group and the programme stalls: the engineers can build but cannot decide what is worth building; the business waits to be consulted; leadership signs off on things it cannot evaluate. The rows are the framework. The columns are why training one team is not enough.

## Where it came from

Not a whiteboard. The shape that shipped on the engagement behind this was a governed workflow, not an autonomous agent: classify, match with a confidence score, route anything uncertain to human review. Deterministic functions beat model calls wherever reliability mattered.

The failures came from the awkward edge of ingestion — documents too long to process in one pass, scans with no extractable text, malformed files that stalled and quietly re-ran, spending money on each retry — not from the model, and not from the happy path.

And the decisive factor was a business team who were not technical. They defined what each class of document meant, decided what had to reach a human, ran the review queue, and corrected the output. Every correction was captured and became the data that improved the system. The engineers built to their calls.

## Using this

Free to use, quote, adapt and build on under [CC BY 4.0](LICENSE) — attribution appreciated, a link more so. If you adapt it for your own organisation, we would genuinely like to hear how.

**What this repository is not.** It is the reasoning, not the practice. The exercises, templates, rubrics, and the governed sandbox where people set a threshold and live with the consequences are part of [Syntropik's enterprise programme](https://beta.syntropik.co/#programmes). Everything here is complete on its own terms; it is not a substitute for doing it.

## Contributing

**Stage system.** The five assessments, their questions and their colours are fixed by design — treat any change to a name, question or colour as a breaking change to the framework, not a wording tweak. Open an issue to propose one.

Issues and pull requests welcome — particularly:

- Failure modes we have not named
- Places the framework does not fit your sector
- Corrections where we are simply wrong

## About

Built by [Syntropik](https://beta.syntropik.co), a UK company doing enterprise AI enablement — leadership briefings, business-team programmes, and hands-on engineering cohorts.

hello@syntropik.co.uk
