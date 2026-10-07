# LDO Monolith Gantry Kits

[Repository overview](README.md)

Official milled [Monolith Gantry](https://github.com/Monolith3D/Monolith_Gantry) kits for Voron V2 and Voron Trident, manufactured by [LDO](https://ldomotion.com/).

Milled parts and supporting hardware for 2WD or AWD builds.

## What is Included

The kit includes the milled gantry parts and supporting hardware for the selected printer variant.

Key kit features:

- CNC/milled Monolith Gantry parts
- Parts for both 2WD and AWD configurations
- Robust removable tensioners for belting and pre-tensioning
- 9/10 mm belt support, depending on toolhead compatibility
- Genuine Gates pulleys and press-fit live-shaft idlers
- AWD front extrusion support for tool changer setups

The kit does not include belts, steppers, toolhead, probe, electronics, printer-specific frame or panel upgrades, or firmware mods.

## Printed Parts and Shared Files

Kit-specific prints, helper tools, and shared Monolith Gantry STL links are listed in [STLs](STLs).

The user manuals show where these printed parts and helper tools are used during assembly.

## Choosing 2WD or AWD

These kits are intended for standard 250-350 mm bed sizes.

2WD is the safer starting point for stock or lightly modified machines, especially with printed or modular toolheads, stock panels, or a frame that has not been stiffened.

AWD is most useful when the rest of the printer is ready to benefit from the added belt stiffness. That means the frame, panels, toolhead, and X-rail all need to support the higher-stiffness path.

> [!NOTE]
> AWD is not automatically better for every printer. On a less rigid machine, 2WD is probably the better configuration.

The user manuals show the configuration-specific 2WD and AWD assembly paths.

## Steppers

LDO 2504 Speedy Power steppers are the known-good baseline for this kit. LDO 2504 S45R "Monolith Edition" steppers are commonly bundled with the kits, and their shaft length is compatible across the Monolith Gantry platform.

Alternate NEMA17 steppers may work, but the stepper shafts need to be 5 mm in diameter and at least 37 mm long to work with the kit in double-shear. 8 mm shaft diameter can work, but only in single-shear.

Some Batch 1 kits may have documented stepper screw engagement problems. Check the [batch notes](#batch-notes) before installing motors.

## NP and FT

NP means No Protrusion. It keeps the gantry inside the stock frame or panel footprint by moving the relevant mounts and belt path inward.

FT means Full Travel. It prioritizes travel, but it may require clearance changes around panels, doors, or vertical extrusions.

Physical fit and performance recommendation are separate questions. A layout can fit inside the printer and still be the wrong performance path if the rest of the machine cannot use the added stiffness.

The user manuals include the detailed NP and FT layout explanation, clearance notes, and spacer placement.

## Toolhead Compatibility

See [Toolheads for Monolith](https://github.com/Monolith3D/Toolheads_for_Monolith) for compatible toolheads, belt clamps, and guidance on stiffness, clearance, and endstops.

## Rail Notes

The LDO milled XY-joints use MGN9H Y-carriages. Z0 / no preload is recommended for the Y-rails to avoid extra wear or binding. Other preload classes can work.

For the separate X-rail recommendation, see the [toolhead design guidelines](https://github.com/Monolith3D/Toolheads_for_Monolith/tree/main/Design_Guidelines#stiffness-and-center-of-mass).

## Batch Notes

Check the [batch notes](Docs/batch_notes.md) before assembly.

## Vendors

See the [gantry kit vendors](README.md#gantry-kits).

## Photos and Renders

- [V2 gantry kit photos](Images/README.md#v2-gantry-kit)
- [Trident gantry kit photos](Images/README.md#trident-gantry-kit)
- [Kit and part renders](Images/README.md#renders)

![LDO Monolith Gantry Kit VT render](Images/Renders/VT.png)
