# Snapmaker U1 calibration firmware — 2.1

**Maintainer: cheeky-bastard | Restored: 2026-11-14**

Personal Paxx-based firmware with independent T1/T2/T3 calibration and a guarded mixed-nozzle print-start workaround. T0 directs the operator to stock full calibration; clean/validate saves nothing.

Read the [usermod instructions](overlays/mods/cheeky_b52/README.md), [full calibration documentation](https://github.com/cheeky-bastard/Snapmaker-U1-Single-Tool-Calibration), and [Releases](https://github.com/cheeky-bastard/Fork-SnapmakerU1-Extended-Firmware_2.1/releases).

These are web UI macro buttons. In Mainsail, put the seven primary buttons in a **Tool Calibration** macro group and enable Standby visibility.

Pinned upstream: `4eda2d5191adca26c32033166fe5dfab150c2ce3`. Reviewed native/CFG payload hashes are unchanged. **2026-11-18 upstream update:** This source includes 19 newer Paxx develop commits: camera-stack changes, Spoolman/SpoolLink improvements, Pushraker notifications, and component updates. The stock firmware, calibration/CFG/nozzle payloads and source guards are unchanged. The new full-image CI run is pending; the previous restored image remains available in Releases with its original test record. On-printer acceptance of the new image is pending. Obtain verified configuration/native backups before persistent printer changes. Use normal operation without debug or factory mode.

## Attribution

Built from [Paxx's Extended Firmware](https://github.com/paxx12-snapmaker-u1/SnapmakerU1-Extended-Firmware). Upstream source history and notices are preserved. See [upstream README](README.upstream.md), [GPL-3.0](LICENSE), and [modification notice](overlays/mods/cheeky_b52/NOTICE.md).

Restored under `cheeky-bastard` on 2026-11-14. Historical source banners, copyright notices and exact native/CFG payload hashes are retained. Old account URLs in source comments and historical records identify provenance; current project links use the new account. The stable `cheeky_b52` mod namespace is retained for compatibility. No upstream PR is authorized.
