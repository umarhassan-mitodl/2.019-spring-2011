---
content_type: page
description: This section provides information on the first part of the design project
  for the course, including objectives, guidance, requirements, and resources.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Labs and Projects
parent_type: CourseSection
parent_uid: fb72b73a-bfba-c4d4-6140-60d96296b293
title: 'Part I Design: Ship Sizing and Hydrostatics'
uid: 30acc1fc-5a6b-a1db-57f4-da4c0e56683c
---

Objective
---------

To develop a preliminary design on hull form, ship sizing, arrangement of tanks and type of mooring; to compute weight distribution and hydrostatic quantities, to perform intact and damage stability analysis; and to conduct a general strength and structural design.

1.  General Arrangement and Hull/System Design  
      
    1.  Choose a proper ship hull form
    2.  Choose a proper mooring system
    3.  Decide the length, width, and height of the hull
    4.  Decide storage tank sizes and properly arrange tanks
    5.  Decide ballast tanks and their distributions
    6.  Discuss the topside arrangement
  
3.  Weight, Buoyancy and Stability  
      
    1.  Decide weight of lightship, weight of topside, weight of risers/moorings
    2.  Decide the total displacement, center of gravity, center of buoyancy, and radius of gyration for roll/pitch/yaw on 0% (with ballast), 50% (without ballast), and 100% (without ballast) loading
    3.  Perform intact stability analysis
    4.  Perform damage stability analysis with 3 different damages
  
5.  Local and Global Loading  
      
    1.  Compute global loading for ballasted, half and full storage tank cases
  
7.  General Strength and Structural Design  
      
    1.  Compute hog and sag moment to check with design criteria
    2.  Compute maximum shear force to check with design criteria
    3.  Compute maximum deflection to check with design criteria

Guidance for Part I design
--------------------------

### General Arrangement and Hull/System Design

_Hull form:_ start from a tanker to develop an FPSO hull form. The main part of the hull should be like a barge. It should have a tandem-stern (convenient for offloading) and a bow similar to that of a tanker. This type of hull is easy to be built. Resistance is of secondary concern. Good stability is required.

_Type of mooring system:_ Turret-point mooring (12 ~16 steel lines)—interior turret mooring or exterior turret mooring. Interior turret system: easy to maintain, smaller vertical motion (due to pitch), leading to longer ships (i.e. larger deck area). Exterior turret system: not increasing ship length, hard to maintain, larger vertical motion (due to pitch). Moon pool diameter = ~20m.

_Ship sizing: Length:_ ~300m, Beam: ~60m, Depth: ~30m (need enough displacement for storage, enough deck space for topside), Length/Beam smaller than that of transport tankers, hydrodynamic concern (to avoid large responses to wave action, green water on deck, wave slamming).

_Single/double hull:_ Double side, single/double hull on bottom. Ballast tanks, strength requirement, and environment protection.

_Tank arrangement:_ 15~20 storage tanks: 2~3 tanks in the transverse direction (maximum beam/length of tank decided by MARPOL (regulation 24), ABS rule, maximum length less than 50m due to sloshing concern), 2 slop tanks (~2% of storage capacity), 2 fuel tanks, ~2 off-spec tanks, utility space, ballast tanks on two sides (width = 2~3m) (capacity = ~ oil storage capacity/2.4) and/or bottom, 1 collision tank on the bow/stern for trim purpose. (You may also choose to place ballast tanks in the middle of the ship).

_Topside:_ relatively uniform distributed weight (production, accommodation, and helipad), make sure there is enough deck space for topside facilities. Accommodation should be placed at least 33m (100ft) away from process facilities. Minimum distance of process facilities to the main deck = 3m.

### Weight, Buoyancy and Stability

Weight of lightship (i.e. steel): 13-16% of displacement (or scaled from existing FPSO)  
Weight of topside: 7-8% of displacement (or scaled from existing FPSO)  
Weight of risers/moorings: ~10,000 tons  
Cargo deadweight (i.e. oil storage): ~ 75% of displacement  
Total displacement: TBA

Three loading conditions:  
0% (with ballast), 50% (without ballast) and 100% (without ballast) loading  
Intact stability analysis: using PARAMARINE™  
Damage stability analysis (with various damages): using PARAMARINE

### Local and Global Loading

Three cases: ballasted, half and full storage: output by PARAMARINE

### General Strength and Structural Design

Using 100-year wave: Consider the worst scenarios for sagging and hogging moment computations and shear force using PARAMARINE. Simple formulae will be provided for computing deflections. Check sagging/hogging bending moment, shear stress, and deflection to satisfy the criteria.

Extreme sagging condition: full load in crude storage tanks coupled with a wave of approximately the ship length with its trough amidships.

Extreme hogging condition: ballast condition coupled with a wave of approximately the ship length with its crest amidship.

Characteristics of the 100-year return period storm for the Gulf of Mexico

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
CHARACTERISTICS
{{< thclose >}}
{{< thopen >}}
REQUIREMENTS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Wind speed (knots)
{{< tdclose >}}
{{< tdopen >}}
80
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Current speed (knots)
{{< tdclose >}}
{{< tdopen >}}
2.1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Significant wave height (m)
{{< tdclose >}}
{{< tdopen >}}
12.2
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Maximum wave height (m)
{{< tdclose >}}
{{< tdopen >}}
22.8
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Wave period (sec)
{{< tdclose >}}
{{< tdopen >}}
14
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Resources for Part 1
--------------------

Intro to PARAMARINE ({{% resource_link 94224666-428c-007d-3d58-b399e6dc82c3 "PDF" %}})

PARAMARINE Tutorial 1 ({{% resource_link 2da6fa90-7a08-1053-254a-e5395b4b079d "PDF" %}})

PARAMARINE Tutorial 2 ({{% resource_link cc72f890-87cf-80c7-e2da-f0355c216bf4 "PDF" %}})

PARAMARINE Tutorial 3 ({{% resource_link bfb3a457-8297-5be2-001a-ae7a48f20f5b "PDF" %}})

PARAMARINE Tutorial 4 ({{% resource_link ecf9fab2-eee7-9234-4229-6e5d4fcc00fa "PDF" %}})

PARAMARINE Tutorial 5 ({{% resource_link 1c2d5838-c0fd-7247-d4a7-5b8b73b87564 "PDF" %}})

PARAMARINE Tutorial 6 ({{% resource_link 98e39d54-f906-40f5-55eb-2547feb2227d "PDF" %}})

PARAMARINE Tutorial 7 ({{% resource_link 618519b7-9bc9-e7ca-04a0-3d09882467ab "PDF" %}})

PARAMARINE Tutorial 8 ({{% resource_link 37dcd8f6-514b-fd01-433f-7ea95a2e0fef "PDF" %}})