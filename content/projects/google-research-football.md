---
title: "Google Research Football"
date: 2020-09-15
description: "Building AI agents to play 11v11 simulated football — 61/1138"
tags: ["kaggle", "reinforcement-learning", "agents"]
---

## Overview

Building AI agents that play 11v11 simulated football. Agents receive game observations (player positions, ball state, game mode) and return actions, competing head-to-head on Kaggle's evaluation servers with Elo-style rating.

## Approach

- **Rule-based tactical foundation** — "marauding wingers" formation: wide players sprint down flanks and deliver crosses into the box
- **Zone-based decision architecture** — field divided into zones (defensive third, wing corridors, crossing range, shooting range) with different behaviors per zone
- **Opponent-aware mechanics** — proximity detection for context-sensitive decisions: sprint in open space, dribble under pressure, pass when crowded
- **Goalkeeper exploitation** — specific logic to detect when the opposing keeper is out of position and trigger long-range shots
- **Sprint/dribble state machine** — manages action mode based on field position and opponent proximity

## Result

61/1138 🥉

## Links

- [GitHub Repository](https://github.com/Galliard7/google-football-2020)
