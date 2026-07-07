# AI Grant Writing Coach

Don't wait for a rejection to find out what's wrong. Refine your grant proposal now, with the same lens a funder uses.

Built by [Fast Forward](https://ffwd.org) for tech nonprofits. This repository is the Claude plugin.

## About

AI can scale social impact, but only if the work underneath holds up. This coach pressure-tests your grant proposal the way a funder would: is the problem real, does the solution fit, can the team deliver, do the numbers hold up. Start with the scorecard for a fast read on the fundamentals, then run the deeper checks for a full teardown. It refines your draft. It never writes it for you.

## Install in Claude

You need Claude Code first. Install it with one of:

- Homebrew: `brew install @anthropic-ai/claude-code`
- npm: `npm install -g @anthropic-ai/claude-code`
- Native installer: https://code.claude.com/docs/en/setup.md

Then sign in:

```
claude login
```

Launch Claude Code by running `claude`, then add the marketplace and install the plugin:

```
/plugin marketplace add ffwdorg/ffwd-proposal-prep
/plugin install ffwd-proposal-prep@ffwd-proposal-prep
```

Prefer a menu? Run `/plugin`, open the Marketplaces tab, add `ffwdorg/ffwd-proposal-prep`, then find the plugin under Discover and install it.

## How to use

1. Paste your full proposal draft into Claude.
2. Applying to a specific funder? Paste their criteria too (RFP, FAQ, or "What We Fund" page). The coach grades you against their priorities, not just the general ones.
3. Type "Run scorecard" to start. It rates the fundamentals, flags your weakest, and points you to the checks to run next.

## Get Feedback (4 checks)

- Which paragraph falls flat?
- What 5 questions would a skeptical reviewer ask?
- Full criterion-by-criterion score (1/2/3 scale)
- Interactive test: Defend your proposal

## Stress-Test & Refine (10 checks)

- Is the problem grounded in real user need?
- Does the solution match the problem?
- Does the team have lived experience with the problem?
- Can the team actually deliver?
- Are you measuring outcomes or just outputs?
- Is your theory of change explicit and credible?
- What happens to the work after the grant ends?
- Does the solution understand the system it's entering?
- Is this proposal the right fit for the funder?
- Are the AI claims credible and responsible?

## Help Us Improve This Tool

Something fall flat? A check need work? Email us: [hello@ffwd.org](mailto:hello@ffwd.org?subject=AI%20Grant%20Writing%20Coach%20Feedback)

## License

Apache 2.0
