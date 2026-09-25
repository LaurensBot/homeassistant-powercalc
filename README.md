# Powercalc Measure recordings: Roborock S7 Max Ultra

Robot `Q100TSC` (HA model `roborock.vacuum.a65`), dock `EWFD04HRR` (UK 230 V), HA 2026.9.3, Powercalc Measure app 0.7.1.
Recorder, complex profile, robot vacuum recipe, drying on. Meter: Shelly Plus Plug UK on the dock's mains lead.

| File | Contents |
|---|---|
| `record-1.jsonl.gz` | Daily run: charging, 2 routine cleans (vacuum only), 1 mop clean with 1 wash, 3 bin empties, ~3.5 h of a 4 h drying cycle. 11,878 samples. |
| `record-2.jsonl.gz` | Office mop clean: 2 washes, 1 bin empty, start of a second drying cycle. 990 samples. |
| `analyser.json` | Analyser output over both recordings (validation: held-out recording). |

Added dock entities: `switch.*_dock_mop_drying`, `binary_sensor.*_dock_mop_drying` (deprecated), `sensor.*_dock_mop_drying_remaining_time`, `sensor.*_dock_dock_error`. Powercalc's own estimated power/energy sensors for the vacuum were removed from the selection.
