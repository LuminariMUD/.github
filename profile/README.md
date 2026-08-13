<p align="center">
  <img src="./assets/lumiverse-hero.webp" alt="The LumiVerse: eight luminous paths converging on a fantasy citadel" width="100%" />
</p>

<h1 align="center">⚔️ LuminariMUD ⚔️</h1>

<p align="center">
  <strong>A living Pathfinder / D&amp;D 3.5 text world—and the engineering ecosystem behind it.</strong>
</p>

<p align="center">
  <em>Enter a persistent realm. Explore its lore. Help build what comes next.</em>
</p>

<p align="center">
  <a href="https://luminarimud.com/"><img alt="Visit LuminariMUD" src="https://img.shields.io/badge/ENTER_THE_WORLD-luminarimud.com-C99846?style=for-the-badge&logo=firefoxbrowser&logoColor=white" /></a>
  <a href="https://web.luminarimud.com/"><img alt="Play in your browser" src="https://img.shields.io/badge/PLAY_IN_BROWSER-web_client-5240A0?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://github.com/orgs/LuminariMUD/repositories"><img alt="Explore the repositories" src="https://img.shields.io/badge/EXPLORE_THE_CODE-repositories-152238?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img alt="Eight connected systems" src="https://img.shields.io/badge/LumiVerse-8_connected_systems-D4A72C?style=flat-square" />
  <img alt="Approximately 446,000 C and header lines" src="https://img.shields.io/badge/C_%2F_header_lines-~446K-2F74C0?style=flat-square&logo=c&logoColor=white" />
  <img alt="More than sixteen thousand commits" src="https://img.shields.io/badge/source_history-16K%2B_commits-6E40C9?style=flat-square&logo=git&logoColor=white" />
  <img alt="Built by volunteers" src="https://img.shields.io/badge/built_by-volunteers-C64A4A?style=flat-square&logo=githubsponsors&logoColor=white" />
  <a href="https://github.com/LuminariMUD/Luminari-Source"><img alt="Luminari-Source stars" src="https://img.shields.io/github/stars/LuminariMUD/Luminari-Source?style=flat-square&color=C99846" /></a>
</p>

---

## Welcome to the LumiVerse

**LuminariMUD** is a persistent, text-based multiplayer RPG built on the tbaMUD/CircleMUD tradition and powered by a modern **GNU C23** server. Its deep rules engine brings **Pathfinder** and **D&amp;D 3.5** mechanics into a shared world of exploration, combat, storytelling, crafting, building, and community.

But the game server is only the heart of the story.

The **LumiVerse** is a connected, multi-product software ecosystem: native and browser clients, real-time protocols, cross-world and Discord gateways, spatial world-building tools, graph-powered lore intelligence, and a full community website and wiki—all maintained by a very small volunteer team.

> **Small team. Vast undertaking.** In commercial terms, the LumiVerse resembles a substantial mid-sized product ecosystem: not mega-company scale, but unquestionably serious engineering and operations.

## Eight systems. One world.

