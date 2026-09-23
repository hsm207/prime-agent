# backlog.md

## 1. Run the backlogged RLM token-efficiency experiments (1, 6, 3 first)
Captured: 2026-09-22
Why: the single-question Alice run showed ~6.9x fewer tokens but a weaker, first-match-only answer; whether RLM holds up across repeated questions, multi-turn state, and better extraction is still unknown. The three-critics spawn track answered a different question, not this one.
Success criteria: experiments 1 (repeated questions on one corpus), 6 (multi-turn persistent state), and 3 (extraction strategies) executed with input/output/total tokens recorded in a lab note, and the full-context/RLM crossover point stated as a number.

## 2. Quote-verification pass for critique grounding
Captured: 2026-09-22
Why: the three critics pulled at most ~995 tokens of source back per model context, so quotations lean on parametric memory; "grounded" is proven for chapter structure but not for a single quote.
Success criteria: every quotation in a three-critics run asserted against alice.txt from Python (`assert quote in text`), with the match rate recorded in a lab note.

## 3. Explain the cancelled-after-done child roster status
Captured: 2026-09-22
Why: probe 5 showed a child reading `cancelled` after collect() had already returned `done`; attempt 3 did not reproduce it, and until explained the roster status cannot be trusted as a completion metric.
Success criteria: cause identified from child-journal evidence and either documented in a lab note or filed upstream.

## 4. Explain the parent agent_start/agent_end asymmetry
Captured: 2026-09-22
Why: attempt 3's telemetry closed 4 agent_start against 5 agent_end with zero stream failures and zero retries; unexplained loop events make any count-based metric drawn from JSONL suspect.
Success criteria: the extra agent_end's source identified in prime-agent source, and the telemetry counting recipe - or the three-critics lab note - corrected accordingly.
