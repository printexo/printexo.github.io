# Troubleshooting — Assembly Issues

This page provides solutions for common problems encountered during PrintExo assembly.

---

## 1. General Assembly Errors

### Incorrect Part Orientation

| Symptom | Cause | Solution |
|---------|-------|----------|
| Parts don't mate | Flipped or rotated incorrectly | Check CAD reference, reassemble |
| Asymmetric fit | Left/right parts swapped | Verify part labels, reinstall correctly |
| Holes don't align | Part upside down | Disassemble and flip part |

### Missing Components

| Issue | Checklist |
|-------|-----------|
| Spacers missing | Verify BOM, check packaging |
| Washers missing | Use BOM checklist before assembly |
| Bearings forgotten | Disassemble and install before continuing |

> **Tip:** Lay out all parts and cross-check with BOM before starting assembly.

### Screws Not Aligning with Holes

| Cause | Solution |
|-------|----------|
| Print warping | Reprint affected part with brim |
| Wrong screw length | Verify screw spec against BOM |
| Hole not drilled/tapped | Ream and tap before assembly |
| Parts shifted during tightening | Loosen all screws, realign, retighten evenly |

---

## 2. Planetary Gear Assembly Issues

### Planet Gears Not Rotating Freely

| Cause | Solution |
|-------|----------|
| Bearing not seated | Press bearing fully into housing |
| Debris in bearing | Clean with compressed air |
| Bearing seized | Replace bearing |
| Gear teeth binding | Check sun gear centering |

### Sun Gear Misalignment

| Symptom | Cause | Solution |
|---------|-------|----------|
| Uneven rotation resistance | Sun gear off-center | Use planet gears to verify centering (see Assembly Guide) |
| Clicking during rotation | Partial tooth engagement | Reassemble with proper alignment |
| Premature wear | Continuous off-axis loading | Disassemble, inspect, realign |

> **Caution:** Even slight misalignment causes binding, uneven wear, or gear failure. Always verify centering before installing ring gear.

### Ring Gear Installation Problems

| Issue | Cause | Solution |
|-------|-------|----------|
| Won't seat fully | Planet gears mispositioned | Rotate planets to align with ring gear teeth |
| Tight fit | Print tolerance | Lightly sand ring gear outer surface |
| Loose fit | Oversized housing | Use shim or retaining compound |

---

## 3. Fastener Problems

### Stripped Threads

| Cause | Solution |
|-------|----------|
| Over-tightening | Reprint part, use thread insert (heat-set) |
| Cross-threading | Back out, realign, restart carefully |
| Repeated assembly/disassembly | Install brass thread inserts |

### Over-Tightened Bolts

| Symptom | Result | Solution |
|---------|--------|----------|
| Bolt won't turn | Threads seized | Apply heat carefully, back out slowly |
| Part cracked | Excessive torque | Reprint part, use lower torque |
| Head stripped | Wrong tool size | Use correct hex key, replace bolt |

> **Prevention:** Tighten until snug, then 1/4 turn more. PLA does not require high torque.

### Cross-Threading

| Symptom | Solution |
|---------|----------|
| Bolt goes in crooked | Back out completely, realign, restart |
| Resistance increases suddenly | Stop immediately, check alignment |
| Threads damaged | Re-tap hole, or reprint part |

### Bolt Length Issues

| Issue | Cause | Solution |
|-------|-------|----------|
| Bolt too short | Wrong spec | Check BOM, use correct length |
| Bolt too long | Bottoming out | Add washer, or use correct length |
| Bolt protrudes dangerously | Incorrect part stackup | Verify assembly order |

---

## 4. Bearing Installation Issues

### Bearing Won't Press In

| Cause | Solution |
|-------|----------|
| Hole undersized | Ream carefully with appropriate bit |
| Bearing cocked | Align squarely, press evenly |
| Debris in hole | Clean hole before installation |

### Bearing Falls Out

| Cause | Solution |
|-------|----------|
| Hole oversized | Use retaining compound (Loctite 648) |
| Housing cracked | Reprint part |
| Wrong bearing size | Verify bearing spec against BOM |

### Bearing Doesn't Spin Freely

| Cause | Solution |
|-------|----------|
| Over-pressed | Bearing deformed — replace |
| Contamination | Clean with isopropyl alcohol |
| Wrong bearing type | Verify bearing spec (must be appropriate type) |

---

## 5. Post-Assembly Functional Checks

Perform these checks after completing assembly:

### Gearbox Rotation Test

| Check | Expected | If Failed |
|-------|----------|-----------|
| Rotate output by hand | Smooth, consistent resistance | Check gear alignment, bearing seating |
| Full 360° rotation | No binding at any position | Look for debris, check tooth mesh |
| Backdrive input | Should rotate with gear ratio resistance | Verify all gears engaged |

### Hinge Alignment Test

| Check | Expected | If Failed |
|-------|----------|-----------|
| Inversion motion | Free movement, no binding | Check hinge pin, clear debris |
| Eversion motion | Free movement, no binding | Verify hinge components aligned |
| Return to neutral | Smooth return | Check for friction, misalignment |

### Shank-to-Actuator Connection

| Check | Expected | If Failed |
|-------|----------|-----------|
| No wobble | Rigid connection | Tighten fasteners, check mating surfaces |
| Aligned with output | Straight torque transmission | Reassemble with proper alignment |

### Shoe Interface Check

| Check | Expected | If Failed |
|-------|----------|-----------|
| Rigid mounting | No play at connection point | Tighten bolts, verify fit |
| Lace tension | Even across all guides | Relace following guide pattern |
| Plantar guides secure | No looseness | Verify installation |

---

## See Also

- [Troubleshooting — Hardware Issues](hardware.md)
- [Assembly Guide](../hardware/assembly.md)
- [3D Printing Guide](../hardware/printing.md)
