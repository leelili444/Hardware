# MX_IMU Hardware Design (using KiCad 9)

This repository contains the MX_IMU V1.0 hardware design files, libraries, and production outputs created with KiCad.

## Overview

- Project: MX_IMU (IMU sensor module)
- Tool: KiCad (schematic capture and PCB layout)

## Key Files

- `MX_IMU.kicad_pro` - Project file
- `MX_IMU.kicad_sch` — Main schematic
- `MX_IMU.kicad_pcb` — PCB layout file
- `*.kicad_sym` — Symbol files, located in `library/symbols`
- `*.kicad_mod` (footprints) — Footprint libraries, located in `library/footprints`
- `3DModels/` — Component 3D STEP models for the PCB 3D viewer
- `production/` — Manufacturing outputs (BOM, placement files, IPC netlist, etc.)

## How to Open

1. Install KiCad on your computer (stable or LTS versions recommended).
2. Open the project via `File -> Open Project` and select `MX_IMU.kicad_pro`, or open `MX_IMU.kicad_sch` / `MX_IMU.kicad_pcb` directly.

## Libraries and 3D Models

- Custom symbols: `library/symbols`.
- Custom footprints: `library/footprints` (contained in `.pretty` directories).
- 3D STEP files: `library/3DModels` for the PCB 3D viewer and manufacturing visualization.

## Production Directory

The `production/` directory includes `bom.csv`, `positions.csv` (placement), `netlist.ipc`, and similar files that can be used for ordering or manufacturing.

