# Build the Robot

This section describes how to **physically build PrintExo** based on its mechanical design, fabrication strategy, and assembly process.

The build pipeline is organized into:

1. understanding the design principles,
2. defining the Bill of Materials (BOM),
3. fabricating the 3D-printed components, and
4. assembling the full device.

---

## 1. Design Principles

PrintExo is designed with a primary objective:

> **to lower the practical barriers that impede researchers and educators from entering ankle exoskeleton research.**

To achieve this, the mechanical design follows three core requirements:

1. **FDM-only custom parts**  
   All custom structural components are manufacturable using consumer-grade desktop FDM 3D printers.

2. **Standard off-the-shelf hardware**  
   All non-printed components are standard, easily available off-the-shelf parts.

3. **Non-invasive shoe interface**  
   The device must interface with commercially available footwear **without permanent modification**.

Within these constraints, the system balances:

- sufficient mechanical rigidity for effective torque transmission  
- a form factor appropriate for experimental use  
- a modular architecture that supports rapid prototyping and iterations of assistance strategies  

---

## 2. Mechanical Architecture

PrintExo consists of three main mechanical subsystems:

### 2.1 Actuation module

The actuation module includes:

- a CubeMars AK60-6 V1.1 KV140 actuator (CubeMars, China),  
- an integrated motor driver,  
- a 3D-printed **1:4 planetary gear stage**, and  
- a protective casing.

The motor, planetary stage, and casing form a single actuation unit that transmits torque to the shoe interface.

---

### 2.2 Shank structure

The shank structure:

- extends vertically from the actuation module,  
- is mounted on the **lateral side** of the user’s lower leg, and  
- is secured using a **sports calf support sleeve**.

Design features:

- Although assistive torque is applied in the sagittal plane (plantarflexion/dorsiflexion), a **passive hinge** is included to allow frontal-plane inversion/eversion.  
- This hinge improves alignment with the user’s natural gait kinematics and helps mitigate off-axis loads that could otherwise cause mechanical damage.  
- The calf sleeve provides a long contact length to resist rotation and slippage, while distributing pressure evenly.  
- No custom-molded orthotics are required, which reduces fabrication complexity and remains consistent with the use of accessible components.

---

### 2.3 Shoe interface

The shoe interface uses a **lace-based integration strategy** to form a non-invasive but secure connection to the footwear.

Main elements:

- A rigid **dorsal component** that contours the midfoot and extends diagonally to the lateral side to connect with the planetary gear output.  
- During fitting, the shoe is partially unlaced, then relaced through:
  - guides in the dorsal interface component, and  
  - the original eyelets of the shoe.  

This procedure effectively sandwiches the interface between the shoe tongue and the tensioned laces, creating a stable bond.

Additional stabilization:

- **Auxiliary laces** are routed through guide holes on the plantar (sole) section of the interface and tightened across the bottom of the shoe.  
- This helps the device remain cinched to the shoe during dynamic walking.

Torque transmission:

- During plantarflexion assistance, the rigid dorsal structure pushes against the foot, converting actuator rotation into assistive force.  
- During swing or dorsiflexion, the lace tension maintains contact and returns the interface toward a neutral position without restricting natural ankle range of motion.

Scalability:

- The shoe interface is **parametrically designed**, enabling researchers to print discrete sizes that correspond to standard footwear dimensions.  
- Combined with lace-based attachment, this allows deployment across a wide variety of commercially available lace-up shoes and participant cohorts.

---

## 3. Fabrication Overview (FDM Printing)

All custom structural components of PrintExo are fabricated using **PLA filament**.

Rationale:

- PLA was chosen for its high availability and ease of printing, consistent with the goal of minimizing entry barriers.  
- The design remains compatible with higher-performance materials such as **PETG** or **carbon-fiber–reinforced filaments**.

Printing setup:

- Printer: Bambu Lab X1C (Bambu Lab, China)  
- Nozzle: 0.4 mm  
- Layer height: 0.20 mm  
- Infill pattern: 70% **gyroid**

Structural considerations:

- Due to the anisotropic strength of FDM printing, load-bearing components are oriented to avoid inter-layer shear as the dominant failure mode.

Open resources:

- Editable CAD files (`.f3d`)  
- Mesh files (`.stl`)  
- Print-ready files (`.gcode`)  

These are provided in an open-access repository to support transparency and reproducibility.

---

## 4. Assembly Overview

Hardware and fastening:

- PrintExo uses standardized commercial hardware for all load-bearing interfaces.  
- All fasteners are **unified to M3 bolts**, and a single roller bearing size is used throughout.  
- Components are joined via **screw-fastening**.

Assembly workflow:

1. Print all required PLA components.  
2. Perform basic post-processing:
   - remove supports,  
   - perform light sanding if necessary.  
3. Tap or drill pre-modeled holes to ensure precise fastener alignment.  
4. Install bearings and fit the planetary gear assembly.  
5. Assemble the shank structure and hinge.  
6. Attach the shoe interface and verify alignment with the actuator output.  
7. Mount the device on the calf sleeve and shoe for fitting.

Tools:

- Common hand tools (e.g., screwdrivers, hex keys).  
- A power drill can be used to speed up certain steps, such as drilling and tapping.

Documentation:

- A comprehensive **open-source assembly manual** is provided.  
- Additional guidance is included for modifying CAD or hardware choices to match locally available non-printable parts.

---

## 5. Where to Go Next

To actually build PrintExo, continue with:

- [Bill of Materials (BOM)](bom.md)  
- [3D Printing Guide](printing.md)  
- [Assembly Guide](assembly.md)  

These pages provide the specific part lists, printer settings, and step-by-step assembly procedures derived from the system design summarized above.
