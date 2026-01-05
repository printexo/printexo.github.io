# Troubleshooting — Hardware Issues

This page provides solutions for common mechanical and hardware problems encountered when building or using PrintExo.

---

## 1. Mechanical Fit Problems

### Parts Do Not Fit Together

| Symptom | Possible Cause | Solution |
|---------|---------------|----------|
| Parts too tight | Over-extrusion, elephant's foot | Sand mating surfaces, calibrate flow rate |
| Parts too loose | Under-extrusion, shrinkage | Reprint with adjusted settings, use shims |
| Misaligned holes | Print warping, incorrect orientation | Reprint with brim, verify print orientation |

### Holes Too Tight or Too Loose

| Issue | Cause | Solution |
|-------|-------|----------|
| M3 bolt won't thread | Hole undersized or filled with stringing | Ream with 2.5 mm drill, tap with M3 tap |
| Bolt spins freely | Hole oversized, stripped threads | Use thread-locking compound, reprint part |
| Bearing won't press in | Hole undersized | Ream carefully, avoid cracking |
| Bearing falls out | Hole oversized | Use retaining compound (Loctite 648) |

### Interference Between Moving Parts

- **Check for:** Residual support material, stringing, over-extrusion blobs
- **Solution:** Carefully trim with flush cutters, sand contact surfaces
- **Prevention:** Increase clearance in CAD, improve print cooling

---

## 2. Gearbox Issues

### Excessive Backlash

| Cause | Solution |
|-------|----------|
| Worn gear teeth | Inspect and reprint affected gears |
| Loose bearing fit | Replace bearings, check housing dimensions |
| Sun gear not centered | Reassemble with proper alignment (see Assembly Guide) |

### Unusual Noise (Grinding, Clicking)

| Noise Type | Likely Cause | Solution |
|------------|--------------|----------|
| Grinding | Gear teeth interference, debris | Disassemble, clean, check tooth mesh |
| Clicking | Chipped tooth, foreign object | Inspect teeth, remove debris |
| Whining | Tight mesh, insufficient lubrication | Verify clearances, apply light grease |

### Jamming During Rotation

1. **Check sun gear centering** — misalignment causes binding
2. **Inspect planet gear bearings** — seized bearings lock rotation
3. **Verify ring gear alignment** — ensure it's seated properly
4. **Look for debris** — plastic shavings can jam teeth

---

## 3. Structural Failures

### Cracked Printed Parts

| Location | Likely Cause | Solution |
|----------|--------------|----------|
| Around bolt holes | Over-tightening | Reprint, use torque-limiting technique |
| Layer lines | Weak layer adhesion | Reprint with higher temp, slower speed |
| Stress concentration | Design issue | Reinforce with epoxy, report for CAD update |

### Layer Delamination

| Cause | Solution |
|-------|----------|
| Low nozzle temperature | Increase temp by 5–10°C |
| Fast print speed | Reduce speed for structural parts |
| Moisture in filament | Dry filament before printing |
| Poor bed adhesion (warping stress) | Use enclosure, increase bed temp |

### Deformed Components

| Symptom | Cause | Solution |
|---------|-------|----------|
| Warped flat surfaces | Heat, inadequate cooling | Reprint with better cooling, use enclosure |
| Bent shank | Overload during use | Inspect for cracks, reprint if compromised |
| Sagging overhangs | Insufficient support | Reprint with supports enabled |

---

## 4. Shoe & Shank Attachment Issues

### Calf Sleeve Slipping

| Cause | Solution |
|-------|----------|
| Sleeve too loose | Use smaller size or add padding |
| Smooth sleeve material | Add silicone grip strips |
| Excessive sweating | Use moisture-wicking liner |

### Lace Interface Loosening

| Symptom | Cause | Solution |
|---------|-------|----------|
| Interface shifts during walking | Laces not tight enough | Re-tension laces, double-knot |
| Laces slip through guides | Worn guide edges | Inspect guides, reprint if damaged |
| Uneven tension | Improper lacing pattern | Follow lacing guide in Assembly section |

### Discomfort or Pressure Points

| Location | Cause | Solution |
|----------|-------|----------|
| Top of foot | Dorsal interface too rigid | Add foam padding |
| Calf | Shank rotation | Readjust sleeve position, check alignment |
| Ankle | Misaligned axis | Verify device axis matches ankle axis |

---

## 5. General Diagnostic Checklist

Before troubleshooting, verify:

- [ ] All bolts are tightened (but not over-torqued)
- [ ] Bearings are properly seated
- [ ] No visible cracks or deformations
- [ ] Gearbox rotates smoothly by hand
- [ ] Hinge moves freely
- [ ] Shoe interface is securely attached
- [ ] Laces are properly tensioned
- [ ] Motor is unpowered during inspection
