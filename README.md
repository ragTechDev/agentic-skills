![ragTech Banner](https://yt3.googleusercontent.com/c5DAYKK2gBwR0B6itYEL85Nb5qqNnWmgCnm5c81mz242lC7Xq9mYOYYUbEQI0NZig4oL4xdJ=w2276-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj)

# Agentic Skills

A collection of reusable agentic coding skills from the team behind [ragTech](https://ragtechdev.com), a tech podcast run by three software engineers. These are skills we actually use in our own day-to-day engineering work, open-sourced in case they're useful to you too — in the same spirit as our [lean-canvas-model](https://github.com/ragTechDev/lean-canvas-model) template.

We don't represent any organisation beyond our show, and this isn't a declared industry standard — just what has worked for us. Feel free to adapt anything here to your own workflow.

## What's a Skill?

Each skill lives in its own directory under `.agents/skills/`, with a `SKILL.md` describing what it does and when to use it, plus whatever supporting `assets/`, `references/`, or `evals/` it needs. This follows the same AgentSkills convention used across our other repos.

A `.claude/skills` symlink points at `.agents/skills` so Claude Code picks these up automatically.

## Quick Setup

Clone the whole repo to get every skill:
```
git clone https://github.com/ragTechDev/agentic-skills.git
```

Or copy just the skill directory you want into your own project's `.agents/skills/`:
```
cp -r agentic-skills/.agents/skills/<skill-name> your-project/.agents/skills/
```

## Available Skills

See `.agents/skills/` — each subdirectory's `SKILL.md` documents what it does. (This list grows as skills get migrated/added — check open issues for what's in progress.)

## Support Us!

<img src="https://ragtechdev.com/assets/techybara/techybara-holding-follow-card-saying-subscribe.png" alt="Techybara holding subscribe card" width="200"/>

If you found this useful, give this repo a star, and help us grow:

- Give this repo a star
- Subscribe to us on [YouTube](https://www.youtube.com/@ragTechDev) and give our podcast a star on [other streaming platforms](linktr.ee/ragtechdev)
- Watch/stream our biweekly podcast, where three of us talk tech, on [YouTube](https://www.youtube.com/@ragTechDev), [Spotify](open.spotify.com/show/1KfM9JTWsDQ5QoMYEh489d), [Apple Podcast](https://podcasts.apple.com/us/podcast/ragtech/id1755966218) or [MeListen](melisten.sg/podcast/playlist/ragtech-3415841). Links on [linktr.ee/ragtechdev](linktr.ee/ragtechdev)!
- Follow us on [Instagram](instagram.com/ragtechdev), [LinkedIn](linkedin.com/company/ragtechdev) and [TikTok](tiktok.com/@ragtechdev)
- If you'd like to work with us or know someone who does, contact us at `hello@ragtechdev.com`

## Other Projects

### Lean Canvas Model Template
Our template for planning out a product with a coding agent: [ragTechDev/lean-canvas-model](https://github.com/ragTechDev/lean-canvas-model)

### Waitlist for Techie Taboo
We're launching a tech card game soon on Kickstarter — [waitlist here](https://ragtechdev.com/techie-taboo) for news.
