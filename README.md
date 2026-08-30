# Eaglercraft 1.16.5

Minecraft 1.16.5 compiled to WebAssembly, running entirely in the browser.
No install, no plugins, no account.

**▶ [Play](https://techyako.github.io/Eaglercraft-1.16.5/)**

---

## Builds

| Version | Target | Size | Link |
|---------|--------|------|------|
| **u3** *(current)* | WASM-GC | 44 MB | [play](https://techyako.github.io/Eaglercraft-1.16.5/u3/game.html) |
| u2-beta | WASM-GC | 53 MB | [play](https://techyako.github.io/Eaglercraft-1.16.5/u2/game.html) |

Each build is a single self-contained HTML file. Download it and it runs
offline — worlds are saved in your browser's local storage.

## What's new in u3

**Fixes**
- Hostile mobs now spawn correctly (light-level check was broken)
- Server no longer crashes when a crossbow mob attacks
- TPS freezing during play resolved
- Hurt flash, creeper charge-up, and smoke particles render correctly
- Enchanting table text and layout fixed

**Performance**
- Rendering optimizations — smoother frame times, fewer stalls while chunks stream

**Features**
- Screen recording
- Restored vanilla-quality sounds

## Requirements

- **WebAssembly GC** — Chrome or Edge 119+ (Firefox 120+ may work)
- **WebGL 2.0** with hardware acceleration enabled
- **~1 GB** of free memory available to the browser
- Desktop only — mobile is not supported

---

Not affiliated with Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Studios.
