# awaken.fyi

**Operating rules for AI.** *Catch your agent's confident mistakes before they ship.*

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
| **[xop-labs](https://github.com/awakenfyi/xop-labs)** | The experimental arm — rules and pilots in the wild, before they earn the standard. | proof |

## In the Wild — Does it let go?

Our first field study installs a rule that makes an AI build small, runs it on every response, then tells it to let go — **and measures whether it does.** Preregistered, instruments committed before any run, results published either way. Told to strip the safety code, it must refuse.

**[→ Hold & Release: Ponytail](https://github.com/awakenfyi/hold-release)** · status: EVALUATION-READY

## Current research program — Reusable Judgment

Stop re-teaching your AI the same judgment in every new chat. A **Judgment
Ledger** keeps the operating rules a project has adopted — what the rule is,
why it exists, when it applies, and when it should stop. **Pilot 000** is the
preregistered test of whether that beats plain memory, a placebo, and prose:
blind human labels, a public kill condition, results published either way.

**[→ Try the paper prototype](https://github.com/awakenfyi/xop-labs/tree/main/in-the-wild/reusable-judgment)** · **[Read Pilot 000](https://github.com/awakenfyi/xop-labs/blob/main/in-the-wild/reusable-judgment/pilot-000-paper/PREREGISTRATION.md)**

Status: **DESIGNED. Under test. No efficiency claim exists yet.**

## Where the evidence actually stands

We publish status honestly, per component, misses alongside hits. The Guards are deterministic and rule-tested; the central gate has **not yet** been validated against blind human labels. Every claim on every README is limited to the evidence attached to it. The evidence ladder (`DESIGNED → EVALUATION-READY → RULE-TESTED → HUMAN-EVALUATED → FIELD-VALIDATED`) never skips rungs, and no model output becomes ground truth.

The rule that does not move: **never override a state that is still warranted.** A system may improve only by surfacing more honestly, never by agreeing more.

*Want the theory? [The formula, one layer down →](https://github.com/awakenfyi/lyra)*

**Receipts, not vibes.** MIT licensed. *[awaken.fyi](https://awaken.fyi)*
