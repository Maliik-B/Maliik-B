# Hi, I'm Maliik

Full-stack developer and game designer. I build production software and multiplayer games with TypeScript, React, Node.js, and game engines.

## Projects

### Nibble -- Food & Product Safety Platform

**[trynibble.app](https://trynibble.app)** | Available on Google Play

A production PWA that aggregates food, drug, device, product, and vehicle recalls from government agencies across 13 countries. Users get personalized safety alerts based on dietary needs, allergies, and location.

- **Frontend:** React + TypeScript, 48 pages, 14 languages, Capacitor for Android
- **Backend:** Express.js API with 48 automated ingestion pipelines sourcing data from FDA, Health Canada, FSANZ, TGA, EU Safety Gate, RASFF, and 30+ other agencies
- **Data:** PostgreSQL via Supabase, 108 migrations, full keyword extraction and classification
- **Monetization:** Stripe + RevenueCat (subscription model)

`158K LOC` | `1,134 tests` | `48 data pipelines` | `13 countries` | `14 languages`

*Private repository -- available for code walkthrough in interviews.*

---

### [Turing Tables](https://github.com/Maliik-B/turing-tables) -- Roguelite Deckbuilder vs a Live LLM

**[Playable](https://maliik-b.github.io/turing-tables/)** | Built for the June Solstice Game Jam

A roguelite deckbuilder where you interrogate AI opponents. About 70% of the opponent's moves are live Google Gemini calls and 30% are deterministic scripts, and you score by catching the fakes, a playable Turing test.

- React 19 + TypeScript + Vite + Tailwind, fully static (GitHub Pages), no backend
- Google Gemini API with multi-model fallback (2.5 Flash-Lite / 2.5 Flash / 3 Flash)
- All visuals generated in CSS/SVG, audio synthesized via Web Audio, CSP locked to Google only

`React 19` | `TypeScript` | `Gemini API` | `shipped`

---

### [Waypoint IEP Server](https://github.com/Maliik-B/waypoint-mcp) -- MCP Server for Education

An MCP server that helps teachers differentiate instruction for students with Individualized Education Programs (IEPs). Given a lesson and a student's IEP, the server provides Claude with structured context to produce specific, actionable instructional modifications.

- TypeScript, Model Context Protocol (MCP 1.0)
- Multi-student differentiation with accommodation matrices
- Structured IEP data parsing, lesson plan analysis, and self-regulation checkpoints
- Built for the [Waypoint Learning Challenge](https://github.com/igoldstein19/waypoint-challenge)

`48 tests`

---

### [RogueEr](https://github.com/Maliik-B/RogueEr) -- Multiplayer Poker Roguelike

A multiplayer poker game where the rules mutate every round. Players vote on rule changes that alter hand rankings, card properties, and win conditions.

- TypeScript monorepo: Phaser 4 (client) + Colyseus (server) + shared game logic
- 30-rule mutation system across 3 categories (hierarchy, card property, composition)
- 4-stage hand evaluation pipeline with immutable state
- Full betting engine, spectator system, action replay

`9.5K LOC` | `180 tests`

---

### [Fable](https://github.com/Maliik-B/Fable) -- Narrative Deckbuilder

A Slay the Spire-inspired deckbuilder in Godot 4 with a narrative layer. Features a passion system that shifts combat dynamics based on story choices, and dual-personality characters that evolve across acts.

- GDScript, Godot 4
- Combat engine, procedural map generator, branching event system
- Card/relic pools, status effects, shop and rest mechanics
- Uses the [Copy All Errors](https://github.com/Maliik-B/Fable/tree/master/addons/copy_all_errors) Godot editor plugin for batch-copying debugger output

`6.3K LOC`

---

## Open Source

I contribute to the tools I build on:

- **[resend/react-email #3572](https://github.com/resend/react-email/pull/3572)** -- Merged a fix so uploading a template updates the existing Resend template instead of creating a duplicate.
- **[supabase/postgres-meta #1083](https://github.com/supabase/postgres-meta/pull/1083)** and **[supabase/postgrest-js #2461](https://github.com/supabase/supabase-js/pull/2461)** -- A `bigint_as` type-generation option for int8/numeric columns, so values past 2^53 stay lossless. In active maintainer review, designed together with a Supabase maintainer.

---

## Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?logo=stripe&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?logo=godotengine&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?logo=godotengine&logoColor=white)
![Phaser](https://img.shields.io/badge/Phaser-8B0000?logo=data:image/svg+xml;base64,&logoColor=white)
