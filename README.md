# Numbas

Waypoint collection of artificial reefs, wrecks, and dive/fishing spots off Florida, merged into a single GPX file for loading onto a GPS or chartplotter.

## Layout

```
sources/   Original GPX files, kept as-is
dist/      Merged output, ready to load
```

### Sources

| File | Waypoints | Contents |
|---|---|---|
| `Combined_Marine_Data.gpx` | 4,340 | Statewide artificial reef deployments. Each description lists material category (`MatCat`), depth, relief, tonnage, deploy date, and county. |
| `PinellasArtificials.gpx` | 124 | Pinellas County artificial reef sites (Clearwater, Dunedin, Indian Shores, etc.) with depth notes. |
| `PJs_numbas.gpx` | 367 | Personal waypoints with symbols (dive flags, wrecks, fishing areas). |

### Output

`dist/All_the_goods_v2.gpx` has 4,755 waypoints merged from the sources above, in GPX 1.1 format.

## Usage

Import `dist/All_the_goods_v2.gpx` into your GPS, chartplotter, or mapping app (Garmin, Navionics, OpenCPN, etc.).

## Ideas

- Assign `<sym>` icons by type (e.g. `MatCat: Vessel` → `Shipwreck`) so reefs, wrecks, and spots are distinguishable on the map.
