# Design-check reports

Generated on 2026-10-09 using KiCad CLI 10.0.6 on the copied, unmodified source files.

- [ERC.json](ERC.json): all severities, including exclusions. Four warning records represent two unique GPIO1/GPIO2 single-pin label findings, duplicated as normal and excluded records. No error-severity records are reported.
- [DRC.json](DRC.json): all severities and schematic parity. Four excluded USB-C hole-clearance errors; zero non-excluded violations, unconnected items or schematic-parity findings.

Both reports list ignored checks from the saved project settings. No source rules or exclusions were changed. Copper zones were not saved/refilled as part of this packaging task. These are software-check snapshots, not hardware test reports or fabrication approval. See the [project guide](../README.md) for limitations.
