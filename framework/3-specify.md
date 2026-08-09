# Specify — what correct means here

_The skill that unblocks stalled AI projects, and the one only the business can supply._

Stalled AI projects rarely stall on engineering. They stall because nobody wrote down what a correct answer looks like in terms a system could be built and tested against — and no engineer can supply that, because it is domain knowledge, not technical knowledge.

A usable specification answers three questions.

**What must always be true.** Not aspirations. Checkable statements: every item is assigned to exactly one category; monetary values are never inferred where the document does not state them.

**What must never happen.** Refusals matter more than capabilities, and they are the part people forget. The system should decline rather than guess when the input is unreadable, when the confidence is low, when the request falls outside scope.

**What is authoritative.** Which system, which document, which version — and, critically, what is stale or must not be used. This is domain knowledge acting as grounding strategy, and getting it wrong produces confident answers from the wrong source, which is the most expensive kind of error because it looks fine.

## The failure to watch for

A specification line that sounds precise but cannot be tested. "Handle correspondence appropriately" reads like a requirement and constrains nothing. The test is simple: could two reasonable people disagree about whether a given output satisfies it? If so, it is not yet a specification.

---

**Going further.** The programme takes people from a blank page to a completed one-page specification for their own process — acceptance criteria, refusals, ground truth and gate placement — reviewed against the failure modes that make specifications untestable. The review is what turns a plausible spec into a buildable one.

See [the enterprise programme](https://beta.syntropik.co/#programmes).
