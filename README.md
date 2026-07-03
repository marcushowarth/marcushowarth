# Hi, I'm Marcus Howarth

Java developer by trade. In my own time I build personal tools that connect AI to the real world — things I actually use, wired up to my own data.

---

## What I'm building

MCP servers — [Model Context Protocol](https://modelcontextprotocol.io) adapters that give AI assistants genuine capabilities beyond chat.

| Project | What it does |
|---------|-------------|
| [KanbanMCP](https://github.com/marcushowarth/KanbanMCP) | Connects Claude to [Kanboard](https://kanboard.org) — my self-hosted [kanban board](https://en.wikipedia.org/wiki/Kanban_board) for tracking tasks and projects |
| [MediaWikiMCP](https://github.com/marcushowarth/MediaWikiMCP) | Connects Claude to my personal MediaWiki instance — a self-hosted second brain for notes, projects and reference docs |

The goal: Claude can read my task board, update my wiki, and work with context about what I'm actually doing — rather than starting from scratch each conversation.

Both deploy via GitHub Actions → ECR → EC2, built on [Quarkus](https://quarkus.io) and compiled to [GraalVM](https://www.graalvm.org) native images (~10–20 MB resident).

---

## FIN OPTICS

A retirement projection app — [try it live](https://optics.howarth.eu). Split across three repos:

| Repo | Role |
|------|------|
| [fin-model](https://github.com/marcushowarth/fin-model) | Java modelling engine — the projection maths itself |
| [fin-optics-api](https://github.com/marcushowarth/fin-optics-api) | Quarkus-native REST API wrapping the engine |
| [fin-optics-ui](https://github.com/marcushowarth/fin-optics-ui) | Vue 3 front end — interactive ECharts, client-side persistence |

Same deploy shape as the MCP servers: GitHub Actions → ECR → EC2, Quarkus-native on GraalVM.

---

## Other interests

- Home automation — Home Assistant, Zigbee, MQTT, solar/battery monitoring with [foxess_modbus](https://github.com/nathanmarlor/foxess_modbus); early days also with [hass-mcp-server](https://github.com/ganhammar/hass-mcp-server) to give Claude direct access to Home Assistant
- Restoring bikes
- Java, Apache Camel, messaging and microservices

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/marcushowarth)
- [howarth.eu](https://howarth.eu)
