# scrapMetal3D

3D-scanned scrap metal samples (binary STL) for shape/material classification work.
All meshes are watertight exports.

## Structure

```
Al/   Aluminium samples   19 meshes   Al_1 - Al_10, Al_15 - Al_19, Al_22, Al_26, Al_28, Al_33
Bra/  Brass samples       18 meshes   Bra_1 - Bra_18
Cop/  Copper samples      14 meshes   Cop_1 - Cop_10, Cop_15 - Cop_18
```

51 meshes, 21,735,092 triangles, 1036.4 MiB total. All files are binary STL, units in millimetres.

## Files

| File | Material | Triangles | Size (MiB) |
|------|----------|-----------|------------|
| `Al/Al_1.stl` | Aluminium | 47,490 | 2.26 |
| `Al/Al_2.stl` | Aluminium | 400,022 | 19.07 |
| `Al/Al_3.stl` | Aluminium | 631,336 | 30.10 |
| `Al/Al_4.stl` | Aluminium | 222,902 | 10.63 |
| `Al/Al_5.stl` | Aluminium | 232,514 | 11.09 |
| `Al/Al_6.stl` | Aluminium | 271,016 | 12.92 |
| `Al/Al_7.stl` | Aluminium | 143,812 | 6.86 |
| `Al/Al_8.stl` | Aluminium | 196,652 | 9.38 |
| `Al/Al_9.stl` | Aluminium | 188,300 | 8.98 |
| `Al/Al_10.stl` | Aluminium | 1,043,594 | 49.76 |
| `Al/Al_15.stl` | Aluminium | 177,548 | 8.47 |
| `Al/Al_16.stl` | Aluminium | 185,986 | 8.87 |
| `Al/Al_17.stl` | Aluminium | 198,274 | 9.45 |
| `Al/Al_18.stl` | Aluminium | 104,484 | 4.98 |
| `Al/Al_19.stl` | Aluminium | 272,524 | 13.00 |
| `Al/Al_22.stl` | Aluminium | 290,242 | 13.84 |
| `Al/Al_26.stl` | Aluminium | 353,994 | 16.88 |
| `Al/Al_28.stl` | Aluminium | 286,688 | 13.67 |
| `Al/Al_33.stl` | Aluminium | 59,774 | 2.85 |
| `Bra/Bra_1.stl` | Brass | 1,055,672 | 50.34 |
| `Bra/Bra_2.stl` | Brass | 388,658 | 18.53 |
| `Bra/Bra_3.stl` | Brass | 721,658 | 34.41 |
| `Bra/Bra_4.stl` | Brass | 810,250 | 38.64 |
| `Bra/Bra_5.stl` | Brass | 1,398,440 | 66.68 |
| `Bra/Bra_6.stl` | Brass | 545,038 | 25.99 |
| `Bra/Bra_7.stl` | Brass | 266,330 | 12.70 |
| `Bra/Bra_8.stl` | Brass | 462,302 | 22.04 |
| `Bra/Bra_9.stl` | Brass | 300,952 | 14.35 |
| `Bra/Bra_10.stl` | Brass | 298,700 | 14.24 |
| `Bra/Bra_11.stl` | Brass | 515,920 | 24.60 |
| `Bra/Bra_12.stl` | Brass | 309,588 | 14.76 |
| `Bra/Bra_13.stl` | Brass | 258,182 | 12.31 |
| `Bra/Bra_14.stl` | Brass | 229,620 | 10.95 |
| `Bra/Bra_15.stl` | Brass | 287,758 | 13.72 |
| `Bra/Bra_16.stl` | Brass | 740,216 | 35.30 |
| `Bra/Bra_17.stl` | Brass | 498,398 | 23.77 |
| `Bra/Bra_18.stl` | Brass | 126,634 | 6.04 |
| `Cop/Cop_1.stl` | Copper | 1,133,968 | 54.07 |
| `Cop/Cop_2.stl` | Copper | 551,282 | 26.29 |
| `Cop/Cop_3.stl` | Copper | 572,528 | 27.30 |
| `Cop/Cop_4.stl` | Copper | 378,874 | 18.07 |
| `Cop/Cop_5.stl` | Copper | 764,486 | 36.45 |
| `Cop/Cop_6.stl` | Copper | 269,722 | 12.86 |
| `Cop/Cop_7.stl` | Copper | 159,346 | 7.60 |
| `Cop/Cop_8.stl` | Copper | 209,460 | 9.99 |
| `Cop/Cop_9.stl` | Copper | 396,836 | 18.92 |
| `Cop/Cop_10.stl` | Copper | 643,494 | 30.68 |
| `Cop/Cop_15.stl` | Copper | 525,824 | 25.07 |
| `Cop/Cop_16.stl` | Copper | 474,688 | 22.63 |
| `Cop/Cop_17.stl` | Copper | 393,512 | 18.76 |
| `Cop/Cop_18.stl` | Copper | 739,604 | 35.27 |

## Notes

- File names are normalised; the scanner's original export names are not preserved.
- Sample numbers are the scanner's own IDs, so the aluminium and copper numbering has gaps.
- The mesh first published as `Bra_1` is copper and now lives at `Cop/Cop_1.stl`; the mesh published as `Bra_2` is now `Bra/Bra_1.stl`. The current `Bra/Bra_2.stl` is a different, later sample.
- `Al_1.stl` is the original 47,490-triangle export and has not been re-scanned.
- Early commits in this repository hold superseded versions of some samples, including a `Cop_7` that was a second scan of the `Cop_10` sample.
