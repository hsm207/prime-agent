# backlog.md

## 1. Run the DoC editorial council on prime-agent (preregistration port)
Captured: 2026-09-23
Why: human ruling - priority one, the chosen next experiment. Corpus and EXPERIMENT.md are not in this workspace (writing-pipeline lives on the Windows machine) and session time ran out. Executes writing-pipeline's preregistered dual-pipeline council (5-turn loop, N=4 waves) via rlm.spawn on gemini-3.8-flash - testing H3 (binary DoC protocol, anti-sycophancy); H1 GPU saturation and H2 L4-vs-API economics stay parked with the deleted L4.
Success criteria: corpus + EXPERIMENT.md obtained (clone URL, paste, or declared deviation), adaptation ruling recorded against the 2026-09-13-03 preregistration, two camera-ready articles produced by a prime-agent run with clean [DISAGREE]/[COMMIT] stances and malformed=0, telemetry captured, results lab note in writing-pipeline (vs preregistration) plus run-mechanics note in prime-agent.

## 2. Run the backlogged RLM token-efficiency experiments (1, 6, 3 first)
Captured: 2026-09-22
Why: the single-question Alice run showed ~6.9x fewer tokens but a weaker, first-match-only answer; whether RLM holds up across repeated questions, multi-turn state, and better extraction is still unknown. The three-critics spawn track answered a different question, not this one.
Success criteria: experiments 1 (repeated questions on one corpus), 6 (multi-turn persistent state), and 3 (extraction strategies) executed with input/output/total tokens recorded in a lab note, and the full-context/RLM crossover point stated as a number.

## 3. Quote-verification pass for critique grounding
Captured: 2026-09-22
Why: the three critics pulled at most ~995 tokens of source back per model context, so quotations lean on parametric memory; "grounded" is proven for chapter structure but not for a single quote.
Success criteria: every quotation in a three-critics run asserted against alice.txt from Python (`assert quote in text`), with the match rate recorded in a lab note.

