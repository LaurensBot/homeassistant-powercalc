# Measure app 0.10.0 session: Roborock S7 Max Ultra

Recorder, complex profile, robot vacuum recipe, drying on. Entities as auto-selected by 0.10.0 (vacuum, battery, status, dock `dust_emptying` / `mop_washing` / `mop_drying` switches) plus `mop_drying_remaining_time`. The device ID in the headers is replaced with `redacteddeviceid`.

| File | Run | Charge | Drying | Bin empties | Mop washes |
|---|---|---|---|---|---|
| `record-1.jsonl.gz` | House mop | 66 → 100 % | 4 h 00 min | 1 | 8 |
| `record-2.jsonl.gz` | Vacuum-only drain, then one-room mop | 43 → 100 % | 4 h 00 min | 2 | 2 |
| `analyser.json` | Both runs, held-out recording | | | | |
