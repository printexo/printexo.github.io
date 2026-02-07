# 3D Printing Guide

This page provides detailed instructions for 3D printing all custom structural components of PrintExo.

## CAD Files

All CAD files required for 3D printing PrintExo are provided as open-source resources.

- **Printable STL files** for all structural components, organized by left/right assemblies and individual parts  
- **Editable Fusion 360 parametric models (.f3d)** for design inspection and modification  
- **Parametric export script (`PrintExo_code.py`)** that allows users to adjust the shoe-width parameter and automatically export a corresponding STL file from Fusion 360

👉 **Download CAD files:**  
[Google Drive – PrintExo CAD Release](https://drive.google.com/drive/folders/1tcYwJKkRYvDyukaBFUs_2lasKkoU8P6Q?usp=drive_link)





---

## 1. Overview

**Key points:**

- All custom parts are designed for **consumer-grade FDM printers**
- Primary material: **PLA** (PETG or carbon-fiber–reinforced filaments also compatible)

The following subsystems require 3D-printed components:

| Subsystem | Components |
|-----------|------------|
| Actuation module | Planetary gear stage, protective casing |
| Shank structure | Shank body, passive hinge |
| Shoe interface | Dorsal component, plantar guides |

### Printing Estimates (per leg)

| Item | Value |
|------|-------|
| Total print time | 1 day 23 hours 51 minutes |
| Model filament | 928.70 g |
| Support filament | 21.22 g |
| **Total filament** | **949.92 g** |
| Estimated cost | $23.74 |

> **Note:** Estimates based on 70% gyroid infill with supports. Actual values may vary depending on printer, slicer settings, and filament brand.

---

## 2. Required Printing Equipment

### Printer
- **Recommended:** Bambu Lab X1C (or equivalent enclosed FDM printer)
- Any consumer-grade FDM 3D printer is compatible

### Nozzle
- **Diameter:** 0.4 mm (standard)
- Hardened steel nozzle recommended for abrasive filaments

### Slicer Software
- Bambu Studio (for Bambu Lab printers)
- PrusaSlicer, Cura, or equivalent

### Optional
- Filament dryer (recommended for hygroscopic materials like PETG)
- Enclosed chamber (improves print consistency)

---

## 3. General Print Settings

| Parameter | Recommended Value | Notes |
|-----------|-------------------|-------|
| Layer height | 0.20 mm | Balance between speed and strength |
| Nozzle diameter | 0.4 mm | Standard |
| Infill pattern | Gyroid | Good omnidirectional strength |
| Infill ratio | 70% | For structural rigidity |
| Perimeters (walls) | 4 | Increases shell strength |
| Top/Bottom layers | 5 | Ensures solid surfaces |
| Support | Part-dependent | See Part-by-Part notes |
| Material | PLA | PETG or CF-PLA also compatible |
| Bed temperature | 60°C | For PLA |
| Nozzle temperature | 210°C | Adjust per filament brand |

---

## 4. Print Orientation & Strength Considerations

FDM prints exhibit **anisotropic strength** — they are weakest along the layer lines (Z-axis).

### Guidelines

1. **Load-bearing parts** should be oriented so that primary stresses act **parallel to the print bed** (X-Y plane), not perpendicular (Z-axis).

2. **Planetary gears** require careful orientation to ensure tooth strength and smooth meshing.

3. **Use brims** (5–10 mm) for parts with small footprints to prevent warping and improve bed adhesion.

4. **Avoid rafts** unless absolutely necessary — they can affect dimensional accuracy on mating surfaces.

### Critical Orientations

| Part | Recommended Orientation | Reason |
|------|------------------------|--------|
| Shank body | Vertical (standing) | Maximizes bending strength |
| Gear components | Flat (teeth facing up) | Preserves tooth geometry |
| Shoe interface | Flat | Ensures accurate mounting surfaces |

---

## 5. Part-by-Part Printing Notes

| Part Name | Quantity | Orientation | Support | Infill | Special Notes |
|-----------|----------|-------------|---------|--------|---------------|
| Sun gear | 1 | Flat | No | 70% | — |
| Planet gear | 3 | Flat | No | 70% | Print bearings separately |
| Ring gear | 1 | Flat | No | 70% | Check inner teeth quality |
| Carrier | 1 | Flat | Yes | 70% | Remove supports carefully |
| Motor casing | 1 | Upright | Yes | 50% | — |
| Shank body | 1 | Vertical | Yes | 70% | Orient for bending load |
| Hinge component | 2 | Flat | No | 70% | — |
| Dorsal interface | 1 | Flat | Yes | 70% | Size-specific |
| Plantar guide | 2 | Flat | No | 50% | — |

> **Note:** This table is an example. Refer to the CAD files for the complete part list.

---

## 6. Post-processing

After printing, perform the following steps:

### 6.1 Support Removal
- Use flush cutters or needle-nose pliers
- Be careful around gear teeth and mounting holes

### 6.2 Surface Finishing
- Light sanding (220–400 grit) on mating surfaces
- Focus on surfaces that interface with bearings or fasteners

### 6.3 Hole Preparation
- **Reaming:** Use appropriately sized drill bits to clean up holes
- **Tapping:** M3 holes may require tapping for secure bolt threads
- Use a hand tap to avoid cracking the plastic

### 6.4 Dimensional Verification
- Check critical dimensions with calipers
- Gear mesh should be smooth without binding
- Bearing press-fit should be snug but not overly tight

---

## 7. Common Printing Issues

| Issue | Possible Cause | Solution |
|-------|---------------|----------|
| Warping | Poor bed adhesion, no enclosure | Use brim, increase bed temp, use enclosure |
| Layer delamination | Under-extrusion, low temp | Increase nozzle temp, check filament quality |
| Poor gear tooth finish | Too fast, insufficient cooling | Reduce speed for outer walls, increase cooling |
| Holes too tight | Over-extrusion | Calibrate flow rate, or ream holes after printing |
| Holes too loose | Under-extrusion | Increase flow rate, or use smaller drill bit |
| Stringing | High temp, no retraction | Lower temp, enable/increase retraction |
| Z-seam visible | Slicer settings | Set seam position to "sharpest corner" or "rear" |

---

## Next Steps

After completing all prints and post-processing:

- [Assembly Guide](assembly.md) — Step-by-step assembly instructions
- [Bill of Materials](bom.md) — Verify all components are ready

### Having Issues?

- [Troubleshooting — Hardware Issues](../troubleshooting/hardware.md) — Print quality and fit problems
