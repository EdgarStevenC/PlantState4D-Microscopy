# PlantState4D

### From fluorescent signals to plant architecture

*Multiscale observation of Arabidopsis structure and development through 3D microscopy, quantitative imaging and multispectral phenotyping.*

**Work in progress** · MATLAB · Python · 2026

---

**Observation → Reconstruction → Quantitative characterization → Biological interpretation**

Fluorescence microscopy and multispectral imaging provide complementary views of plant organization, from cellular structures and developing tissues to whole-plant morphology.

The visualizations emphasize what is experimentally observed, how image-derived representations are constructed, and which biological questions they can support.

## 01 · Fluorescent signals and cellular organization

### Floral meristem · Membrane and auxin-response reporters

***Arabidopsis thaliana*** · Confocal fluorescence microscopy · 3D volumes

Two fluorescent reporters provide distinct biological observables.

**PM · `pUBQ10::acyl:TDT`** — membrane-associated fluorescence for observing cellular and tissue organization.

**DR5 · `DR5v2::n3eGFP`** — nuclear reporter of auxin-responsive transcriptional activity.

### Membrane-associated fluorescence

**Three observations · T1–T3**

3D renderings reveal the spatial organization of the imaged floral tissues.

<table>
<tr>
<td align="center"><b>T1</b><br><img src="assets/d03/flower/gif/T1_PM.gif" width="260"></td>
<td align="center"><b>T2</b><br><img src="assets/d03/flower/gif/T2_PM.gif" width="260"></td>
<td align="center"><b>T3</b><br><img src="assets/d03/flower/gif/T3_PM.gif" width="260"></td>
</tr>
</table>

### Complementary fluorescence signals

**T1 · PM + DR5**

<p align="center">
<img src="assets/d03/flower/gif/01_D03_T1_PM_DR5_overlay.gif" width="650" alt="Exploratory PM and DR5 fluorescence rendering">
</p>

<p align="center">
<strong>PM</strong> · Membrane-associated fluorescence &nbsp; | &nbsp;
<strong>DR5</strong> · Auxin-response reporter
</p>

*Exploratory dual-channel visualization. Spatial registration remains provisional; apparent signal proximity does not establish colocalization. DR5 does not directly measure auxin concentration.*

---

## 02 · Cellular architecture and developing organs

### Ovule development

***Arabidopsis thaliana*** · Volumetric fluorescence microscopy · Seven annotated developmental stages

3D observations illustrate the architecture of developing ovules, including tissue boundaries and changing morphological organization.

![Seven stages of ovule development](assets/d02/ovules/panel/D02_ovule_development.png)

### Three-dimensional observations

<table>
<tr>
<td align="center"><b>Stage 2-IV</b><br><img src="assets/d02/ovules/gif/01_Ovule_2-IV.gif" width="220"></td>
<td align="center"><b>Stage 2-V</b><br><img src="assets/d02/ovules/gif/02_Ovule_2-V.gif" width="220"></td>
<td align="center"><b>Stage 3-I</b><br><img src="assets/d02/ovules/gif/03_Ovule_3-I.gif" width="220"></td>
<td align="center"><b>Stage 3-II</b><br><img src="assets/d02/ovules/gif/04_Ovule_3-II.gif" width="220"></td>
</tr>
<tr>
<td align="center"><b>Stage 3-III</b><br><img src="assets/d02/ovules/gif/05_Ovule_3-III.gif" width="220"></td>
<td align="center"><b>Stage 3-IV</b><br><img src="assets/d02/ovules/gif/06_Ovule_3-IV.gif" width="220"></td>
<td align="center"><b>Stage 3-V</b><br><img src="assets/d02/ovules/gif/07_Ovule_3-V.gif" width="220"></td>
<td></td>
</tr>
</table>

*Developmental labels refer to the original morphological stage annotations. The animations show changes in viewpoint, not elapsed biological time.*

### Root tissue architecture

**3D fluorescence imaging · Spatial tissue organization**

A selected root volume illustrates cellular and tissue-level architecture in three dimensions.

