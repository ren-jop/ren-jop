# Ren Jopson

Software engineering across **native macOS, Rust, embedded systems, and game systems**.

I like projects where boundaries matter: GUI ↔ daemon, calendar ↔ timer, firmware ↔ hardware, procedural generation ↔ player feedback. My focus is clear ownership, observable runtime behaviour, and small systems that can be reasoned about when something goes wrong.

**Portfolio:** https://ren-jop.github.io/  
**Project index:** https://ren-jop.github.io/projects/

## Selected engineering

| Project | Problem | Engineering |
| --- | --- | --- |
| [Deadlock](https://github.com/ren-jop/deadlock) | Make sleep windows and distraction rules difficult to ignore | Swift, privileged daemon, launchd, IOKit, Unix IPC |
| [Focus](https://github.com/ren-jop/focus) | Keep focus-session timing simple while retaining useful history | Swift, adaptive timers, local history, IPC |
| [Planner](https://github.com/ren-jop/planner) | Connect planning to execution without creating another calendar database | EventKit, Apple Calendar, cross-app state boundaries |
| [Oxide Keys](https://github.com/ren-jop/oxide-keys) | Learn embedded Rust through a real handheld device | RP2040, embedded Rust, custom 4-layer PCB, firmware |
| [Descent: Null](https://github.com/ren-jop/descent-null) | Build a readable survival loop around procedural caves | Rust, Bevy ECS, procgen, survival and hazard systems |

## Stack

**macOS:** Swift · AppKit · SwiftUI · EventKit · launchd · IOKit  
**Systems:** Unix IPC · state machines · diagnostics · event-driven design  
**Rust:** Bevy · embedded Rust · `no_std` · rp2040-hal  
**Hardware:** KiCad · RP2040 · PCB design · datasheet-driven development

## How I build

- Give important state one authoritative owner.
- Prefer runtime evidence, compiler output and documentation over assumptions.
- Keep idle work small; use events and lifecycle hooks where they fit.
- Validate a complete working path early, then widen the system.
- Use AI for research, debugging and review, while treating generated output as a hypothesis rather than a source of truth.

Most of the macOS apps are currently **preview builds**. I label them that way deliberately instead of presenting unverified work as production-ready.
