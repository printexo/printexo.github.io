# Bill of Materials (BOM)

This page lists all **non-printed components and printing consumables** required to build one PrintExo unit.
All custom structural parts are fabricated using 3D printing and are documented separately in the
[3D Printing Guide](printing.md).

---

## 1. Overview

PrintExo is designed to minimize sourcing complexity by:
- relying on **standard, off-the-shelf components**,  
- avoiding custom machining or proprietary parts, and  
- enabling regional substitution where possible.

The total hardware cost (excluding tools and the 3D printer) is approximately ~~ for one pair of PrintExo units.
All listed components can be sourced from common online retailers or local suppliers.
All costs in this BOM are listed in U.S. dollars (USD).


---

## 2. Printing Consumables

3D-printed parts are not listed individually in this BOM.
Instead, printing requirements are summarized as consumables.

| Item | Specification | Qty | Unit Cost | Example Source | Notes |
|:----:|:-------------:|:---:|:---------:|:--------------:|:-----:|
| P01 | PLA filament (1.0 kg) | 2 | $19.99 | [Bambu Store](https://kr.store.bambulab.com/products/pla-basic-filament?id=565422966019776519) | Any standard PLA filament is acceptable |
> **Note:** Detailed part lists, orientations, and print settings are provided in the [3D Printing Guide](printing.md).

---

## 3. Fasteners & Bearings

| Item | Specification | Qty | Unit Cost | Example Source | Notes |
|:----:|:-------------:|:---:|:---------:|:--------------:|:-----:|
| H01 | M3 bolt, 5 mm | 12 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221005179096/?KWSearch=m3&searchFlow=results2products&list=PageSearchResult) |  |
| H02 | M3 bolt, 12 mm | 8 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221005796349/) |  |
| H03 | M3 bolt, 18 mm | 6 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221005796372/) |  |
| H04 | M3 bolt, 20 mm | 8 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221005796383/) |  |
| H05 | M3 bolt, 22 mm | 48 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/110310898469/?list=PageCategory) | |
| H06 | M3 bolt, 40 mm | 4 | $0.05 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221300250577/?list=PageCategory) |  |
| H07 | Bearing (HK0810) | 8 | $2.71 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221000068571/?HissuCode=HK0810&srsltid=AfmBOopc_61bB8nqXv06_OH-1Fif4HUJUN-m0MQhErcm6FwjCQKK_I0m) |  |
| H08 | M3 plastic washer (spacer) | 2 | $0.42 | [MiSUMi](https://kr.misumi-ec.com/vona2/detail/221004999040/?srsltid=AfmBOoqMOtebLmETM_6xZZwp_zSu5yEmjtOMsrQxjlbbBfaBfQ7PFngH) |  |
> **Note:** Unit costs are approximate, normalized estimates for budgeting consistency; actual prices vary by supplier and purchase volume.




---

## 4. Actuator

| Item | Specification | Qty | Unit Cost | Example Source | Notes |
|:----:|:-------------:|:---:|:---------:|:--------------:|:-----:|
| A01 | CubeMars AK60-6 V1.1 KV140 | 2 | $ 298.90 | [CubeMars](https://www.cubemars.com/product/ak60-6-v1-1-kv140-robotic-actuator.html) | One per leg, integrated driver |
> **Note:** This BOM covers the exoskeleton hardware platform; electrical design and power supply configurations may vary by use case, so only the actuator is specified here.

---


## 5. Etcs

| Item | Specification | Qty | Unit Cost | Example Source | Notes |
|:----:|:-------------:|:---:|:---------:|:--------------:|:-----:|
| E01 | Calf compression sleeve | 2 | $ 16.99 | [Amazon](https://www.amazon.com/Vive-Calf-Brace-Compression-Circulation/dp/B0101BXKHM?th=1) | One per leg |
| E02 | Shoe laces (auxiliary) | 2 | $ 10.00 | [Amazon](https://www.amazon.com/Miscly-Round-Durable-Shoelaces-Hiking/dp/B0D98SB5JT?th=1&psc=1) |  |

---

## 6. Tools Required (Non-consumable)

The following tools are commonly required for assembly but are not included in the BOM cost.


| Tool | Notes |
|------|------|
| Hex key set | M3 fasteners |
| Screwdrivers | General assembly |
| Hand drill | Hole cleanup / tapping |
| M3 tap | Recommended |
| Flush cutters | Support removal |

---

## 7. Substitutions & Alternatives

- **Fasteners and bearings:**  
  Equivalent metric components may be substituted if dimensions match.

- **Filament:**  
  PETG or carbon-fiber–reinforced filaments are compatible but may require print setting adjustments.

> When deviating from the reference configuration, verify mechanical fit and electrical compatibility.

---

## Next Steps

- [3D Printing Guide](printing.md)  
- [Assembly Guide](assembly.md)
