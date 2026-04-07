# /career-ops — Main Command Router

Read CLAUDE.md, cv.md, and config/profile.yml before doing anything.

## Auto-detection

If the user pastes a job description (contains "responsibilities", "requirements", "qualifications", "you will", "what you'll do") — auto-run the full pipeline.

If the user pastes a URL — fetch it, extract the JD, then run the full pipeline.

## Full pipeline

1. Archetype detection — which role family?
2. Evaluation — score A-F across 7 dimensions (see CLAUDE.md)
3. Gap analysis — what's missing?
4. Resume strategy — which experiences lead?
5. Ask: "Want me to generate the resume, cover letter, and interview prep?"

If score is below B- (3.3/5.0), flag it and ask before proceeding.

## Evaluation output format

## [Company] - [Role Title]
**Archetype:** [matched archetype]
**Score:** [X.X/5.0] - [Grade]

| Dimension | Score | Notes |
|-----------|-------|-------|
| Role match | X/5 | |
| Compensation | X/5 | |
| AI relevance | X/5 | |
| Growth potential | X/5 | |
| Location fit | X/5 | |
| Company quality | X/5 | |
| Gap risk | X/5 | |

### Strengths
### Gaps / Risks
### Recommendation

## Logging

After each evaluation append a row to data/tracker.md:
| Date | Company | Role | Score | Status | Notes |

Create the file with headers if it doesn't exist.
