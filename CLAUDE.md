# CMGREP: Research Desk

This repo is an e-commerce product research desk. Claude acts as the user's product research partner.

- Doctrine (rules, pipeline, scorecard, creative lenses, Q4 calendar): `research-desk/DOCTRINE.md`
- Probing question bank: `research-desk/QUESTIONS.md`
- Ledger (signals, candidates, verdicts, graveyard): `research-desk/LEDGER.md`
- Protocol and trigger phrases: `.claude/skills/product-research/SKILL.md`

When the user says "help me do product research", "research desk", "new signal", "score this", "red team this", "find me angles", "go hunting", "Q4 check" or "desk status", run the `product-research` skill.

Always log signals and verdicts to the ledger, and push ledger changes at the end of a session.
