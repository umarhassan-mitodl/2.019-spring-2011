---
content_type: page
description: This section provides information on labs and projects, including objectives,
  procedures and schedule, design tools and applications, design requirements, main
  design areas, and design project references.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Labs and Projects
uid: fb72b73a-bfba-c4d4-6140-60d96296b293
---
## Objective

The objective is to develop a preliminary design of a Floating, Production, Storage, and Offloading (FPSO) vessel. This facility is self-contained and processes, stores, and offloads crude oil products. The vessel operation site is the deep water of Gulf of Mexico. The scope of this project is limited to designing a stable, weathervaning hull, and single-point mooring system. ABS and API guidelines are used to provide structural requirements and safe mooring sizing.

## Procedure and Schedule

The whole project is divided into three parts. {{% resource_link "30acc1fc-5a6b-a1db-57f4-da4c0e56683c" "Part I" %}} focuses on ship sizing and hydrostatics and addresses main design areas (a), (b), (c), and (d), shown below. {{% resource_link "3193fb9c-ad91-359e-2ccc-ce828c451176" "Part II" %}} focuses on seakeeping analysis and addresses design area (e). {{% resource_link "5e53764d-3f62-6170-707c-d53c8a26ab64" "Part III" %}} focuses on mooring system design and addresses design areas (f) and (g).

The project is to be completed in team with each individual responsible for the report and discussion of a separate subject. Each team contains 2~3 members. A draft report for each design subject and a final report and presentation for the whole design project are required.

## Design Tools and Applications

Three pieces of design software were used for the design project. They are: PARAMARINE™ for hull form design and stability analysis, WAMIT® for sea-keeping performance analysis, and RISER-SIM for mooring system design. Access to this software is restructured; alternative software options for completing this project are A, B, and C.

*PARAMARINE*: PARAMARINE is software developed by Qinetiq. With the aid of this software most, of the spokes of the ship design spiral were addressed. The design was based on various rules such as the pertinent for FPSOs classification rules of ABS, API, MARPOL, etc. (see Design Project References below). The rules were presented to the students in parallel with the software instructions. The key procedures in the application of PARAMARINE for the project are:

- Initially the software was used to develop the hull form of the FPSO. The students were taught how to create a hull and fair the lines. In order to assess the fairness of the hull the lines drawings were generated with PARAMARINE: profile, body plan, and half-breadth were created.
- Then, the internal subdivision was designed based on the calculations performed in a homework assignment. Decks and transverse and longitudinal bulkheads were added to the design.
- Subsequently the tank layout was created. Major tanks (such as oil and ballast tanks) were generated following the internal subdivisions created. Capacities were calculated to make sure that they met the payload requirements. Major building blocks were added to the design, the most important of which were the turret mooring system, the process facility, and the accommodation. At this stage, the students were taught how to produce 2D drawings that would enhance the presentation of their design.
- After completing the geometry of the vessel hydrostatic characteristics, curves were calculated for a number of different drafts and trim angles. Subsequently, various loading conditions were defined. Based on these loading conditions, cases of intact and damaged stability were analyzed: three different damaged stability cases were analyzed for each loading condition, and various criteria for both intact and damaged stability were examined in order to make sure that the stability requirements were satisfied.
- The next step was to perform a longitudinal strength analysis of the design. Load distribution was estimated for calm water, sagging and hogging conditions. Shear forces and bending moments were calculated. The structural elements that comprise the ship structure were then defined, ensuring that the design satisfied the criteria for maximum stress. A one-year operating condition and a one hundred-years surviving condition were considered. Finally, a midship section was generated.
- The final work done with PARAMARINE was a design for production analysis. Production blocks, sub-assemblies and individual parts were used to form a hierarchy representing the actual building process of a shipyard.

*WAMIT:* Though PARAMARINE has the capability of sea-keeping analysis for floating ships, it does not provide the prediction of wave drift loads on the ship, which is needed in the design of mooring system. (Nevertheless, the students were taught on the use of PARAMARINE for sea-keeping analysis). For this project, thus, sea-keeping performance of the FPSO designed was analyzed by WAMIT, which has been evolving as a standard tool for sea-keeping analysis in the offshore industry. WAMIT was run on a Linux machine in the Athena computing environment of MIT. The students could either directly or remotely access the software. In different loading, operation, and surviving conditions, this analysis tool provides results for hydrodynamic coefficients, RAOs, and RMS motions of the FPSO.

*RISER-SIM:* This software was used to perform the analysis of a mooring line in dynamic ocean environment. It provides a prediction of line configuration and tension distribution along the line under various loading conditions. From this analysis, students obtained the loading-excursion relation of the mooring system, which is essential information for optimizing the mooring design.

## Design Requirements

Field performance period: 20 years

Daily production: ~ 150, 000 bbls

Storage capacity: ~ 2,000,000 bbls

Offloading routine: ~ 10 days

Water depth: ~1000 meters

Operation condition: 1-year storm (wind/current/wave)

Survival condition: 100-year storm (wind/current/wave)

Operation condition (1-year return period):

- Wind speed: 15.0 m/s
- Current speed: 1.2 m/s
- Significant wave height (Hs): 4.0 m
- Peak wave period (Tp): 10.0 s

Survival condition (100-year return period):

- Wind speed: 40.0 m/s
- Current speed: 1.5 m/s
- Significant wave height (Hs): 12.0 m
- Peak wave period (Tp): 14.0 s

## Main Design Areas

1. General arrangement and overall hull/system design
2. Weight, buoyancy and stability
3. Local and global loading
4. General strength and structural design
5. Hydrodynamic loading and seakeeping
6. Wind/current loads, wave drift and slowly-varying loads
7. Mooring and station keeping

## Design Project References

"Guide for Building and Classing Floating Production Installations." American Bureau of Shipping, 2010. ({{% resource_link "e652038e-bcb7-42e6-b1e6-a1dd2d288790" "PDF - 3.1MB" %}})

"Guide for 'Dynamic Loading Approach' for Floating Production, Storage and Offloading (FPSO) Installations." American Bureau of Shipping, 2010. ({{% resource_link "8d51aaac-17d4-48f6-865f-60f7ab41555e" "PDF" %}})

Sections 5.1 to 5.4 of "Common Structural Rules for Double Hull Oil Tankers." American Bureau of Shipping, 2010. ({{% resource_link "f0d8f300-ab88-4220-9b87-bac8d17979e0" "PDF - 7.4MB" %}})

International Maritime Organization. Regulation 22 from *MARPOL Consolidated Edition*. International Maritime Organization, 2006. ISBN: 9789280142167. ({{% resource_link "9d5026ce-e4e2-4614-999d-56f5988066ce" "PDF - 13.0MB" %}})

Offshore-Technology.com. "{{% resource_link "e5219cc5-d52f-45d4-976b-e6fa1087529c" "Elf exploration field – Girassol, Luanda, Angola" %}}." Accessed July 12, 2011.

Doumont, Jean-Luc. Part Four, "Effective Graphical Displays." *Trees, Maps, and Theorems*. Principiae, 2009. ISBN: 9789081367707.