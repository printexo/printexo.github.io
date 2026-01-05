# Assembly Guide

This guide describes how to assemble **PrintExo** from 3D-printed components, off-the-shelf mechanical parts, and electronics.

---

## 1. Overview

PrintExo uses a modular architecture organized into three main subsystems:

| Subsystem | Description |
|-----------|-------------|
| Actuation module | Motor, planetary gear stage, protective casing |
| Shank structure | Vertical frame, passive hinge, calf attachment |
| Shoe interface | Dorsal component, plantar guides, lace integration |

Assembly follows a bottom-up approach: gearbox → actuation module → shank → shoe interface.

---

## 2. Before You Begin

### Checklist

- [ ] All 3D-printed parts completed and post-processed
- [ ] All BOM components available (bearings, fasteners, motor)
- [ ] Required tools prepared
- [ ] Clean, well-lit workspace

### Recommended Preparation

1. **Verify printed parts** — check for warping, incomplete features, or layer defects
2. **Ream all holes** — use appropriate drill bits to clean up M3 holes
3. **Tap threads** — tap M3 holes where bolts will be inserted
4. **Dry-fit bearings** — ensure press-fit is snug but not cracked

---

## 3. Required Tools

| Tool | Size/Spec | Purpose |
|------|-----------|---------|
| Hex key set | 2.5 mm (for M3) | Tightening bolts |
| Screwdriver | Phillips / Flat | General fastening |
| Drill bits | 2.5 mm, 3.0 mm | Hole reaming |
| Hand tap | M3 × 0.5 | Threading holes |
| Needle-nose pliers | — | Support removal, small parts |
| Calipers | — | Dimensional verification |
| Power drill (optional) | — | Speeds up drilling/tapping |

---

## 4. Assembly Steps

### Step 1 — Planetary Gearbox Assembly

1. Gather sun gear, planet gears (×3), ring gear, and carrier
2. Install bearings into each planet gear
3. Place sun gear at center of carrier
4. Position planet gears around sun gear, ensuring teeth mesh properly

   > **Caution:** Use the planet gears to verify the sun gear is perfectly centered. Even slight misalignment can cause binding, uneven wear, or gear failure. Rotate the assembly by hand and confirm all planet gears contact the sun gear evenly before proceeding.

5. Lower ring gear over the assembly
6. Verify smooth rotation without binding

### Step 2 — Actuation Module Assembly

1. Mount the CubeMars AK60-6 motor to the motor casing
2. Secure with M3 bolts
3. Attach planetary gearbox output to motor shaft
4. Install protective casing cover
5. Verify motor spins freely and gearbox output rotates correctly

### Step 3 — Shank Structure Assembly

1. Assemble shank body components
2. Install passive hinge for inversion/eversion
3. Connect shank to actuation module output
4. Verify hinge allows frontal plane motion
5. Check overall alignment

### Step 4 — Shoe Interface Assembly

1. Attach dorsal interface component to gearbox output
2. Install plantar guides on bottom of interface
3. Verify rigid connection and correct orientation

### Step 5 — Final Integration

1. Thread shoe laces through dorsal interface guides
2. Relace through original shoe eyelets
3. Route auxiliary laces through plantar guide holes
4. Mount shank to calf sleeve
5. Don device and verify fit

---

## 5. Alignment & Fit Verification

After assembly, perform the following checks:

### Mechanical Checks

| Check | Expected Result |
|-------|-----------------|
| Gearbox rotation | Smooth, no grinding or binding |
| Hinge movement | Free inversion/eversion motion |
| Motor operation | Spins without obstruction |
| Shoe interface rigidity | No wobble at mounting point |

### Fit Checks

- [ ] Shank aligned with lateral side of lower leg
- [ ] Ankle joint axis approximately aligned with device axis
- [ ] Calf sleeve secure but comfortable
- [ ] Laces tensioned evenly across dorsal interface
- [ ] No pinch points during range of motion test

---

## 6. Safety Notes

- **Do not over-tighten** M3 bolts — PLA can crack under excessive torque
- **Inspect all structural joints** before human testing
- **Check for pinch points** around hinge and gearbox
- **Verify motor is unpowered** during mechanical assembly
- **Perform bench test** before wearing the device
- **Start with zero-torque mode** for initial human trials

---

## 7. Next Steps

After completing mechanical assembly, proceed to:

- [Electronics & Control Overview](../elec_control/index.md)
- [Motor Driver & Configuration](../elec_control/motor.md)
- [Wiring](../elec_control/wiring.md)
- [Running Demo](../elec_control/demo.md)
