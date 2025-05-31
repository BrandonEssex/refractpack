# RefractPack – Official Plugin Repository for PrismX

**RefractPack** is the official plugin repository for [PrismX](https://github.com/prismx), offering modular extensions including timers, journaling feeds, UI tools, and command integrations.

---

## 🧩 Plugin Architecture

Plugins integrate with PrismX via:
- `manifest.json` registry
- `on_load()`, `on_key()`, `on_signal()` lifecycle hooks
- TUI slot rendering (`top-right`, `bottom-right`, `overlay`)
- Trusted sandboxed WASM or native `cdylib` formats

---

## 📦 Official Plugins

| Plugin         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Countdown (🕓) | Countdown timer with beam alert visuals                                      |
| Pomodoro (🍅)  | Focus timer with Zen panel and habit tracking                               |
| StickyNotes    | Detached quick-notes overlay panel (upgraded from Triage integration)       |
| JournalFeed    | Chronological journaling stream with timestamps and tag parsing             |

---

## 🚀 Usage

To activate a plugin in PrismX:
1. Add its entry to `refractpack/manifest.json`
2. Enable it via the PrismX Settings panel
3. Use Spotlight to invoke commands (`start`, `pause`, `tag`, etc.)

---

## 🌟 Roadmap

Planned modules include:
- RoutineForge (habit scheduler)
- Plugin Settings UI
- Plugin Dashboard Metrics
- ShardVault (encrypted workspace vaults)
