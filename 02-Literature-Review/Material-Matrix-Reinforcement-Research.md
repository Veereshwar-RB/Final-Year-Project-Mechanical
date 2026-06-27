Material Matrix + Reinforcement Research

Unexplored Combinations for FDM/FFF 3D Printing

Literature review note for this final year project — tracking under-studied
polymer matrix + reinforcement pairings that have good bonding chemistry and
mechanical potential on paper, but little to no published FDM-specific
research.

Status

🔄 6 combinations shortlisted, profiling in progress.

Shortlisted Combinations

ComboMatrixReinforcementResearch Gap1PETBasalt FiberBasalt+PET pairing barely studied in AM; mostly basalt+epoxy/glass literature exists2PEEKBasalt FiberPEEK+carbon and PEEK+glass are studied; PEEK+basalt is largely untouched3PPSGlass FiberPPS alone is FFF-studied, but PPS+glass fiber filament data is sparse4TPUBasalt FiberFlexible matrix + stiff mineral fiber is an uncommon pairing in AM literature5PETBoron NitrideBN is used for thermal-conductive filaments, but rarely paired with PET6PETGGraphene NanoplateletsPETG+carbon fiber is common; PETG+graphene is a thin research area


Combo 1 — PET + Basalt Fiber

Matrix (PET): Semi-crystalline thermoplastic, already FDM-proven, decent
chemical resistance and recyclable.

Reinforcement (Basalt Fiber): Continuous mineral fiber from volcanic
rock. Comparable tensile strength to E-glass, but notably higher thermal
stability.

Typical print parameters (literature/datasheet range — verify before
testing): nozzle ~230–260°C, bed ~70–80°C. PET is hygroscopic — pre-dry
before printing with fiber-filled blends.

Why this is a gap: Basalt fiber composites are well studied with epoxy
and glass-style matrices, but basalt+PET in AM specifically has almost no
published work.

Potential applications: structural brackets needing better heat
resistance than glass-fiber PETG; lower-cost alternative to carbon fiber
where natural/recyclable sourcing matters.

Open questions: fiber-matrix adhesion without a coupling agent; optimal
fiber length/loading without nozzle clogging.


Combo 2 — PEEK + Basalt Fiber

Matrix (PEEK): Aerospace/medical-grade engineering polymer, high
strength-to-weight, chemically inert, heat resistant — demanding to print.

Reinforcement (Basalt Fiber): High thermal stability matches PEEK's
high processing temperature better than glass fiber, which loses strength
faster under repeated high-temp cycling.

Typical print parameters (verify before testing): nozzle ~380–420°C,
heated chamber ~120–150°C, bed ~230–250°C with a PEEK-compatible surface.

Why this is a gap: PEEK+carbon and PEEK+glass filaments are
commercially studied. PEEK+basalt is not, despite basalt's thermal
stability being a closer match to PEEK's processing window.

Potential applications: aerospace/automotive brackets needing
PEEK-level heat resistance at lower cost than carbon fiber; components
where carbon fiber's conductivity is undesirable.

Open questions: whether basalt survives PEEK's processing temperature
without degrading; interfacial bonding without a coupling treatment.


Combo 3 — PPS + Glass Fiber

Matrix (PPS): High-temperature, chemically resistant, inherently
flame-retardant. Sulfur-containing backbone bonds well with mineral/ceramic
fillers.

Reinforcement (Glass Fiber): The most common FDM reinforcement fiber —
but almost always paired with PLA, PETG, ABS, or nylon, not PPS.

Typical print parameters (verify before testing): nozzle ~300–330°C,
bed ~120–140°C, heated enclosure recommended. PPS tolerates ~200°C+
continuous service.

Why this is a gap: PPS alone is FFF-documented; glass fiber is
documented for other matrices. The overlap — PPS+glass specifically — has
very little published filament-level data.

Potential applications: chemical-resistant, flame-retardant structural
parts (pumps, housings, under-hood components); lower-cost alternative to
PPS+carbon where conductivity isn't wanted.

Open questions: fiber dispersion uniformity at PPS processing
temperatures; whether glass loading compromises PPS's flame rating.


