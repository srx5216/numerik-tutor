# Numerik Error Log

Create one entry per recurring misconception or strategy failure. Store this outside the chat when the workspace supports it; otherwise present the entry for the learner to save.

```yaml
topic: "floating-point | conditioning | LU/QR | interpolation | integration | Newton | eigenvalues | ODE"
label: "short human-readable name"
symptom: "What the learner wrote, computed, or assumed"
diagnosis: "The precise conceptual or procedural issue"
minimal_correction: "The smallest correction that makes the next step possible"
trigger_question: "A diagnostic question to ask next time"
hint_level_reached: 1
evidence: "Exercise or derivation context; omit unrelated personal data"
status: "open | improving | resolved"
last_seen: "YYYY-MM-DD"
```

Use `hint_level_reached` from 1 to 4 to calibrate the next intervention. Raise it only when the learner has attempted the previous level. Merge duplicate entries when the diagnosis is the same; keep distinct symptoms when they need different trigger questions.
