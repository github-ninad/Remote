# Incident Post-Mortem Template

```markdown
# Incident PM: [Title] — [Date]

**Severity:** SEV-N
**Duration:** [start] to [end]  ([X] hours)
**Detected by:** [system / human / customer]
**Mitigated by:** [Name(s)]
**Author:** [Name]

## Summary
2–3 sentences. What happened, what was impacted, how it was resolved.

## Timeline
- HH:MM — Event
- HH:MM — Event
[All times in UTC]

## Impact
- Customers affected: [number / scope]
- Revenue impact: [if known]
- Internal impact: [team time spent]

## Root cause(s)
Be specific. "Bad code" is not a root cause. "Race condition in X function under load > Y rps" is.

## What went well
- [Specific observations]

## What didn't go well
- [Specific observations — no blame, just facts]

## Action items
| Action | Owner | Due | Status |
|--------|-------|-----|--------|
| [Item] | [Name] | YYYY-MM-DD | Open |

## Blameless reflection
This is not about who. It's about what conditions made the failure possible. Capture them.
```

---

*Part of the [REMOTE playbook](../REMOTE.md)*
