# Changelog

All notable changes to Occulii releases are documented here.

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
