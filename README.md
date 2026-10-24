# Inventory Kit (`inventory_kit`)

Item & inventory model: ItemResource, ItemDB registry, a grid Inventory with stacking/quick-slots, and InventorySlot. No 2D/3D dependency.

Part of the **[godot-game-kit](https://github.com/duckenclaw/godot-game-kit)** modular
template ecosystem — a set of reusable Godot 4 addons shared across FPS,
third-person, 2D sidescroller and top-down game templates.

## Install

**Git submodule (recommended)** — this repo is root-layout, so it drops straight
into a project's `addons/`:

```bash
git submodule add https://github.com/duckenclaw/godot-inventory-kit addons/inventory_kit
git submodule update --init
```

Then enable **Inventory Kit** in *Project → Project Settings → Plugins*.

**Godot Asset Library** — an Asset-Library-compatible release (files wrapped under
`addons/inventory_kit/`) is published per tagged version; search for "Inventory Kit" in the
editor's AssetLib tab.

## Dependencies

none

## Versioning

Semantic versioning via git tags (`v1.0.0`). The Asset Library entry tracks tags.

## License

MIT — see [LICENSE](LICENSE).
