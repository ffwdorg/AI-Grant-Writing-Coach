# AI Grant Writing Coach

Stress-test your grant proposal before you submit. A self-serve coach that rates the fundamentals, then takes each one apart with the same lens a funder uses.

Built by [Fast Forward](https://ffwd.org) for tech nonprofits. Available as a ChatGPT Custom GPT, a Gemini Gem, or a Claude plugin. It refines your draft. It never writes it for you.

---

## How to use

1. Start a conversation and paste your full proposal draft.
2. Applying to a specific funder? Paste their criteria too (RFP, FAQ, or "What We Fund" page). The coach grades you against their priorities, not just the general ones.
3. New here? Run the scorecard first: type "Run scorecard." It rates the seven fundamentals, names your weakest ones, and points you to the stress tests to run next.
4. Then run those stress tests for a full teardown: quoted evidence, the reviewer's actual objection, and the type of evidence that would close the gap. Or run any check by name.

The scorecard is the map. The stress tests are the teardown. The scorecard is a fast rating across the seven fundamentals. Each stress test takes one dimension apart in depth. AI responsibility, theory of change, systems thinking, and funder alignment are covered only by their own stress tests, not the scorecard.

---

## Install

### ChatGPT

Open the Custom GPT: https://chatgpt.com/g/g-6a235c871f808191bdcb22c951569dae-fast-forward-grant-proposal-prep

### Gemini

Open the Gem: https://gemini.google.com/gem/1EOKtC8V4_uyvUbYAriTdfTD4jSjmWxN5?usp=sharing

### Claude

Available as a Claude plugin at public launch. During the beta, ask for the plugin zip to install it locally in Claude Code.

---

## Checks

### Scorecard (start here)

| Skill | What it does | Invoke with |
|---|---|---|
| `scorecard` | Rates the 7 fundamentals (1/2/3), flags your weakest, and routes you to the right stress tests | "Run scorecard" |

### Stress-Test (10 deep-dive checks)

| Skill | What it checks | Invoke with |
|---|---|---|
| `problem-clarity` | Is the problem grounded in real user need? | "Run problem clarity" |
| `solution-fit` | Does the solution match the problem? | "Run solution fit" |
| `lived-experience` | Does the team have lived experience with the problem? | "Run lived experience" |
| `team-capacity` | Can the team actually deliver? | "Run team capacity" |
| `impact-measurement` | Are you measuring outcomes or just outputs? | "Run impact check" |
| `theory-of-change` | Is your theory of change explicit and credible? | "Run theory of change" |
| `sustainability` | What happens to the work after the grant ends? | "Run sustainability" |
| `systems-thinking` | Does the solution understand the system it's entering? | "Run systems thinking" |
| `funder-alignment` | Is this proposal the right fit for this funder? | "Run funder alignment" |
| `ai-specifics` | Are the AI claims credible and responsible? | "Run AI check" |

### Feedback (3 prep checks)

| Skill | What it checks | Invoke with |
|---|---|---|
| `weakest-paragraph` | Which paragraph is doing the most damage? | "Find the weakest paragraph" |
| `reviewer-questions` | What 5 questions would a skeptical reviewer ask? | "Run reviewer questions" |
| `defend-draft` | Interactive pressure test: defend your proposal live | "Run defend the draft" |

---

## Reviewer context

Every check uses a human-centered design lens that weights user evidence, solution fit, co-design, lived experience, capacity, and outcomes. If you paste funder-specific criteria before running any check, the coach prioritizes those criteria over the general lens.

It will never invent statistics, quotes, or sources, and it will never write the proposal for you. It flags gaps and names the kind of evidence that would close them. You write the words.

---

## Feedback

Something fell flat? A check needs work? Tell us: [hello@ffwd.org](mailto:hello@ffwd.org?subject=AI%20Grant%20Writing%20Coach%20Feedback)

---

## License

Apache 2.0
