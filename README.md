# Paul Mueller · Roblox developer

Gameplay systems for Roblox: vehicle and drone controllers, combat and weapons, cameras, HUDs
and tools. **Open for commissions:** message me on Discord, **@thejuneman**.

## FPV Strike

![FPV Strike: a rocket salvo breaching the house wall](https://raw.githubusercontent.com/thejuneman/fpv-strike/main/docs/gifs/breach.gif)

An FPV strike drone with a real flight model, guided missiles, SAM sites that shoot back, a
goggles-style OSD and a replay system with cinematic cameras.
**[Play it on Roblox](https://www.roblox.com/games/131319634104165)** ·
**[Code, write-up and more clips](https://github.com/thejuneman/fpv-strike)**

| | |
|---|---|
| ![Four-target seeker volley](https://raw.githubusercontent.com/thejuneman/fpv-strike/main/docs/gifs/volley.gif) | ![Flares pulling off a SAM](https://raw.githubusercontent.com/thejuneman/fpv-strike/main/docs/gifs/sam.gif) |
| ![Through the breach and out the window](https://raw.githubusercontent.com/thejuneman/fpv-strike/main/docs/gifs/inside.gif) | ![Debug overlay drawing the guidance](https://raw.githubusercontent.com/thejuneman/fpv-strike/main/docs/gifs/debug.gif) |

- **Flight physics:** the drone has to tilt to move, under drag and ground effect. There are
  three flight modes, including full acro on Betaflight rate curves.
- **Missile guidance:** proportional navigation that leads moving targets, a top-attack dive
  profile, multi-target lock-on, and flares that decoy seekers.
- **Server-authoritative combat:** the server checks and re-flies every shot, and clients
  predict impacts so hits feel instant.
- **Enemies that fight back:** SAM sites with radar locks, enemy drones that dodge and drop
  flares, and a house that blows apart brick by brick and rebuilds itself.
- **Presentation:** a goggles OSD, analog video breakup as the signal weakens, a missile cam,
  a slow-motion kill cam, and replays with an automatic camera director.
- **Engineering:** automated tests that fly the real flight and guidance code; lint, format and
  strict type checks all pass; a debug overlay draws the guidance maths in the world.

Built with AI (Claude, by Anthropic) as the coding agent, directed and play-tested by me.

## Commissions

Message me on Discord, **@thejuneman**, with what you need, your deadline and your budget.
