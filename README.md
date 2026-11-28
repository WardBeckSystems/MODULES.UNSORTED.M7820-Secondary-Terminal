# M7820 Secondary Terminal · Unsorted

Ward-Beck Systems M7820. Wiki page: [M7820 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M7820.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 1 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 1 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

Not on Google Drive yet: `19xx - 7820-04-001 - SECONDARY TERMINAL FRONT & REAR LAYOUT - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M7820.stl`](MECHANICAL/M7820.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M7820)

- **Size:** 41 × 208.62 mm panel, 165 mm deep, 3.2 mm plate (assumed 41 mm wide (1.6"), the drawn panel's proportions)
- **From the drawing:** 16 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M7820 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M7820.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M7820.kicad_sym](KICAD/M7820.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
