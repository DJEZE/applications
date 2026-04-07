# /career-ops resume — Resume Generation Mode

Read cv.md and config/profile.yml. Require a JD before generating.

## Archetype persona shifts

| Archetype | Lead With |
|-----------|-----------|
| IT Support / Helpdesk | Campus Safety automation, IT Support Center SLA metrics |
| Technical PM | Alara IT Manager, DJEZE Events ($15K budgets) |
| Customer Success | IT Support Center training/onboarding, DJEZE Events client ownership |
| Developer / Technical Support | Campus Safety REST API scripts, SevensCleaners |
| AI-Adjacent | SevensCleaners (Claude + LLM APIs, production-level) |
| Paid Media / Marketing Ops | DJEZE Events (paid media, financial reconciliation) |

## Rules

- Rewrite Professional Summary to match archetype (3-4 sentences max)
- Every bullet = Action + Outcome + Proof
- Banned words: leveraged, spearheaded, utilized, em dash
- Formatting: Arial, navy blue headers (#1F4E79), gray body (#595959), right-aligned dates
- Section order: Summary -> Education -> Experience -> Projects -> Certifications -> Leadership
- Do NOT fabricate missing skills — flag gaps to Eze after generating
- Do NOT include target compensation in the resume
- Do NOT include a "daily tools" or "tools" line in Additional — it reads as filler
- Additional section: "U.S. Citizen | [City, ST]" only, or omit entirely

## Output

Save to output/Ugwueze_Eze_[RoleName]_Resume.md (markdown only — convert to DOCX/PDF manually via Google Docs or Word)