| System | Role in the LumiVerse |
| :--- | :--- |
| 🏰 **[Luminari-Source](https://github.com/LuminariMUD/Luminari-Source)**<br><br>[![Tests](https://github.com/LuminariMUD/Luminari-Source/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/LuminariMUD/Luminari-Source/actions/workflows/test.yml) [![Stars](https://img.shields.io/github/stars/LuminariMUD/Luminari-Source?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/Luminari-Source) ![C23](https://img.shields.io/badge/GNU_C-23-2F74C0?style=flat-square&logo=c&logoColor=white) | **The realm itself.** A roughly 446,000-line C/header game server with more than 16,000 commits, Pathfinder and D&amp;D 3.5 systems, persistent world data, builders' tools, MariaDB-backed services, and decades of history. |
| 🧭 **[LuminariGUI](https://github.com/LuminariMUD/LuminariGUI)**<br><br>[![CI](https://github.com/LuminariMUD/LuminariGUI/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/LuminariMUD/LuminariGUI/actions/workflows/ci.yml) [![Stars](https://img.shields.io/github/stars/LuminariMUD/LuminariGUI?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/LuminariGUI) ![Lua](https://img.shields.io/badge/Lua-Mudlet-2C2D72?style=flat-square&logo=lua&logoColor=white) | **The adventurer's cockpit.** A rich Mudlet interface with live MSDP vitals, interactive mapping, tabbed chat, spell and affect tracking, group status, sound alerts, and a customizable layout. |
| 🌐 **[luminariweb](https://github.com/LuminariMUD/luminariweb)**<br><br>[![Tests](https://github.com/LuminariMUD/luminariweb/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/LuminariMUD/luminariweb/actions/workflows/test.yml) [![Stars](https://img.shields.io/github/stars/LuminariMUD/luminariweb?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/luminariweb) ![TypeScript](https://img.shields.io/badge/TypeScript-React_%2B_Node-3178C6?style=flat-square&logo=typescript&logoColor=white) | **The browser gateway.** A first-party React client with an MSDP-driven HUD, accessible terminal experience, PWA capabilities, and a secure WebSocket-to-Telnet proxy. **[Launch it →](https://web.luminarimud.com/)** |
| 🔮 **[Intermud3](https://github.com/LuminariMUD/Intermud3)**<br><br>[![Stars](https://img.shields.io/github/stars/LuminariMUD/Intermud3?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/Intermud3) ![Python](https://img.shields.io/badge/Python-3.12%2B-3776AB?style=flat-square&logo=python&logoColor=white) ![I3](https://img.shields.io/badge/Intermud--3-v3-6F42C1?style=flat-square) | **The road between worlds.** An independent Python I3 gateway with MudMode/LPC framing, router state, network services, observability, and JSON-RPC APIs integrated directly with the C server. |
| 💬 **[discord-mud-chat](https://github.com/LuminariMUD/discord-mud-chat)**<br><br>[![Stars](https://img.shields.io/github/stars/LuminariMUD/discord-mud-chat?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/discord-mud-chat) ![JavaScript](https://img.shields.io/badge/JavaScript-Node.js-F7DF1E?style=flat-square&logo=javascript&logoColor=111111) ![Discord](https://img.shields.io/badge/Discord-bidirectional_chat-5865F2?style=flat-square&logo=discord&logoColor=white) | **The community bridge.** Bidirectional MUD ↔ Discord chat with channel mapping, reconnects, rate limiting, mention safety, logging, health checks, and container-ready operations. |
| 🗺️ **[wildeditor](https://github.com/LuminariMUD/wildeditor)**<br><br>[![CI](https://github.com/LuminariMUD/wildeditor/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/LuminariMUD/wildeditor/actions/workflows/ci.yml) [![Stars](https://img.shields.io/github/stars/LuminariMUD/wildeditor?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/wildeditor) ![Stack](https://img.shields.io/badge/React_%2B_FastAPI-spatial_editor-149ECA?style=flat-square&logo=react&logoColor=white) | **The cartographer's workshop.** A full-stack wilderness editor for drawing regions and paths against the game's spatial database, with strict shared types, validation, authentication boundaries, REST APIs, MCP tools, and an optional AI assistant. |
| 📚 **[Sage](https://github.com/LuminariMUD/sage)**<br><br>[![Code Quality](https://github.com/LuminariMUD/sage/actions/workflows/code-quality.yml/badge.svg?branch=main)](https://github.com/LuminariMUD/sage/actions/workflows/code-quality.yml) [![Stars](https://img.shields.io/github/stars/LuminariMUD/sage?style=flat-square&label=stars&color=C99846)](https://github.com/LuminariMUD/sage) ![GraphRAG](https://img.shields.io/badge/Python-GraphRAG-3776AB?style=flat-square&logo=python&logoColor=white) | **The living library.** A production-oriented GraphRAG lore platform combining PostgreSQL/pgvector, Neo4j, knowledge graphs, validation workflows, APIs, agents, and MCP to make the world's canon discoverable. |
| ✨ **Website &amp; community tooling** *(private)*<br><br>![Astro](https://img.shields.io/badge/Astro-website_%2B_wiki-BC52EE?style=flat-square&logo=astro&logoColor=white) ![Private](https://img.shields.io/badge/development-private-6E40C9?style=flat-square&logo=github&logoColor=white) | **The front door.** The full Astro-powered [LuminariMUD.com](https://luminarimud.com/) experience, wiki, project presentation, and community-facing services. |

## How the realm fits together

```mermaid
flowchart TB
    Players((Players & Builders))
    Website[Website + Wiki]
    GUI[LuminariGUI]
    Web[luminariweb]
    Core[Luminari-Source<br/>C23 Game Server]
    Discord[Discord Bridge]
    I3[Intermud3 Gateway]
    Editor[Wildeditor]
    World[(Spatial World DB)]
    Sage[Sage GraphRAG]

    Players --> Website
    Players --> GUI
    Players --> Web
    GUI -->|Telnet + MSDP| Core
    Web -->|WebSocket → Telnet| Core
    Discord <-->|Bidirectional chat| Core
    I3 <-->|JSON-RPC integration| Core
    Editor <-->|World authoring| World
    World <--> Core
    Sage <-->|Lore, APIs + MCP| Website
    Sage -->|World knowledge| Players
```

## The technology spellbook

<p align="center">
  <img alt="C" src="https://img.shields.io/badge/C23-A8B9CC?style=for-the-badge&logo=c&logoColor=111111" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111" />
  <img alt="Lua" src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white" />
  <img alt="Astro" src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" />
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Neo4j" src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="MCP" src="https://img.shields.io/badge/MCP-tools_%2B_APIs-7C3AED?style=flat-square" />
</p>

## Choose your doorway

| ⚔️ **Play** | 🧭 **Adventure with Mudlet** | 🛠️ **Build** |
| :---: | :---: | :---: |
| Jump straight into the [browser client](https://web.luminarimud.com/), or begin at [LuminariMUD.com](https://luminarimud.com/). | Install [LuminariGUI](https://github.com/LuminariMUD/LuminariGUI) for mapping, live gauges, chat tabs, spell tracking, and more. | Start with the server's [onboarding checklist](https://github.com/LuminariMUD/Luminari-Source/blob/master/docs/onboarding.md), then choose the layer that calls to you. |

## Join the party

The LumiVerse has room for **C hackers, world builders, frontend engineers, Python developers, lorekeepers, testers, technical writers, artists, operators, and curious players**.

- 🗡️ **Find your quest:** browse the [open issues across the organization](https://github.com/search?q=org%3ALuminariMUD+is%3Aissue+is%3Aopen&type=issues).
- 📜 **Read the map:** every public project keeps its own setup, architecture, testing, and contribution guidance close to the code.
- 🏗️ **Build the world:** begin with [Luminari-Source](https://github.com/LuminariMUD/Luminari-Source), [Wildeditor](https://github.com/LuminariMUD/wildeditor), or the [builder quickstart](https://github.com/LuminariMUD/Luminari-Source/blob/master/docs/world_game-data/BUILDER_QUICKSTART.md).
- 🔭 **Explore the whole ecosystem:** visit the [LuminariMUD repositories](https://github.com/orgs/LuminariMUD/repositories).

---

<p align="center">
  <strong>One persistent world · Eight connected systems · Countless stories still unwritten</strong>
</p>

<p align="center">
  <a href="https://luminarimud.com/">Website</a> ·
  <a href="https://web.luminarimud.com/">Play in Browser</a> ·
  <a href="https://github.com/LuminariMUD/Luminari-Source">Game Server</a> ·
  <a href="https://github.com/orgs/LuminariMUD/repositories">All Repositories</a>
</p>
