# ARCML Specification

**ARCML (Adaptive Ribbon Console Markup Language)** is an open specification for **adaptive, content-driven user interfaces**.  
It defines *what* an interface means — not *how* it looks — so that renderers can automatically adapt to devices, inputs, and user contexts.

---

## What is ARCML?

ARCML is a declarative, JSON-based language that describes:
- **Content roles** (primary, secondary, contextual)
- **Actions and events** (grouped, leveled, categorized)
- **Intents and capabilities** (e.g. `media.play`, `map.route`, `feed.comment`)
- **Constraints and hints** (e.g. “emphasize visuals,” “minimum touch target size”)

Renderers then choose the most appropriate **patterns and layouts** automatically:
- On mobile → swipeable decks, bottom sheets, overlays  
- On desktop → split panes, lists, sidebars  
- On TV → full-bleed panels, remote-friendly focus models  

ARCML makes **content drive the interface**, not developer hard-coding.

---

## Goals

- ✅ **Universal** – works across web, mobile, desktop, and embedded  
- ✅ **Adaptive** – automatically adjusts to screen, input, bandwidth, accessibility  
- ✅ **Semantic** – describes meaning and intent, not pixels  
- ✅ **Accessible** – WCAG 2.2 AA compliance built-in  
- ✅ **Deterministic** – same document + context → same UI every time  
- ✅ **Future-proof** – JSON schema + patch/update model; optional YAML/DSL authoring  

---

## Getting Started

- 📖 [Draft Specification](./docs/spec-v0.1.md) (coming soon)  
- 🧩 [Reference Renderer](https://github.com/arcml.org/renderer) (React prototype)  
- 📝 [Examples](https://github.com/arcml.org/examples) — canonical ARCML documents  

---

## Community

- 🌍 Website: [https://arcml.org](https://arcml.org)  
- 💬 Join the discussion: (Discord/Slack link TBD)  
- 🐙 GitHub Organization: [github.com/arcml.org](https://github.com/arcml.org)  

---

## Contributing

ARCML is **community-driven**. You can help by:
- Opening issues with feedback, questions, or proposals  
- Submitting PRs to improve the spec or examples  
- Sharing use cases to expand the pattern catalog  

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## License

All ARCML specifications and reference implementations are released under the [Apache 2.0 License](./LICENSE).
