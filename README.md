# Fast Forward AI Proposal Prep

Stress-test your AI grant proposal before you submit. 11 structured checks across problem clarity, solution fit, team capacity, impact measurement, and funder alignment.

Built by [Fast Forward](https://ffwd.org) for tech nonprofits.

---

## Install

### Claude / Claude Code

```bash
claude --plugin-url https://ffwd.org/tools/proposal-prep/plugin.zip
```

Or install from the community marketplace once listed:

```
/plugin install ffwd-proposal-prep
```

### ChatGPT

Open the Custom GPT: [chatgpt.com/g/g-PLACEHOLDER](#)

### Gemini

Open the Gem: https://gemini.google.com/gem/1EOKtC8V4_uyvUbYAriTdfTD4jSjmWxN5?usp=sharing

---

## How to use

1. Start a conversation and paste your full proposal draft.
2. Optionally paste funder criteria (RFP, FAQ, "What We Fund" page) — this improves the Funder Alignment check.
3. Run any check by name.

---

## Skills

### Stress-Test (7 checks)

| Skill | What it checks | Invoke with |
|---|---|---|
| `problem-clarity` | Is the problem grounded in real user need? | "Run problem clarity" |
| `solution-fit` | Does the solution match the problem? | "Run solution fit" |
| `lived-experience` | Does the team have lived experience with the problem? | "Run lived experience" |
| `team-capacity` | Can the team actually deliver? | "Run team capacity" |
| `impact-measurement` | Are you measuring outcomes or just outputs? | "Run impact check" |
| `funder-alignment` | Is this proposal the right fit for this funder? | "Run funder alignment" |
| `ai-specifics` | Are the AI claims credible and responsible? | "Run AI check" |

### Feedback (4 checks)

| Skill | What it checks | Invoke with |
|---|---|---|
| `weakest-paragraph` | Which paragraph is doing the most damage? | "Find the weakest paragraph" |
| `reviewer-questions` | What 5 questions would a skeptical reviewer ask? | "Run reviewer questions" |
| `scorecard` | Full criterion-by-criterion score (1/2/3 scale) | "Run scorecard" |
| `defend-draft` | Interactive pressure test — defend your proposal live | "Run defend the draft" |

---

## Reviewer context

Every skill uses the **generic reviewer** archetype: a human-centered design lens that weights user evidence, solution fit, co-design, lived experience, capacity, and outcomes.

If you paste funder-specific criteria before running any check, the skills will prioritize those criteria over the general lens.

---

## Feedback

Something fell flat? A prompt needs work? Tell us: [hello@ffwd.org](mailto:hello@ffwd.org?subject=AI%20Proposal%20Prep%20Feedback)

---

## License

Apache 2.0
