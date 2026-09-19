# scrapMetal3D

3D-scanned scrap metal samples (binary STL) for shape/material classification work.

## Structure

```
Al/   Aluminium samples (Al_1 - Al_6)
Bra/  Brass samples     (Bra_1 - Bra_6)
Cop/  Copper samples    (Cop_2 - Cop_6)
```

17 meshes, 1,803,598 triangles, 86.0 MB total. All files are binary STL.

## Files

| File | Material | Triangles | Size (MB) |
|------|----------|-----------|-----------|
| `Al/Al_1.stl` | Aluminium | 47,490 | 2.26 |
| `Al/Al_2.stl` | Aluminium | 123,559 | 5.89 |
| `Al/Al_3.stl` | Aluminium | 88,127 | 4.20 |
| `Al/Al_4.stl` | Aluminium | 57,403 | 2.74 |
| `Al/Al_5.stl` | Aluminium | 57,127 | 2.72 |
| `Al/Al_6.stl` | Aluminium | 75,829 | 3.62 |
| `Bra/Bra_1.stl` | Brass | 114,715 | 5.47 |
| `Bra/Bra_2.stl` | Brass | 72,717 | 3.47 |
| `Bra/Bra_3.stl` | Brass | 153,638 | 7.33 |
| `Bra/Bra_4.stl` | Brass | 153,992 | 7.34 |
| `Bra/Bra_5.stl` | Brass | 206,783 | 9.86 |
| `Bra/Bra_6.stl` | Brass | 85,337 | 4.07 |
| `Cop/Cop_2.stl` | Copper | 250,010 | 11.92 |
| `Cop/Cop_3.stl` | Copper | 119,353 | 5.69 |
| `Cop/Cop_4.stl` | Copper | 57,290 | 2.73 |
| `Cop/Cop_5.stl` | Copper | 95,482 | 4.55 |
| `Cop/Cop_6.stl` | Copper | 44,746 | 2.13 |

## Notes

- File names were normalised on upload (`AL_3.stl`, `COP_2.stl` and the long `Al_1_1_scan_watertight_47490tri_mm.stl` became `Al_3.stl`, `Cop_2.stl`, `Al_1.stl`). Mesh data is unchanged.
- There is no `Cop_1` — the copper set starts at `Cop_2`.
- Units are millimetres.
