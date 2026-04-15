# Nicolas Brantut Corpus Notes

## Status

This note captures the first research pass:

- verified author identity from the GFZ profile
- extracted ORCID from the GFZ profile
- used Crossref to build an initial ORCID-backed publication corpus
- identified an initial `core` paper set for the themes of interest
- noted one additional highly relevant 2025 coauthored preprint on fluid-induced aseismic slip that did not appear in the ORCID-only list

## Verified Author Identity

- GFZ profile: `https://www.gfz.de/en/staff/nicolas.brantut/sec42`
- ORCID: `0000-0002-1704-7468`
- GFZ profile description: `Physics of rock deformation and faulting`

## Corpus-Building Notes

- Crossref ORCID query returned 33 records.
- The ORCID-backed list is much cleaner than a broad author-name query.
- A broader Crossref search also surfaced additional Brantut coauthored items not captured by the ORCID filter.
- For this project, the ORCID list is the backbone corpus, with additional targeted searches used to catch obvious missing papers in the induced-seismicity cluster.

## Initial Core Paper Set

These papers appear most relevant to the user's interests based on title and abstract screening.

| Year | Title | DOI | Primary Themes |
| --- | --- | --- | --- |
| 2018 | Fault Reactivation by Fluid Injection: Controls From Stress State and Injection Rate | `10.1029/2018gl080470` | induced-seismicity, fluids, fault-stability, lab-model relevance |
| 2019 | Stability of Pulse-Like Earthquake Ruptures | `10.1029/2019jb017926` | fault-stability, rupture modelling |
| 2019 | Rupture Energetics in Crustal Rock From Laboratory-Scale Seismic Tomography | `10.1029/2019gl083040` | lab-model-iteration, rupture energetics |
| 2021 | Fault Friction During Simulated Seismic Slip Pulses | `10.1029/2021jb022149` | friction, rupture mechanics, lab-model-iteration |
| 2021 | Dilatancy Toughening of Shear Cracks and Implications for Slow Rupture Propagation | `10.1029/2021jb022239` | modelling, fluids, fault-stability |
| 2023 | Rupture and Afterslip Controlled by Spontaneous Local Fluid Flow in Crustal Rock | `10.1029/2023jb027534` | fluids, fault-stability, afterslip, lab-model-iteration |
| 2024 | Opposite Variations for Pore Pressure on and off the Fault During Simulated Earthquakes in the Laboratory | `10.1029/2024jb028829` | pore pressure, fault interaction, induced-seismicity relevance |
| 2024 | Permeability Development During Fault Growth and Slip in Granite | `10.1029/2024jb029057` | permeability, fault growth, fluids, lab observations |
| 2025 | Analysis of Stress in the Cohesive Zone, Dissipation and Fracture Energy During Shear Rupture Experiments | `10.1029/2024gl113972` | rupture mechanics, fracture energy, modelling |

## Additional Potentially Important Paper

This one appears highly relevant to induced seismicity and aseismic slip, but it came from a broader Crossref search rather than the ORCID-only corpus.

| Year | Title | DOI | Why It Matters |
| --- | --- | --- | --- |
| 2025 | Propagation of fluid-driven aseismic slip fronts along crustal faults | `10.21203/rs.3.rs-6812099/v1` | Directly addresses fluid-induced seismicity, diffusion versus aseismic slip front propagation, and experimental validation of fracture-mechanics predictions |

Related conference/preprint metadata also appeared under:

- `10.5194/egusphere-egu25-15900` - *Influence of injection rate on the dynamic of fluid-induced aseismic slip fronts*

## First-Pass Theme Notes

### Fault Stability

The early read suggests that Brantut's work treats fault stability as strongly controlled by:

- dilatancy and the associated transient pore-pressure drop
- thermal and frictional weakening during rapid slip
- rupture mode selection, especially pulse-like versus crack-like behavior
- off-fault damage and its effect on rupture energetics
- permeability evolution and hydraulic heterogeneity during fault growth

### Induced Seismicity

The clearest direct connection so far comes from the fluid injection and pore-pressure papers.

Early takeaways:

- injection rate matters because it controls how heterogeneous and localized the pressure field becomes
- local undrained conditions can decouple fault reactivation from simple Coulomb-style expectations based on borehole pressure alone
- aseismic slip and post-failure fluid recharge may be central for explaining delayed or migrating seismicity
- pore-pressure increases outside the slipping fault may help trigger nearby instabilities

### Modelling Approaches

From titles and abstracts alone, the main modelling styles appear to include:

- fracture mechanics
- elastodynamic rupture models
- slip-pulse theory
- thermal pressurization and flash-heating constitutive approaches
- poromechanical or fluid-flow coupling

These are not used in isolation. Even in the early screen, the work repeatedly appears to move between:

- laboratory constraints on friction, damage, permeability, or pore pressure
- theory or models used to interpret those observations and upscale them

### Lab-Model Iteration

This looks like a defining feature of the research program.

Recurring pattern:

1. Run controlled rock deformation or fault-slip experiments under crustal conditions.
2. Measure mechanical, acoustic, hydraulic, or microstructural evolution.
3. Use theory or numerical models to explain the mechanism and scale dependence.
4. Feed the experimental constraints back into rupture or fluid-fault models.

## Immediate Reading Priorities

The next deep-reading pass should start with:

1. `10.1029/2018gl080470` - fluid injection and fault reactivation
2. `10.1029/2021jb022239` - dilatancy toughening and slow rupture
3. `10.1029/2023jb027534` - rupture, fluid flow, and afterslip
4. `10.1029/2024jb028829` - pore pressure on and off fault
5. `10.1029/2024jb029057` - permeability evolution during fault growth
6. `10.1029/2019jb017926` - pulse-like rupture stability
7. `10.1029/2021jb022149` - friction during simulated slip pulses
8. `10.21203/rs.3.rs-6812099/v1` - fluid-driven aseismic slip fronts

## Caveats

- This note is based mainly on metadata and abstract-level screening.
- Some strong claims above are provisional until the full papers are read.
- The induced-seismicity synthesis will need careful wording, because some papers are directly about fluid injection while others are more generally about fault mechanics with indirect relevance.
