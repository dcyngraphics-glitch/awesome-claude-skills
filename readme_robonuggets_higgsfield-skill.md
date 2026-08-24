# Higgsfield Skill

One MCP, 30+ image and video models. Skill for Claude Code that wraps the Higgsfield MCP — Seedance 2.0, Sora 2, Veo, Kling, Nano Banana Pro, GPT Image 2, Flux, Hailuo, plus Higgsfield exclusives Soul and Cinema Studio.

## Quick start

Clone into your project (or anywhere a Claude Code session can see):

```
git clone https://github.com/robonuggets/higgsfield-skill
```

Then in Claude Code, install the MCP at user scope so every session shares one auth:

```
claude mcp add --transport http --scope user higgsfield https://mcp.higgsfield.ai/mcp
```

Complete OAuth:

```
/mcp
```

Sign in with your Higgsfield account. Restart Claude Code if tools don't appear.

## What's included

```
higgsfield-skill/
├── .claude/skills/higgsfield/
│   └── SKILL.md              # the skill
├── CLAUDE.md                 # project instructions
└── README.md                 # this file
```

## Features

- **One auth, 30+ models** — no per-provider API keys to manage
- **Built-in decision rule** — only suggests Higgsfield when the user already subscribes
- **Pricing transparency** — surfaces credit costs and reminds you of the cost-approval gate before paid runs
- **Pairs with existing pipelines** — slots into cinematic-ads, image-gen, b-roll workflows

## Usage examples

After install, just ask Claude what you want. The skill activates on Higgsfield-related requests:

- *"Use higgsfield to generate a cinematic shot of a runner at sunrise."*
- *"Animate this storyboard frame with Kling via higgsfield."*
- *"Generate a poster with GPT Image 2 through my higgsfield sub."*

## When NOT to use

If you don't have a Higgsfield subscription, this skill isn't for you — the whole value is unlocking models you're already paying for. Don't subscribe just for one project.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use with attribution.

## Attribution

Created by Jay from RoboLabs. Learn more at [RoboNuggets](https://robonuggets.com).
