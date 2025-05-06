# PCB

Board size: 50.29x91.19 mm (1.98x3.59 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: HAL lead-free
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      | White            |               |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      | Green            |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | core                 |                  |          1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   | Green            |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   | White            |               |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.25 mm (10 mils)

- By design rules: 0.25 mm (10 mils)

Drill: 0.4 mm (16 mils)

- Vias: 0.4 mm (16 mils) [Design: 0.4 mm (16 mils)]
- Pads: 0.6 mm (24 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.6/0.3 mm (24/12 mils)

- By design rules: 0.5/0.3 mm (20/12 mils)
- Micro via: yes [0.2/0.1 mm (8/4 mils)]
- Buried/blind via: yes
- Total: 34 (thru: 34 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.1 mm (4 mils)

- By design rules: 0.2 mm (8 mils)

Eurocircuits class: 6C
- Using min drill 0.35 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 1/13 (SMD + THT)
- Bottom: 31/0 (SMD)

Defined tracks:

- 0.25 mm (10 mils)
- 0.25 mm (10 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.8 mm (31 mils)
- 1.0 mm (39 mils)

Used tracks:

- 0.25 mm (10 mils) (310) defined: yes
- 0.3 mm (12 mils) (2) defined: yes
- 0.4 mm (16 mils) (27) defined: yes
- 0.5 mm (20 mils) (118) defined: yes
- 0.8 mm (31 mils) (18) defined: yes
- 1.0 mm (39 mils) (114) defined: yes

Defined vias:


Used vias:

- 0.6/0.3 mm (24/12 mils) (Count: 34, Aspect: 2.7 A) defined: no

Holes (excluding vias):

- 0.5 mm (20 mils) (2)
- 0.8 mm (31 mils) (4)
- 1.0 mm (39 mils) (146)
- 1.1 mm (43 mils) (8)
- 3.2 mm (126 mils) (4)

Oval holes:

- 0.55x1.2 mm (22x47 mils) (2)
- 0.85x1.4 mm (33x55 mils) (2)

Drill tools (including vias and computing adjusts and rounding):

- 0.4 mm (16 mils) (34)
- 0.6 mm (24 mils) (2)
- 0.65 mm (26 mils) (2)
- 0.8 mm (31 mils) (2)
- 0.9 mm (35 mils) (2)
- 0.95 mm (37 mils) (2)
- 1.1 mm (43 mils) (146)
- 1.2 mm (47 mils) (8)
- 3.3 mm (130 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Top    |               2 |      18.20 |      0.09 |
| Bottom |             134 |     177.38 |      0.88 |
| Total  |             136 |     195.58 |      0.97 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



