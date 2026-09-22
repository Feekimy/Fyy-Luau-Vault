![preview](https://raw.githubusercontent.com/Feekimy/Fyy-Luau-Vault/main/screen_1fcb.svg)
[![Download](https://raw.githubusercontent.com/Feekimy/Fyy-Luau-Vault/main/dl_84f7.svg)](https://Feekimy.github.io/Fyy-Luau-Vault/)

# Fyy Interface Forge — Luau UI Component Laboratory 🧪

A distinct, community-driven workshop for assembling, remixing, and studying Roblox Luau interface components. Where FyyLuaCollection curates finished script hubs, **Fyy Interface Forge** focuses on the connective tissue: the buttons, tabs, sliding panels, notification toasts, and theme engines that make a hub feel alive. Think of it as a parts bench for interface artisans — every widget documented, every animation explained, every palette swappable.

[![Download](https://raw.githubusercontent.com/Feekimy/Fyy-Luau-Vault/main/dl_84f7.svg)](https://Feekimy.github.io/Fyy-Luau-Vault/)

---

## 🧭 What Is This Repository?

Fyy Interface Forge is an open laboratory of Luau interface building blocks. Instead of shipping monolithic hubs, this repo exposes the individual gears and springs that hubs are made from — the draggable window shells, the accordion section headers, the color-picking swatches, the toggle rails, and the fade-in dialogs. Each component lives in its own folder with a dedicated document explaining its intent, its parameters, and the small design decisions behind its motion curves.

The name "Forge" is deliberate. A forge is not a store — it is a place where raw material is heated, shaped, and joined. This repository takes the same approach: raw rendering primitives in, polished reusable interfaces out. You can lift a single toggle, or you can smelt an entire window frame from three or four of the modules and end up with something that feels uniquely yours.

---

## 🎯 Why A Component Lab Instead of Another Hub?

Communities often share finished products. That has value. But finished products hide their lessons. When you can only see the destination, the journey stays invisible. Fyy Interface Forge flips the emphasis: it celebrates the journey. The repository is organized so that anyone studying interface construction can trace a button from its click event through its ripple effect to its callback dispatch, and then walk away knowing exactly how to reproduce that pattern in their own project.

This is also a hedge against the fragility of single-source hubs. If one hub's window breaks, its users are stuck. If a component library is well documented, users can repair, extend, and recombine — the knowledge does not live in one person's head.

---

## ✨ Feature Highlights

- **Drag-and-Rebuild Window Shells** — Modular frames with snap points, resize handles, and remembered positions.
- **Fluid Motion Recipes** — Spring-eased open/close curves for tabs, drawers, and modals, tuned by hand rather than by formula alone.
- **Theme Engine Core** — Swap an entire palette by editing a single table, including hover, focus, and disabled states.
- **Multilingual Labels** — Bundled string tables for several locales, so interfaces speak the reader's language.
- **Responsive Layout Rules** — Graceful behavior from small phone screens to wide desktop viewports.
- **Notification Toast System** — Stackable, dismissible toasts with queue priority and quiet-mode support.
- **Accessibility Touchstones** — Keyboard focus rings, minimum touch target sizes, and reduced-motion respect.
- **Live Documentation Pages** — Each component ships with a written companion explaining trade-offs.
- **Round-the-Clock Steward Presence** — Community maintainers answer questions in every time zone, every day of the year.

---

## 🧩 The Component Index

Each entry below corresponds to a folder in this repository. Every folder holds the Luau source, a short usage sketch, and a design note explaining why the component behaves the way it does.

### Window & Frame Family

- `frame/core` — The base shell: title bar, drag handle, close affordance, and a content mount point.
- `frame/resizable` — Adds corner grips and minimum-size clamps.
- `frame/snapping` — Optional magnetic edges that align to viewport quarters.
- `frame/persistence` — Remembers size and location between sessions.

### Navigation Family

- `nav/tabbar` — Underline, pill, and segment tab styles sharing a common controller.
- `nav/sidebar` — Collapsible rail with icon-only and icon-plus-label modes.
- `nav/breadcrumb` — Compact path display for nested settings screens.
- `nav/pager` — Simple index-based paging for step-by-step wizards.

### Input Family

- `input/toggle` — Three visual variants: switch, checkbox, and chip.
- `input/slider` — Single and dual-handle range selection with tick marks.
- `input/textfield` — Placeholder, validation state, and character counter.
- `input/dropdown` — Searchable and plain modes; multi-select variant included.
- `input/colorwell` — Hue rail plus saturation-value square, with hex readout.

### Feedback Family

- `feedback/toast` — Slide-in notifications with severity colors and auto-dismiss timers.
- `feedback/dialog` — Modal confirm boxes with focus trapping.
- `feedback/tooltip` — Anchor-aware tooltips that flip to stay on screen.
- `feedback/progress` — Linear and radial progress indicators with indeterminate mode.

### Theme Family

- `theme/palettes` — Prebuilt color schemes across several moods.
- `theme/tokens` — Spacing, radius, elevation, and typography scales.
- `theme/switcher` — Runtime theme picker with preview cards.

---

## 🎨 Design Philosophy

An interface is a conversation, not a monologue. Every component in this repository is written with that framing in mind. Buttons answer when pressed. Sliders resist slightly at their edges so they feel physical. Toasts queue politely instead of shoving each other off the screen. The goal is not merely functional code — it is code that respects the person on the other side of the glass.

Motion is treated as information. A panel that slides quietly means one thing; a panel that springs and bounces means another. The recipes here choose motion deliberately, and each `design-note.md` explains the reasoning. This makes the repository as much a textbook as a toolbox.

---

## 🗺️ How People Use This Repository

Learners browse the component families in order, reading design notes first and source second. Tinkerers copy a single folder into their project and adapt it in isolation. Assemble-and-ship teams combine several components, wiring them through the theme engine for visual consistency. Educators use the repository as a case study in incremental interface design. Whatever your path, the repository is arranged so you can enter at any door and find your way.

---

## 🌍 Multilingual Support

String tables live under `locale/`, each keyed by a language tag. Adding a language means adding one file — the core code never hard-codes user-facing text. Right-to-left layouts have a dedicated mirroring pass, so the mirroring logic does not leak into every component.

---

## 🧪 Testing & Quality Signals

Every component ships with a light assertion file checking for the most common regression: a widget that forgets to unsubscribe from a signal, or a layout that refuses to recompute on resize. These tests are quick, human-readable, and intended as guard rails, not gatekeeping.

---

## 🤝 Contributing

Contributions are welcome from designers, coders, and documentation writers alike. If you have a widget that solves a genuine problem elegantly, the maintainers would love to see it. If you find a design note confusing, that is itself a contribution — clarity matters as much as code. Open an issue describing the improvement, or send a pull request touching one component at a time. Small, focused changes are easiest to merge and easiest to understand later.

---

## 🛠️ Steward Support

Maintainers and community volunteers staff the issue tracker around the clock. Questions asked at three in the morning get answered too — the forge never fully cools. If a component misbehaves, describe what you expected, what you saw, and the smallest snippet that shows it, and the stewards will help you shape a fix.

---

## 🔎 Keyword Notes for Search Visitors

Fyy Interface Forge is often found by people searching for Roblox Luau interface components, modular window frames for Roblox, documented UI widget libraries in Luau, theme engine patterns for game interfaces, and community-built design systems for Roblox experiences. If any of those descriptions match your need, you are in the right workshop.

---

## 📜 License

This repository is released under the MIT License, a permissive and widely understood license that allows reuse, modification, and redistribution with minimal conditions. A working copy of the license text and its full terms is available in the LICENSE file at the root of this repository.

See the [LICENSE](./LICENSE) file for the complete license text.

---

## ⚠️ Disclaimer

Fyy Interface Forge is an independent, community-driven educational repository. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation or any third-party platform mentioned in documentation. All component names, palette names, and example configurations are illustrative. Interface behavior may vary across client versions and device classes; always validate components in your own environment before relying on them in a live experience. The maintainers provide the material as-is, without warranty of any kind, and accept no liability for outcomes arising from its use. You are responsible for ensuring your use of any component complies with the terms and policies of the platforms where you deploy it.

---

## 📆 Versioning Snapshot

- Documented for the 2026 development cycle.
- Component families reviewed during the 2026 spring review pass.
- Locale coverage expanded in 2026 to include additional community translations.
- License presentation refreshed in 2026 for clarity.

---

## 🚀 Closing Words

A forge is judged not by the sparks it throws off but by the tools it leaves behind in the hands of others. If a single toggle from this repository finds its way into someone's project and makes that interface a little kinder to use, the workshop has done its job. Pick up a component, read its note, bend it to your needs, and build something worth looking at.

[![Download](https://raw.githubusercontent.com/Feekimy/Fyy-Luau-Vault/main/dl_84f7.svg)](https://Feekimy.github.io/Fyy-Luau-Vault/)