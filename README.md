# Vangrd: a Travian automation assistant

[Vangrd](https://vangrd.bot) is a Travian bot that plays your account the way you set it up. It builds villages, starts farm lists, trains troops, runs NPC trades, and warns you about incoming attacks, all on a weekly schedule that looks like a person playing rather than a script.

This repository holds the public [changelog](CHANGELOG.md) and the [guides](#guides). The guides are also on the live site, where they stay current with the UI.

## What it automates

- Buildings. Each village follows its own build plan. You can save plans as templates and let Vangrd pick the next upgrade on its own.
- Farming. It starts farm lists on schedule, farms and clears oases, and can tune troop counts per wave with the optimizer.
- Training. Priority queues per village, account defaults, and automatic troop healing.
- Trade. Automatic NPC trades and supply routes between villages.
- Defense. Attack alerts, per-village response rules, and notifications.
- Attacks. A planner for multi-wave attacks, timed by send time or landing time.
- Expansion. It trains settlers and founds new villages at coordinates you pick.
- Scouting. Player tracking with profile history, and a search for inactive villages near you.
- Safety. Weekly activity schedules, a dedicated residential IP per account, and a browser whose locale and timezone match that IP.

## Guides

Start with [getting started](guides/getting-started.md), then read the guide for whichever automation you want to turn on.

### Setup

| Guide | What it covers |
|---|---|
| [Getting started with Vangrd](guides/getting-started.md) | Add a Travian account, read the dashboard, and turn on your first automations. |
| [Travian bot schedules, agents, and safety settings](guides/schedules-and-safety.md) | Weekly activity schedules, coordinating agents, and browser locale and timezone settings. |

### Farming

| Guide | What it covers |
|---|---|
| [Travian farm bot](guides/travian-farm-bot.md) | Farm list scheduling, oasis farming and clearing, target scanning, and fatal reports. |
| [Travian farm list optimizer](guides/farm-optimizer.md) | Auto-optimize and auto-tune per list, with a preview of every change before it applies. |

### Villages and economy

| Guide | What it covers |
|---|---|
| [Travian auto builder](guides/building-queue-automation.md) | Village build plans, account defaults, and reusable templates. |
| [Travian NPC bot](guides/travian-npc-bot.md) | NPC trades, supply routes between villages, and account-wide caps on both. |
| [Travian settler bot](guides/auto-expansion.md) | Settler training, Residence support, and settlement coordinates. |

### Military

| Guide | What it covers |
|---|---|
| [Travian troop training bot](guides/troop-training-automation.md) | Training priorities per village, account defaults, and troop healing. |
| [Travian defense bot](guides/automated-defense.md) | Incoming attack alerts, per-village responses, and notifications. |
| [Travian attack planner](guides/attack-planner.md) | Multi-wave attacks with send-at or lands-at timing. |

### Intelligence

| Guide | What it covers |
|---|---|
| [Travian player tracker](guides/player-tracking.md) | Player snapshots, profile change history, and finding inactive villages. |

## Changelog

[CHANGELOG.md](CHANGELOG.md) lists every update, newest first. It matches the changelog inside the app.

## Links

- Live site: [vangrd.bot](https://vangrd.bot)
- Guides with screenshots of the current UI: [vangrd.bot/guides](https://vangrd.bot/guides)
