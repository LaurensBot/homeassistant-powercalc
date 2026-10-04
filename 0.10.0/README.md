# Measure app 0.10.0 session: Roborock S7 Max Ultra

Recorder, complex profile, robot vacuum recipe. Runs 1 and 2 with drying on (app 0.10.0); runs 3 and 4 added with Record more, drying off (app 0.12.0). Entities as auto-selected by 0.10.0 (vacuum, battery, status, dock `dust_emptying` / `mop_washing` / `mop_drying` switches) plus `mop_drying_remaining_time`. The device ID in the headers is replaced with `redacteddeviceid`.

| File | Run | Charge | Drying | Bin empties | Mop washes |
|---|---|---|---|---|---|
| `record-1.jsonl.gz` | House mop | 66 → 100 % | 4 h 00 min | 1 | 8 |
| `record-2.jsonl.gz` | Vacuum-only drain, then one-room mop | 43 → 100 % | 4 h 00 min | 2 | 2 |
| `record-3.jsonl.gz` | Vacuum-only, charge with drying off | 53 → 100 % | none | 1 | 0 |
| `record-4.jsonl.gz` | Vacuum-only at Max+, charge with drying off | 25 → 100 % | none | 1 | 0 |
| `analyser.json` | All four runs, app 0.12.0 | | | | |
