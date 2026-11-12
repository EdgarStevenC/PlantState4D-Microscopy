# Data sources and acquisition notes

This document records the established provenance and interpretation limits of the PlantState4D visual demonstrations. The images and animations are processed representations of experimental datasets.

## D01 · Whole-plant multispectral phenotyping

**Organism:** *Arabidopsis thaliana*

**Investigation:** Quantitative Monitoring of Arabidopsis thaliana Growth and Development Using High-Throughput Plant Phenotyping.

**Institution:** IPK Gatersleben, Germany.

**Principal investigator identified in the investigation metadata:** Astrid Junker.

**Experimental sample:** `1135FA1125`, corresponding to `plant_122` in the ISA-Tab study metadata.

**Study start:** 19 August 2011.

**Acquisition platform:** LemnaTec phenotyping system.

**Modalities:** RGB(VIS), NIR and FLUO.

**Camera configurations:** `A_Rgb_Top_Pot`, `A_Nir_Top_Pot`, `A_Fluo_Top_Pot`.

**Selected top-view acquisition days:** 12, 14, 17, 19, 21, 24, 26 and 28 DAS.

**Source metadata:** `i_investigation.txt`, `s_study.txt`, `a_phenotyping.txt`.

**Processing manifest:** `multispectral_manifest.csv`.

**Accession:** EURISCO accession 1668187 is referenced by the original study. The corresponding cultivar designation still requires independent confirmation.

**Interpretation:** Digital intensities are not calibrated radiance. The displayed fusion combines FLUO, VIS and NIR for visualization. Segmented projected area is not a direct biomass measurement. Pre-flowering status of the selected frames requires visual confirmation.

## D02 · Ovule and root volumes

**Organism:** *Arabidopsis thaliana*.

**Content:** Seven annotated ovule stages and one selected root volume.

**Observation:** Volumetric fluorescence imaging of biological structures.

**Outstanding verification:** Exact staining or reporter, genotype, microscope model, voxel calibration and primary dataset citations.

**Interpretation:** Rotations display alternative 3D viewing angles, not biological time progression.

## D03 · Floral meristem fluorescence

**Organism:** *Arabidopsis thaliana*.

**Membrane-associated reporter:** `pUBQ10::acyl:TDT`.

**Auxin-response reporter:** `DR5v2::n3eGFP`.

**Content:** Three PM observations (T1–T3) and exploratory T1 PM/DR5 dual-channel visualization.

**Interpretation:** DR5 is an auxin-response reporter, not a direct measure of auxin concentration. Spatial registration between PM and DR5 remains provisional.

**Outstanding verification:** Original experimental sample relationship between T1–T3 and complete acquisition metadata for the particular files.

## D04 · Leaf fluorescence volumes

**Organism:** *Arabidopsis thaliana*.

**Fluorescent label:** PM-YFP.

**Content:** Three representative volumes categorized visually as small, medium and large.

**Interpretation:** These size categories do not establish a validated growth trajectory.

**Outstanding verification:** Genotype, microscope model, voxel calibration, acquisition settings and complete source citation.

## Scientific interpretation

The examples concern different observables and acquisition contexts: fluorescent reporter activity, membrane-associated fluorescence, tissue architecture and whole-plant optical imaging.

Morphological data alone do not establish mechanical forces, biochemical concentrations or causal developmental mechanisms.

Original publications, attribution requirements and reuse permissions should be verified against each source dataset.