<p align="center">
<img src="assets/d02/root/gif/01_Root_Movie1_t00003.gif" width="520" alt="3D root fluorescence volume">
</p>

*The animation rotates a selected volume; it does not represent a time-lapse.*

---

## 03 · Leaf morphology and tissue geometry

### Leaf epidermis · PM-YFP fluorescence

***Arabidopsis thaliana*** · 3D confocal microscopy · Three representative volumes

Membrane-associated fluorescence reveals aspects of tissue geometry and cellular organization.

The selected volumes illustrate differences in apparent leaf size and morphology, providing a starting point for quantitative characterization of cellular geometry and organ shape.

![Three representative leaf volumes](assets/d04/leaf/panel/D04_leaf_triptych.png)

### Three-dimensional observations

<p align="center"><strong>Small leaf</strong></p>
<p align="center">
<img src="assets/d04/leaf/gif/01_Leaf_Small.gif" width="750" alt="Small leaf 3D rotation">
</p>

<p align="center"><strong>Medium leaf</strong></p>
<p align="center">
<img src="assets/d04/leaf/gif/02_Leaf_Medium.gif" width="750" alt="Medium leaf 3D rotation">
</p>

<p align="center"><strong>Large leaf</strong></p>
<p align="center">
<img src="assets/d04/leaf/gif/03_Leaf_Large.gif" width="750" alt="Large leaf 3D rotation">
</p>

*The size labels describe representative samples, not a validated longitudinal growth sequence.*

---

## 04 · Whole-plant phenotyping and multispectral imaging

### Arabidopsis · RGB(VIS), NIR and FLUO

**IPK Gatersleben** · LemnaTec phenotyping platform · Top-view acquisition

Three complementary imaging modalities provide distinct optical observations of plant structure and digital signal responses.

**RGB(VIS)** · Visible imaging with red, green and blue channels.

**NIR** · Near-infrared imaging.

**FLUO** · Fluorescence imaging.

### Multispectral acquisition

Representative observations demonstrate the complementary information available from the three imaging modalities.

![Multispectral imaging modalities](assets/d01/multispectral/02_reference_modalities.png)

### Image registration, segmentation and fusion

**FLUO → Red · VIS → Green · NIR → Blue**

Geometric registration and plant segmentation support a common visual representation of the processed multimodal observations.

![Multispectral segmentation and fusion](assets/d01/multispectral/03_reference_segmentation_fusion.png)

### Digital signal distribution

**VIS-R/G/B · NIR · FLUO-R/G/B**

Digital intensity distributions illustrate the responses of the seven channels used for exploratory characterization.

![Digital channel distributions](assets/d01/multispectral/04_reference_channel_responses.png)

### Early rosette observations · 12–28 DAS

**Eight acquisitions · One plant · Three imaging modalities**

Repeated top-view observations of plant `1135FA1125` illustrate changes in projected morphology over time.

The labels indicate **days after sowing (DAS)**, recovered directly from the original experimental metadata.

![Multispectral plant observations at 12 to 28 DAS](assets/d01/multispectral/00_vegetative_gallery.png?v=ad78e09)

*The fused colors are a visualization convention, not physical spectral colors. Digital intensities are not calibrated radiance; projected morphology does not directly measure biomass. Phenological classification of the selected images remains subject to visual verification.*

---

## From images to quantitative plant biology

**Geometry · Fluorescent signaling · Morphogenesis · Temporal observation**

Across cellular, tissue, organ and whole-plant scales, these datasets illustrate complementary experimental observables.

Their quantitative potential lies in connecting image-derived measurements with explicit biological questions: changes in cell and tissue geometry, spatial organization, organ morphology and plant development.

Understanding relationships with mechanical stress, material properties or biochemical regulation requires additional measurements, modeling and experimental validation.

The four demonstrations originate from independent datasets and do not constitute a single continuous multiscale experiment.

**[Data provenance and acquisition notes](DATA_SOURCES.md)**

---

*Work in progress · MATLAB · Python · 2026*
