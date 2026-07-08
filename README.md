# AI Grant Writing Coach

Want to get your AI proposal in tip-top shape before you submit to a funder? Refine your proposal draft with the same lens a funder uses.

Built by [Fast Forward](https://ffwd.org).

## About the Tool

Make the case for what you're building, then adapt it with 14 prompts modeled on the principles funders are considering. The prompts surface what needs more work before you submit. They pressure-test your draft across problem clarity, solution fit, impact, and more.

## Before you start

Remove any personally identifying information from your proposal if your organization's policies require it.

## Install in Claude

The coach installs as a plugin. Choose the Claude surface you use.

### Claude Code (terminal, desktop, or IDE)

Install Claude Code first: `brew install @anthropic-ai/claude-code`, or `npm install -g @anthropic-ai/claude-code`, or the native installer at https://code.claude.com/docs/en/setup.md. Then sign in with `claude login`.

Launch Claude Code by running `claude`, then:

```
/plugin marketplace add ffwdorg/AI-Grant-Writing-Coach
/plugin install ai-grant-writing-coach@ai-grant-writing-coach
```

### Cowork (claude.ai web app)

Plugin installs happen in Settings.

1. Go to Settings, then Plugins.
2. Click Add, then Add marketplace, and enter: `ffwdorg/AI-Grant-Writing-Coach`
3. Open the Browse or Personal tab, find `ai-grant-writing-coach`, and install it.

The GitHub connector is a separate feature and is not required to install this plugin.

## How to use

1. Paste your full proposal draft into Claude.
2. Applying to a specific funder? Paste their RFP or "What We Fund" page along with your draft, and the coach evaluates you against their specific criteria.
3. Type "Run scorecard" to start. It rates the fundamentals, flags your weakest, and points you to the checks to run next.

Ask for any check in plain language, for example "Run the scorecard" or "Check my theory of change."

## Staying updated

The plugin installs onto your Claude, so you stay on the version you installed until you update it. When we push improvements, refresh the marketplace and update the plugin from the same place you installed it. The hosted versions (the website, the Custom GPT, and the Gem) update automatically. Only the installed plugin needs a manual refresh.

## Get Feedback

- Assess my proposal against all criteria.
- Which paragraph falls flat?
- What 5 questions would a skeptical reviewer ask?
- Stress-test my proposal in an interactive debate.

## Stress-Test & Refine

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

Help Us Improve This Tool. Email us: [hello@ffwd.org](mailto:hello@ffwd.org?subject=AI%20Grant%20Writing%20Coach%20Feedback)

## License

Apache 2.0
