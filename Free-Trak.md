---
title: "Free-Trak Standards"
subtitle: "**Version:** 2026.10.23"
layout: default
outline_numbering: true
---

Free-Trak is a proposed N scale module standard that combines the ease of use and “bulletproof” connections of T-Trak™ with the module shape flexibility of Free-Mo. This increased flexibility aims to make modules easier to integrate into home layouts and lead to more operational interest for clubs. Wiring standards are based on Free-moN wiring standards. Though Free-Trak modules are physically compatible with T-Trak™, the reversible nature of Free-Trak modules means that they cannot be wired the same, and connecting Free-Trak to T-Trak™ will require an adapter harness or module. An article on ways to connect the two systems electrically will be available soon.

---

## Module Design

1. Modules may take any length and shape between endplates.
2. Total module width between endplates may vary, with a minimum of 6” wide.
3. Modules are designed to be set up on folding tables, not self standing.

## Endplates
1. Endplate widths must be a minimum of 6” (152mm) and maximum of 12” (305mm).
    1. Internal endplates for multi-piece modules that will always be assembled together may be of any width 6” or greater.
2. Endplates height must be 2 3/4” (70mm) tall with adjustable feet.
    1. Module height must remain at 2 ¾” tall with no obstructions for the first 1/2” from the mating end of the module.
3. Endplates must include a centered slot for wiring a maximum of 1/4” (6.35mm) above the bottom edge of the endplate, at minimum 1/2” (12.7mm) tall and 2” (25.4mm) wide with a minimum of 2” of clearance behind the slot to allow Anderson Powerpole connectors to be inserted easily.
    1. The slot may not be left open to the bottom of the endplate, as this may cause wires to lift modules or cause other vertical alignment issues.
4. Endplates must be constructed so as not to significantly warp.

## Track
1. Track at each end plate should be either single or double Kato™ Unitrack™ track, centered within the end plate.
    1. Double track modules should use standard 33mm Kato™ Unitrack™ spacing at module ends.
    2. More tracks are allowed at the end plate to allow for flexible prototype modeling, but the center one or two tracks shall be considered the main line for connecting to other modules. All additional tracks at endplates shall be spaced at 33mm center to center.
    3. While Unitrack™ is required at endplates, the track between the endplates can be of the modeler’s choice. If code 55 is used, it must accomodate larger flanged wheelsets.
2. Tracks must overhang the endplate by no less than 0.1mm and no more than 1mm at each endplate
3. The minimum turnout shall be #6 for the through-route
4. The minimum through-route curve radius shall be 11” (282mm)


## Wiring
1.  A DCC track power bus must run to each endplate of the module

    1. Insulated 12 gauge flexible stranded wire shall be used for the track bus.

    2. On double track modules, both tracks are fed from the same track bus with the same polarity (not opposite as in T-Trak™)

2. Power connections will be provided by Anderson Power Pole Connectors (APPCs)

    1. Two red 45 amp APPCs with 30 amp contacts are used for the track bus, stacked side by side with hoods to the left.

    2. The right APPC is wired to the right rail, the left APPC to the left rail.

    3. The end of the APPC must be able to extend a minimum of 3 inches beyond the faceplate, and retract fully inside the endplate.

3. Accessory bus – Optional

    1. Insulated 14 gauge wire may be used for the accessory bus.

    2. Module end terminations shall be 2 black APPCs mounted side by side with hoods up

    3. The user should be prepared to provide their own accessory power to the bus for their modules.

    4. Low amperage accessories may take power from the track bus.

    5. Remote only turnouts (with no manual override option) may not take power from the track.

3. Feeders

    1. Track feeders from the track bus to the rails shall be insulated 24 gauge or larger wire, kept as short as possible. Kato feeder tracks may be used.

    2. All community track must be powered through the track bus. Modules shall not rely on adjacent modules for power through the rail joiners for any section of track.

4. Data Connections – LCC optional, no rail data cables.
    1. LCC is RP at this time. Modules without LCC may be bypassed with longer LCC cables.
    2. DCC communication cables may be run directly between boosters on the tables or floor.
    3. Wireless throttles are strongly recommended. No throttle jacks should be mounted on modules to prevent modules from being moved when throttles are plugged in. If wired throttles are desired, a separate throttle communication line may be run to panels clamped to tables at intervals.

5. Ground wire – Not on modules
    1. Ground wire may be run directly between boosters on the tables or floor.

6. High Voltage
    1. High voltage is not allowed anywhere on modules for safety reasons.

## Resolution of Ambiguities
1. Any ambiguities in the physical standards shall be resolved such that they maintain compatibility with T-Trak™ layouts.

2. Any electrical ambiguities should be resolved to maintain compatibility with Free-moN wiring.

## Deviation from Standards
1. Any modules that deviate from the standard must be marked as such on the endplate mating face and contain a description of the deviations. Show layout planners must be made aware of all deviations ahead of time, and may choose to refuse to use the modules as part of a layout at their own discretion.

## Recommended Practices
RP 1. Standardized 3D-printable and laser cut endplate files are available [here](https://github.com/UncommonModels/Free-Trak-Templates)

RP 2. Turnouts should be wired for operation via LCC

RP 3. Use of a DCC system is strongly recommended

RP 4. Use of wireless throttles is strongly recommended

RP 5. Module mounted buttons or knobs should be mounted so that forces applied are in the vertical direction (downward), not horizontally, to prevent modules from sliding.

RP 6. Accessory power is best provided by a DCC booster.
 
---

**Changelog:**
 - Version 2026.10.23
     - Changed to date-based versioning
     - Numbering frozen
     - Settled on wiring similar to Free-Mo 
     - Some points rewritten for clarity
 - Version 0.9.1
     - Added more details regarding wiring
     - Clarified text of module dimension section and moved some suggestions to 
     - Numbering shuffled in most sections
     - Added metric values in addition to imperial where needed
 - Version 0.9.0
     - Added Changelog
     - Switched wiring to match T-Trak™ standard
     - Removed DCC system requirement
     - Added ambiguity resolution section
     - Added recommended practices section