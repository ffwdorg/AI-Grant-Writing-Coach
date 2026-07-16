# AI Grant Writing Coach

Want to get your AI proposal in tip-top shape before you submit to a funder? Refine your proposal draft with the same lens a funder uses.

Built by [Fast Forward](https://ffwd.org).

## About the Tool

Make the case for what you're building, then adapt it with 14 prompts modeled on the principles funders are considering. The prompts surface what needs more work before you submit. They pressure-test your draft across problem clarity, solution fit, impact, and more.

## Before you start

Remove any personally identifying information from your proposal if your organization's policies require it.

## Before installing: the easier paths

This plugin is the advanced, self-managed way to use the coach. Setup runs through GitHub, and updates are manual. For the easiest experience, always running the latest version with zero setup, use the [ChatGPT version](https://chatgpt.com/g/g-6a5913dbdcec8191992bd7a48704e64b-ai-grant-writing-coach), the [Gemini version](https://gemini.google.com/gem/1EOKtC8V4_uyvUbYAriTdfTD4jSjmWxN5?usp=sharing), or the [copy-paste prompts on our website](https://www.ffwd.org/ai-grant-writing-coach). Install the plugin if you work in Claude daily and want the prompts as native slash commands.

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
3. Type "Run assessment" to start. It rates the fundamentals, names your weakest areas, and points you to the prompts to run next.

Ask for any prompt in plain language, for example "Run the assessment" or "Check my theory of change."

## Staying updated

The hosted versions (the website prompts, the Custom GPT, and the Gemini Gem) always run the latest release. You don't need to do anything.

The installed plugin is a snapshot: you stay on the version you installed until you refresh it. Claude's in-app Update button doesn't reliably detect new versions of external plugins (a known Claude issue), so when we release a new version, update by reinstalling:

1. Settings, then Plugins: remove the ai-grant-writing-coach marketplace.
2. Re-add it: `ffwdorg/AI-Grant-Writing-Coach`
3. Reinstall the plugin.

Your installed version shows in the plugin details panel. The latest version is in this repo's `.claude-plugin/plugin.json`.

## Get Feedback

- Assess my proposal against the fundamentals a funder weighs.
- Which paragraph falls flat?
- What 5 questions would a skeptical reviewer ask?
- Stress-test my proposal in an interactive critique.

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

Something fall flat? A prompt needs work? Email us: [hello@ffwd.org](mailto:hello@ffwd.org?subject=AI%20Grant%20Writing%20Coach%20Feedback)

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): use, share, and adapt these prompts freely, with credit to Fast Forward.
