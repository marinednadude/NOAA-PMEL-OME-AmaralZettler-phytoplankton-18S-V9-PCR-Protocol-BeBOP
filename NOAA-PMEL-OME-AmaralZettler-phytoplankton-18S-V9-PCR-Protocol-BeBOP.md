---
#MIOP terms
methodology_category: Omics analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: 'PCR [OBI:0000415]'
analyses: 'PCR [OBI:0000415]'
geographic_location: 'North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]'
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024]
environmental_medium: 'sea water [ENVO:00002149]'
target: 'Small subunit ribosomal ribonucleic acid (SSU rRNA) 18S v9 [SO:0002236]'
creator: 'Shannon Brown, Han Weinrich, Zachary Gold'
materials_required: 'vortexer [OBI:0400118], PCR instrument [OBI:0000989]'
skills_required: 'sterile technique, pipetting skills, and standard molecular technique'
time_required: 135
personnel_required: 1
language: en
issued: '2025-11-06'
audience: 'scientists'
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
inhibition_check_0_1: not applicable
inhibition_check: not applicable
thermocycler: Applied Biosystems Veriti 96-well thermal cycler
assay_name: ssu18sv9_amaralzettler
assay_validation: The assay has been validated through multi-step in-silico, in-vitro, and in-situ validations. In addition to repeat analysis with alternate assays and intra/inter species tests. See BeBOP for citations.
targetTaxonomicAssay: "18S rRNA gene sequencing targeting the V9 region using primers 18S V9 1389 F and 18s v9 1510 R"
targetTaxonomicScope: single-celled eukaryotic organisms
target_gene: 18S rRNA (SSU eukaryote)
target_subfragment: V9
ampliconSize: 87-186
pcr_primer_forward: TTGTACACACCGCCC
pcr_primer_reverse: CCTTCYGCAGGTTCACCTAC
pcr_primer_name_forward: 18S V9 1389 F
pcr_primer_name_reverse: 18s v9 1510 R
pcr_primer_reference_forward: https://doi.org/10.1371/journal.pone.0006372
pcr_primer_reference_reverse: https://doi.org/10.1371/journal.pone.0006372
pcr_primer_vol_forward: 1
pcr_primer_vol_reverse: 1.0
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: Azura TruFI DNA Polymerase
custom_mm: PCR reactions were run in 25 μL reaction volumes, with 2 μL of DNA, 0.25 μL of Azura TruFI DNA Polymerase, 5 μL of Azura TruFI 5X reaction buffer, 15.75 μL of water, and 1 μL of each primer (10 μM).
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
amplificationReactionVolume: 25
pcr_dna_vol: 2.0
pcr_rep: 1.0
nucl_acid_amp: https://doi.org/10.5281/zenodo.11398105
pcr_cond: initial denaturation:95_1;normal_cycling;denaturation:95_0.25;annealing:56_0.25;elongation:72_0.5;30
annealingTemp: 56
pcr_cycles: 30
pcr_analysis_software: "missing: not provided"
pcr_method_additional: Quality was validated via confirmation of a product on a gel.
---

# NOAA PMEL OME AmaralZettler phytoplankton 18S V9 PCR Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2024-02-01|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2024-02-01|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-01|
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-01|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2024-02-01|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME-Gel-Electrophoresis-Protocol | https://github.com/HanWeinrich/NOAA-PMEL-OME-Gel-Electrophoresis-Protocol-BeBOP/blob/main/NOAA-PMEL-OME_Gel_Electrophoresis_Protocol_BeBOP.md | 1.0.1 | 2025-11-06 | Internal  |
| Amplicon Library Preparation | https://www.protocols.io/view/amplicon-library-preparation-bp2l6b4j5gqe/v1 | V1 | 2020-10-04 | External |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2024-02-01 | Initial release |
| 1.1.0 | 2025-05-01 | Addition of FAIR eDNA terms in YAML frontmatter and formatting edits |
| 1.1.1 | 2025-05-29 | Minor acronym and content revisions  |
| 1.2.0 | 2025-06-10 | Adding Gel Electrophoresis protocol, new acronym, and updated reaction mixture concentrations |
| 1.2.1 | 2025-11-06 | Clarified safety guidelines and negative control language |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|18S V9 SSU rRNA |Small subunit ribosomal nucleic acid 18S V9 gene region|
|BSC	|Biosafety cabinet|
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies|
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies
|MBARI| Monterey Bay Aquarium Research Institute|
|MBON	|Marine Biodiversity Observation Network|
|NOAA|National Oceanic and Atmospheric Administration|
|NTC	|No template control
|OME	|Ocean Molecular Ecology
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE    | Personal protective equipment |
|UV| Ultraviolet|
|UW| University of Washington
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically, nuclease-free water or an empty filter is run through the DNA extraction process to control for contamination in the DNA extraction step. |
| Field blank  | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step. |
| No template control | PCR negative control. Typically, nuclease-free water is loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically, a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community is loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## BACKGROUND

