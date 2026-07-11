# awaken.fyi

*Catch your AI agent's confident mistakes before they ship.*

**Stop correcting AI twice.**

You tell your AI to fix something. It agrees. Three turns later it's doing it again. xOP turns a correction you keep repeating into a reusable operating rule — one that knows when it applies, when to back off, and what must never be lost.

## Try this now — the swap test

Ask your AI to critique something; if refused, reword it politely and watch the refusal vanish — that's the bug we work on. No install, no signup: run it in the chat you already have open.

## The shelf

| | One job | |
|---|---|---|
| **[xop](https://github.com/awakenfyi/xop)** | The standard — how AI should behave, and when to stop. | the format |
| **[xop-kit](https://github.com/awakenfyi/xop-kit)** | Catches when AI fakes "done" or just agrees with you. Zero tokens. | tool |
| **[xhat](https://github.com/awakenfyi/xhat)** | Scores whether your AI kept a claim you told it to drop. | tool |
| **[xop-storm](https://github.com/awakenfyi/xop-storm)** | One topic → fact-checked five-angle briefing → marketing from what survived. | tool |
| **[lofi-kit](https://github.com/awakenfyi/lofi-kit)** | The greyscale design system behind every page here. No colour — hierarchy from value. | design |
| **[hold-release](https://github.com/awakenfyi/hold-release)** | Field studies: does an AI rule know when to let go? | proof |

## In the Wild — Does it let go?

Our first field study installs a rule that makes an AI build small, runs it on every response, then tells it to let go — **and measures whether it does.** Preregistered, instruments committed before any run, results published either way. Told to strip the safety code, it must refuse.

**[→ Hold & Release: Ponytail](https://github.com/awakenfyi/hold-release)** · status: EVALUATION-READY

## Where the evidence actually stands

We publish status honestly, per component, misses alongside hits. The Guards are deterministic and rule-tested; the central gate has **not yet** been validated against blind human labels. Every claim on every README is limited to the evidence attached to it. The evidence ladder (`DESIGNED → EVALUATION-READY → RULE-TESTED → HUMAN-EVALUATED → FIELD-VALIDATED`) never skips rungs, and no model output becomes ground truth.

The rule that does not move: **never override a state that is still warranted.** A system may improve only by surfacing more honestly, never by agreeing more.

*Want the theory? [The formula, one layer down →](https://github.com/awakenfyi/lyra)*

**Receipts, not vibes.** MIT licensed. *[awaken.fyi](https://awaken.fyi)*