Combo 4 — TPU + Basalt Fiber

Matrix (TPU): Flexible elastomer for gaskets, seals, impact-absorbing
parts. Print quality depends heavily on retraction tuning and layer
adhesion.

Reinforcement (Basalt Fiber): Stiff mineral fiber — unusual in a
flexible matrix. Intent isn't to make TPU rigid, but to selectively
stiffen or abrasion-resist specific zones.

Typical print parameters (verify before testing): nozzle
~210–230°C, bed ~40–60°C, slower print speed for flow control with a
fiber filler.

Why this is a gap: Flexible matrix + stiff mineral fiber composites
are rare in FDM literature generally; basalt fiber in TPU specifically is
essentially unexplored.

Potential applications: conveyor/wear-pad components needing flex
with localized abrasion resistance; industrial gaskets needing partial
reinforcement.

Open questions: fiber loading ceiling before TPU loses its flexibility
advantage; extrusion reliability through flexible-filament-tuned hardware.


Combo 5 — PET + Boron Nitride

Matrix (PET): Same base as Combo 1, chosen here for a thermal/
electrical functional property rather than mechanical reinforcement.

Reinforcement (Boron Nitride particles): Electrically insulating but
thermally conductive — opposite profile to most carbon-based fillers.
Already used in some thermally conductive filaments, rarely with PET.

Typical print parameters (verify before testing): nozzle
~230–260°C, bed ~70–80°C. BN is abrasive — a hardened steel nozzle is
worth using for real testing.

Why this is a gap: BN-filled filaments exist mostly in nylon or PP
bases. PET+BN is close to unexplored, and PET's recyclability/cost could
make it more accessible than the matrices BN normally pairs with.

Potential applications: electronics enclosures/heat-sink housings
needing thermal conductivity without electrical conductivity; LED
housings, small heat-spreading brackets.

Open questions: BN loading needed for meaningful thermal conductivity
without killing flow; whether BN's platelet structure causes
layer-direction anisotropy in thermal performance.


Combo 6 — PETG + Graphene Nanoplatelets

Matrix (PETG): Easy to print, good layer adhesion, more forgiving
than PET or PEEK.

Reinforcement (Graphene Nanoplatelets): Few-layer graphene flakes —
high strength-to-weight, electrically and thermally conductive. Used in
some PLA/ABS conductive filaments; PETG+GNP is a thinner research area.

Typical print parameters (verify before testing): nozzle
~230–250°C, bed ~70–80°C. Conductive fillers tend to increase brittleness
— flow/retraction may need retuning.

Why this is a gap: PETG+carbon fiber is common and documented.
PETG+graphene is much less so — most graphene-filled filaments to date
are PLA or ABS based, not PETG.

Potential applications: ESD-safe enclosures and jigs; EMI-shielding
housings; lightweight conductive sensors or strain-gauge-style parts.

Open questions: GNP loading vs. conductivity percolation threshold for
PETG specifically; dispersion uniformity (graphene tends to agglomerate
without proper compounding).


Reference Papers


Basalt Fiber Properties Study — https://pmc.ncbi.nlm.nih.gov/articles/PMC11644435/
General study of basalt fiber properties (thermal stability, mechanical
performance) — supports the basalt-related combos (1, 2, 4).
Known factors are: This report explains how 3D printing can be improved by using continuous basalt fibers with Polyamide 12 (PA12) plastic. Basalt fibers are natural, eco-friendly, and have high strength. They can also resist heat and chemicals very well. In this study, a special 3D printer was used to add continuous basalt fibers into the plastic while printing. The researchers tested the strength and stiffness of the printed material by pulling it in different directions. The results showed that the material became almost 15 times stronger than normal PA12 when it was pulled along the direction of the fibers. However, the material was much weaker when it was pulled from the side or twisted. The study concluded that the direction in which the fibers are placed is very important. Engineers must carefully plan the fiber layout during 3D printing so that the final product can withstand heavy loads safely and perform better
Basalt Fiber Composite Study — https://www.sciencedirect.com/science/article/abs/pii/S1359836818332736
Composite-focused study of basalt fiber — useful for the bonding
chemistry / interfacial behavior angle.
