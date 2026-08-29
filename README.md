# Mack AI Home Systems — app repository

Home Assistant add-on repository for **MackCommand**.

**This repository contains configuration only — no source code.** MackCommand ships as a
pre-built container image, so a hub downloads a finished container rather than compiling
on an SD card.

| Channel | Slug | Who runs it |
|---|---|---|
| **MackCommand** | `mackcommand` | Every client hub. Stable. |
| **MackCommand (Edge)** | `mackcommand_edge` | The flagship only. Never a client. |

## Adding it to a hub

Settings → Apps → Add-on Store → ⋮ → Repositories → add this repository's URL.

The image is private, so the hub must first hold a read-only registry credential — see
the fleet runbook, `02_Home_Build/Fleet_Updates_Runbook.html`.
