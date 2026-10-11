# Changelog

All notable changes to Occulii releases are documented here.

## 0.2.0 — 2026-10-10

- **Light mode.** Panels and Settings now come in light as well as dark, styled after Linear's light theme: white tiles on a soft gray panel, quiet hairlines, and chart colors re-tuned so they stay distinct and readable on white.
- **Follows your Mac.** A new Appearance setting offers System, Light or Dark. System is the default and switches with macOS, including while a panel is open. Menu bar items always match your menu bar.
- Hovering a tile now dims it slightly, and the tile whose details are open keeps a stronger outline.
- Cleaner charts: near-zero network and disk samples no longer draw a dotted line along the baseline.
- Settings switches and segmented controls are easier to read in light mode.

**Download:** `Occulii-0.2.0.dmg` from the release assets below.

## 0.1.0 — 2026-10-10

First public release.

- **One menu bar item, everything inside.** The overview panel shows CPU, memory, network, disk and sensors as tiles. Hover or click a tile and that module's full detail opens as a side pane beside the panel.
- **CPU:** user and system load as stacked-bar history, every performance and efficiency core by cluster, GPU load, load average, uptime and top processes.
- **Memory:** app, wired and compressed memory, memory pressure with history, swap and top processes.
- **Network:** live throughput and history per interface, local address and session totals.
- **Disk:** free space on the startup disk and other local volumes, read and write rates with history, bytes since boot, and processes ranked by disk activity.
- **Sensors:** CPU, GPU, SSD and battery temperatures, fan speeds (read-only), and battery charge and cycle count.
- **Separate menu bar items** for CPU, Memory, Network, Disk and Sensors are still there if you want them, in graph, value or minimal styles.
- **Light on resources.** One timer drives all sampling, detail is only read while a panel is open, and sampling stops while the display sleeps. With the default single item: about 0.05% CPU and an 11 MB memory footprint on an M1 Pro.
- Settings for refresh interval, temperature unit, accent color and launch at login.

**Download:** `Occulii-0.1.0.dmg` from the release assets below.