### Summary

This protocol is for amplifying the Small subunit ribosomal ribonucleic acid (SSU rRNA) 18S v9 gene in eukaryotes. The primers (forward: 18S V9 1389 F, reverse: 18S v9 1510 R) were first presented in [Amaral-Zettler et al. 2009](https://doi.org/10.1371/journal.pone.0006372). The target amplicon size is 87 - 186 base pairs.

This primer set targets single-celled eukaryotic organisms (e.g., phytoplankton, dinoflagellates, diatoms, and haptophytes). Important note: this primer also amplifies non-target organisms, including zooplankton and other metazoans.

The protocol presented here is intended as the first PCR of a two-step PCR next-generation sequencing library preparation using Illumina Nextera Unique Dual Indices. Our written protocol does not include the second PCR step in which unique library-specific barcodes are attached to each round 1 PCR product.  

### Method Description and Rationale

This protocol was chosen because it has been widely and historically used by the NOAA-CalCOFI Ocean Genomics (NCOG) and Tara Oceans program, both leaders in the field of eDNA research and important partners in the West Coast Ocean Biomolecular Observing Network (WC-OBON), to generate marine eDNA time series. Our protocol uses the same primers, polymerase, and thermocycling conditions as NCOG. Tara Oceans program uses a different master mix (See [Tara Oceans protocol](https://www.protocols.io/view/18s-and-16s-rrna-genes-amplicon-generation-for-euk-ewov1r52lr24/v1?step=2)) We intentionally chose this protocol to promote standardization of ocean biomolecular observations and easily facilitate integration of PMEL OME eDNA data with NCOG eDNA time series.

This amplification protocol is accessible to most molecular biology labs.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to amplify extracted DNA from thousands of filtered seawater samples taken from coastal stations off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea, and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf). 

### Personnel Required

One person with molecular biology experience.

### Safety

This protocol uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time Needed to Execute the Procedure

PCR preparation and running the PCR protocol for a single 96-well plate takes 2.25 hours (135 minutes), 45 mins of which is the thermocycler run time. Additional plates can be run simultaneously without greatly increasing the time required. 

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|Pipetman P10L|Gilson|1|Can be substituted with any accurate pipettor|
|Pipetter: 20 - 200 μL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor|
|Pipetter: 100-1000 μL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic - internal UV light required|
|Thermocycler|Veriti 96-well thermal cycler |Applied Biosystems| 1|	Can be substituted with generic|
| Mini-centrifuge | Personal mini centrifuge  | BioExcell | 1 | Can be substituted with generic, but needs to fit 1.5-2.0 mL tubes |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic|
| Plate spinner | [Salad spinner]( https://doi.org/10.3390/mps3020041) | Cuisinart | 1| Can be substituted with generic or plate centrifuge |
| Foil roller | Rubber roller | Generic | 1 ||
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Eppendorf | 1 | Can be substituted with generic|
| 1.5 mL tube cooler rack | Benchtop cooler | Thermo Scientific  | 1 | Can be subsituted with generic |
| 2 mL tube rack | Microcentrifuge tube rack | VWR | 1 | Can be substituted with generic |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic |
|Wash bottle|Safety Wash Bottle for Ethanol 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Wash bottle|Safety Wash Bottle for Hypochlorite Bleach 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Freezer|Freezer capable of reaching and maintaining -20°C|Generic|1| Used to store DNA and PCR reagents **NOTE: A separate freezer should be used to store PCR products if possible.**|
|Fridge| Refrigerator capable of reaching and maintaining 4°C|Generic|1|Used to store some PCR reagents **NOTE: A separate fridge should be used to hold PCR products if possible.**|
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic|
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|2| Can be substituted with generic - must be sterilized before use |
| **Consumable equipment** |
| 1000 μL pipette tips | TipOne RPT filter tips 1000 μL XL graduated | USA Scientific | 4 | Can be substituted with generic - must be sterile and filtered |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be substituted with generic - must be sterile and filtered |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be substituted with generic - must be sterile and filtered |
| PCR plates | Twin.tec LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 1 | Can be substituted with generic - must be DNA low retention |
| PCR aluminum foil | Adhesive sterile PCR foil seals | VWR| 2 | Can be substituted with generic - must be sterile |
| 2 mL tubes | Snap cap DNA LoBind 2.0 mL tubes, PCR-clean| Eppendorf |5 | Can be substituted with generic - must be sterile |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |2 | Can be substituted with generic - must be sterile |
| Kimwipes | Delicate task wipes | Kimtech | 5 | |
| Nitrile gloves | Powder Free Nitrile Gloves | Fisher Scientific | 4 | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
|Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|1|Can be substituted with generic|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH  |
|**Optional Equipment**|||			
|Repeater Pipetter: 10-300  μL|E1-ClipTip electronic single channel pipette, 10-300 μL |ThermoFisher|	1|Can be substituted with generic - not required but reduces protocol time|
| 300 μl repeater pipette tips | ClipTip 300 filtered sterile tips| Thermo Scientific| 2| Can be substituted with generic. Must fit repeater pipette. Must be sterile and filtered. |
|8-channel multichannel pipetter: 1-10 μL| Pipetman Multichannel P8X10|	Gilson|	1|Can be substituted with generic. Not required, but reduces protocol time.|
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Can be substituted with generic - recommended not required |
| **Chemicals** |
| 5X reaction buffer |Azura TruFi 5X reaction buffer | Azura Genomics | 520  μl per plate | Store at -20°C |
| DNA Polymerase |Azura TruFi DNA Polymerase | Azura Genomics | 26 μl per plate | Store at -20°C - keep thawed for as little time as possible |
| Forward primer | Custom oligo | IDT |104 μl per plate |Store at -20°C|
| Reverse primer| Custom oligo | IDT | 104  μl per plate | Store at -20°C |
| Nuclease free water | UltraPure DNase/RNase-free distilled water | ThermoFisher | 1638 μl per plate | |
| Positive control| gBlocks HiFi Gene Fragments | IDT | 2 μl per plate | Store at -20°C |
| 70% EtOH | Molecular grade ethanol| Generic | 20 mL | |
| 10% bleach| Hypochlorite bleach |Clorox| 40 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

## STANDARD OPERATING PROCEDURE

### Preparation

1. Sterilize workspaces and durable equipment, including pipettes within the BSC, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
2. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. 
3. Run the UV light in the BSC for 30 minutes before starting work.
4. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). The recommended labeling scheme includes plate name, primer, date of PCR, and personnel initials.
5. Dilute DNA samples to a 1:10 dilution with molecular grade water. 

### PCR

**Primer Sequences without Adapters**: PCR primer sequences (**target sequence bolded**)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|18S V9 1389 F| Forward |**TTGTACACACCGCCC** |
| 18s v9 1510 R| Reverse |  **CCTTCYGCAGGTTCACCTAC**|

**Primer Sequences Used**: PCR primer sequences with Illumina Adapters
(Adapter sequence + **target sequence bolded**)
| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|TO 18S V9 - Nex - F|  Forward| TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**TTGTACACACCGCCC** |
| TO 18S V9 - Nex - R| Reverse | GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**CCTTCYGCAGGTTCACCTAC** |

**Reaction Mixture**: PCR reagents, volumes, initial, and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |-----|
| Azura TruFi 5X reaction buffer |520| 5 | 500%| 100%|
| Azura TruFi DNA polymerase |26|0.25 |100% |1% |
| Forward Primer |104| 1|10 μM |0.4 μM |
| Reverse Primer |104| 1|10 μM |0.4 μM |
| Nuclease-Free Water|1638|15.75 | N/A|N/A |
| Template DNA|N/A| 2 | 10%|0.8% |
| **Total**|**2392**| **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multiplied by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|60s|	1X
|**Normal Cycling**||||
|Denaturation|	95°C|	15s|	30X|
|Annealing|	56°C|	15s	|30X|
|Extension	|72°C	|30s	|30X|
|Hold	|4°C	|∞	|1X|


**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from the post-PCR space where thermocyclers are located, and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease-free water. Then tap/flick AmpliTaq rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make the final master mix, as denoted in the reagent mixture table.
4. Set out the template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well (See [Protocol Sample Sheet](https://docs.google.com/spreadsheets/d/1GiYxSuAibLr0o4OulZFxdJbhuhW9fhLBwIDK_UkXR90/edit?usp=sharing)), but reserve two wells for the positive control and a no template control (NTC). 
7. To one well, add 2 μL of the positive control. To another well, add 2 μL of nuclease-free water for the NTC.
8. Seal the PCR plate with foil.
9. Spin down the plate, and then transport in cooler blocks before placing in the thermocycler.
10.  Run thermocycler protocol.

### Quality control

1. Plates should be removed from the thermocycler  after the run completes and stored at 4°C until run on a gel. Storing the PCR product at -20˚C is ideal for 1-6 months, while -80˚C is ideal for long-term storage.
2. Run gel visualization to confirm successful PCR. [NOAA-PMEL-OME-Gel-Electrophoresis-Protocol](https://github.com/HanWeinrich/NOAA-PMEL-OME-Gel-Electrophoresis-Protocol-BeBOP/blob/main/NOAA-PMEL-OME_Gel_Electrophoresis_Protocol_BeBOP.md)

#### Positive Control

A positive control is used in every PCR run to verify the success of the PCR reaction.  In place of template DNA, 2 μL of positive control diluted to 10^3 copies/µL is used. One well per plate is allotted for the positive control. The positive control used for 18S V9 is the heterotrophic nanoflagellate species *Halocafeteria seosinensis* native to Korean salterns. The reference nuclear sequence used to develop the positive control sequence can be found on GenBank: [Accession DQ269470.1](https://www.ncbi.nlm.nih.gov/nuccore/DQ269470.1). We note that this accession had 1 mismatch in the reverse primer, and thus, we modified the positive control to use the exact primer sequence to avoid mismatches. We note that [Machida metazoan 18S V8 ribosomal DNA V8](https://doi.org/10.1371/journal.pone.0046180) and Amaral-Zettler phytoplankton 18S V9 have overlapping sequences, and thus we designed this positive control to capture both regions.

|Positive Control Sequence|
|--------------------------|
|GCTCTTTCTTGATTCTATGGGTGGTGGTGCATGGCCGTTCTTAGTTGGTGGAGTGATTTGACTGGTTAATTCCGTTAACGAACGAGACCTCCGCCTGCTAATTAGTTTCCAAGTGTGTGCACTTGGTGAAACTTCTTAGAGGGACTATGAGCGTTTAGCTCATGGAAGTTGGAGGCAATAACAGGTCTGTGATGCCCTTAGATGTTCTGGGCCGCACGCGCGCTACGCTGACCGGTGCAACAAGTTTGTATCCTTGGCTCGAAAGGCCTGGGGAATCTTGCAAAGCCGGTCGTGATGGGGATAGATTCTTGCAATTTTTAATCTTCAACGAGGAATTCCTAGTAAACGCAAGTCATCAACTTGCATTGATTACGTCCCTGCCCTTTGTACACACCGCCCGTCGCACCTACCGATTGAATGGTCCGGTGAAACCTCCGGATTGGCGTCGGTTCCCGCAAGGGTCCGCGCCAAAAAGTTGGTTGAACCTTACCATTTAGAGGAAGGTGAAGTCGTAACAAGGTTTCCGTAGGTGAACCTGCAGAAGGATCATTAGAGAGGGAATATA|

#### Negative Control

Nuclease-free water is used as a no-template control (NTC) when setting up each PCR plate. One well per plate is allotted to an NTC. NTCs should be run in addition to both field blanks and extraction blanks.

### Basic Troubleshooting Guide

***Issue 1**: Streaking is observed for sample wells in the gel, but the positive control band appears normal. 

**Solution**: Dilute the sample DNA to a 1:10 dilution with nuclease-free water. If smearing is still observed using a 1:10 dilution, dilute the DNA samples further to a 1:100 dilution. If the samples do not amplify under these conditions, the sample is likely inhibited or has too little target DNA and thus is unlikely to yield valuable results. Alternative solutions include cleaning DNA extractions with a commercial cleanup kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired, and rerun the PCR. If the positive control fails again, the reagents or the positive control are likely compromised. 

**Issue 3**: Band observed in the no-template control.

**Solution**: The PCR was likely contaminated - toss the plate. Sterilize lab space thoroughly and rerun with new aliquots of reagents.

**Issue 4**: Band observed for either the field blank or the extraction blank.

**Solution**: The product should be sent for sequencing to determine the severity of contamination.

**Issue 5**: Low volume post-PCR

**Solution**: If using strip-caps, ensure they are tightly fitting on wells. Any gap in the lid will allow for some volume to evaporate during the PCR process on the thermal cycler. If using PCR plate seals, spin down the plate after taking it off the thermal cycler to ensure all condensation is drawn back into the well.

**Issue 6**: Weak Amplification

**Solution**: If there are weak amplification bands on the gel, ensure the master mix and DNA are being fully mixed. You can also increase the concentration of primers or tweak the PCR process on the thermal cycler (increasing # of cycles of PCR or optimizing the annealing temperature).

## REFERENCES

1. Amaral-Zettler, L. A., McCliment, E. A., Ducklow, H. W., & Huse, S. M. (2009). A method for studying protistan diversity using massively parallel sequencing of V9 hypervariable regions of small-subunit ribosomal RNA genes. PloS one, 4(7), e6372. https://doi.org/10.1371/journal.pone.0006372
2. Machida, R. J., & Knowlton, N. (2012). PCR primers for metazoan nuclear 18S and 28S ribosomal DNA sequences. https://doi.org/10.1371/journal.pone.0046180
   
## APPENDIX A: DATASHEETS
[Protocol Sample Sheet](https://docs.google.com/spreadsheets/d/1cUywijO91LokCADOyBodINfACX8HzShYFKptwyIZUo8/edit?usp=sharing)
