# scrapMetal3D

3D-scanned scrap metal samples (binary STL) for shape/material classification work.
All meshes are watertight exports.

## Structure

```
Al/   Aluminium samples (Al_1 - Al_6)
Bra/  Brass samples     (Bra_1 - Bra_6)
Cop/  Copper samples    (Cop_2 - Cop_6)
```

17 meshes, 10,007,198 triangles, 477.2 MiB total. All files are binary STL, units in millimetres.

## Files

| File | Material | Triangles | Size (MiB) |
|------|----------|-----------|------------|
| `Al/Al_1.stl` | Aluminium | 47,490 | 2.26 |
| `Al/Al_2.stl` | Aluminium | 400,022 | 19.07 |
| `Al/Al_3.stl` | Aluminium | 631,336 | 30.10 |
| `Al/Al_4.stl` | Aluminium | 222,902 | 10.63 |
| `Al/Al_5.stl` | Aluminium | 232,514 | 11.09 |
| `Al/Al_6.stl` | Aluminium | 271,016 | 12.92 |
| `Bra/Bra_1.stl` | Brass | 1,133,968 | 54.07 |
| `Bra/Bra_2.stl` | Brass | 1,055,672 | 50.34 |
| `Bra/Bra_3.stl` | Brass | 721,658 | 34.41 |
| `Bra/Bra_4.stl` | Brass | 810,250 | 38.64 |
| `Bra/Bra_5.stl` | Brass | 1,398,440 | 66.68 |
| `Bra/Bra_6.stl` | Brass | 545,038 | 25.99 |
| `Cop/Cop_2.stl` | Copper | 551,282 | 26.29 |
| `Cop/Cop_3.stl` | Copper | 572,528 | 27.30 |
| `Cop/Cop_4.stl` | Copper | 378,874 | 18.07 |
| `Cop/Cop_5.stl` | Copper | 764,486 | 36.45 |
| `Cop/Cop_6.stl` | Copper | 269,722 | 12.86 |

## Notes

- File names are normalised (`Al_1.stl` ... `Cop_6.stl`); the scanner's original export names are not preserved.
- There is no `Cop_1` — the copper set starts at `Cop_2`.
- `Al_1.stl` is the original 47,490-triangle watertight export and was not re-scanned; every other mesh was re-exported.
- The first commits in this repository hold an earlier, lower-resolution version of the same 17 samples.
