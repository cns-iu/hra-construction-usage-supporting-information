# **Companion Website for &quot;Human BioMolecular Atlas Program (HuBMAP): 3D Human Reference Atlas Construction and Usage&quot;**

Katy Börner<sup>1,\*</sup>, Philip D. Blood<sup>2,3</sup>, Jonathan C. Silverstein<sup>4</sup>, Matthew Ruffalo<sup>3</sup>, Sarah A. Teichmann<sup>5</sup>, Gloria Pryhuber<sup>6</sup>, Ravi Misra<sup>6</sup>, Jeffrey Purkerson<sup>6</sup>, Jean Fan<sup>7</sup>, John W. Hickey<sup>8</sup>, Gesmira Molla<sup>9</sup>, Chuan Xu<sup>5</sup>, Yun Zhang<sup>10</sup> Griffin Weber<sup>11</sup>, Yashvardhan Jain<sup>1</sup>, Danial Qaurooni<sup>1</sup>, Yongxin Kong<sup>1</sup>, HRA Team, Andreas Bueckle<sup>1,\*</sup>, Bruce W. Herr II<sup>1,\*</sup>

<sup>1</sup> Department of Intelligent Systems Engineering, Luddy School of Informatics, Computing, and Engineering, Indiana University, Bloomington, IN, USA\
<sup>2</sup> Pittsburgh Supercomputing Center, Pittsburgh, PA, USA\
<sup>3</sup> Carnegie Mellon University, Pittsburgh, PA, USA\
<sup>4</sup> Department of Biomedical Informatics, University of Pittsburgh School of Medicine, Pittsburgh, PA, USA\
<sup>5</sup> Wellcome Sanger Institute, Wellcome Genome Campus, Hinxton, Cambridge, UK\
<sup>6</sup> University of Rochester Medical Center, Rochester, NY, USA\
<sup>7</sup> Department of Biomedical Engineering, Johns Hopkins University, Baltimore MD, USA\
<sup>8</sup> Department of Biomedical Engineering, Duke University, Durham, NC, USA\
<sup>9</sup> New York Genome Center, New York, NY, USA\
<sup>10</sup> J. Craig Venter Institute, La Jolla, CA, USA\
<sup>11</sup> Department of Biomedical Informatics, Harvard Medical School, Boston, MA, USA\

\* Corresponding authors: \
Katy Börner, katy@iu.edu\
Andreas Bueckle, abueckle@iu.edu\
Bruce W. Herr II, bherr@iu.edu

---

[Link to HuBMAP Portal](https://portal.hubmapconsortium.org)\
[Link to HRA Portal](https://humanatlas.io)

---

#### **Flexible hybrid cloud microservices architecture**

<img alt="alt_text" width="75%" src="images/HuBMAP Microservices Arch - 3.1.2024.png">

---

#### **Atlas Construction and Publication**

Crosswalking tables for 3D Reference Objects:
 - Anatomical Structures, Cell Types and Biomarkers (ASCT+B) Tables to 3D Reference Object Library Mapping: [https://github.com/hubmapconsortium/ccf-releases/blob/main/v2.0/models/asct-b-3d-models-crosswalk.csv](https://github.com/hubmapconsortium/ccf-releases/blob/main/v2.0/models/asct-b-3d-models-crosswalk.csv)

Crosswalking tables for cell type annotation tools:
 - Azimuth: [https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/azimuth.csv](https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/azimuth.csv)
 - CellTypist: [https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/celltypist.csv](https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/celltypist.csv)
 - popV: [https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/popv.csv](https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/popv.csv)
 - All 3 crosswalks as graph: [https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/crosswalks.jsonld](https://github.com/hubmapconsortium/hra-workflows-runner/blob/main/crosswalking-tables/crosswalks.jsonld)



**Skin Anatomical Structures, Cell Types and Biomarker (ASCT+B) Table and Comparison**

In support of CCF design, ASCT+B table was compiled for all organs under investigation in HuBMAP, see details for ASCT+B table effort [here](https://hubmapconsortium.github.io/ccf/pages/ccf-anatomical-structures.html). A subset of these anatomical structures (AS), cell types (CT) and biomarkers (B) were included in this paper. The[ASCT+B Reporter](https://hubmapconsortium.github.io/ccf-asct-reporter) was used to comparethe AS, CT and B used in this paper to the most recent version (1.2) of the skin ASCT+B aster table.

Link to skin master ASCT+B Table: [Anatomical Structures, Cell Types, plus Biomarkers (ASCT+B) table for skin v1.2](https://hubmapconsortium.github.io/ccf-releases/v1.2/docs/asct-b/skin.html)

Link to experimental skin ASCT+B Metadata: [Skin markers used in the paper](https://docs.google.com/spreadsheets/d/1HM_rDLEMGYZ2r8jXjeEs3nNB94ubvn083y4ojjWT6mU/)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/ccf-asct-reporter/vis?selectedOrgans=skin-v1.2&playground=false&comparisonCSVURL=https:%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1ebxX1VmZXrxjfxZC8DdxtPjTGQLId9NBja71ii939c8%2Fedit%23gid%3D1990254927&comparisonName=Human%20Digital%20Twin&comparisonColor=%23ff8000&comparisonHasFile=false)

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/3.png" alt="alt text" title="image Title" />

---

#### **Violin Charts for Immune Cells**

These interactive violin plots show the distribution of distances of immune cells (T Helper, T Killer, T reg, macrophages) to the nearest endothelial cell in all regions and plotted by sun exposure (mild/marked) and age for all 10 donors.

[Link to violin plots for immune cell distances from endothelial cells](https://hubmapconsortium.github.io/vccf-visualization-release/html/violin_cell.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/violin_cell.html)

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/4.png" alt="alt text" title="image Title" />

---

**Violin Charts for Epidermis Cells**

The interactive violin plots combine a box plot and a density plot to display the probability density of keratinocyte cells positive for markers of DNA damage (p53), repair (DBB2) damage and proliferation (Ki67) and distance from the skin surface. They were plotted by sun exposure (mild/marked) and age for all 10 donors.

**_AE1 positive keratinocytes_**

The interactive violin plots combine a box plot and a density plot to display the probability density of keratinocyte cells (detected by cytokeratin AE1) positive for markers of DNA damage (p53), repair (DBB2) damage and proliferation (Ki67) and distance from the skin surface. They were grouped by sun exposure and plotted by age for all 10 donors.

[Link to violin plots for p53, Ki67, DDB2 positive epidermis cells (identified by AE1 positive staining) and distance to skin surface.](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/violin_damage_epidermis.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/violin_damage_epidermis.html)

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/18.png" alt="alt text" title="image Title" />

**_CK26 positive keratinocytes_**

[Link to violin plots for p53, Ki67, DDB2 positive keratinocytes (CK26 positive) and distance to skin surface.](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis_entire/violin_damage_epidermis.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis_entire/violin_damage_epidermis.html)

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/5.png" alt="alt text" title="image Title" />

---

**Vascular Common Coordinate Framework Visualization - Immune Cell Distance to Endothelial Cells**

These interactive plots show the 3D view of the skin and the distribution of immune cells (T helper, T killer, T reg, macrophages) and distance to nearest endothelial cells.

External link to the 3D view for immune cells:

[Region 1](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_1.html) / [Region 2](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_2.html) / [Region 3](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_3.html) / [Region 4](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_4.html) / [Region 5](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_5.html) /

[Region 7](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_7.html) / [Region 8](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_8.html) / [Region 9](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_9.html) / [Region 10](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_10.html) / [Region 11](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_11.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/region_11.html)

**Example Region 4: Immune cells (T helper, T killer, T reg, macrophages) and distance to nearest endothelial cell**

3D distance between immune cells and nearest endothelial cells for region 4 (donor 12, male, 48 years, superior abdomen, mild sun exposure); (ii) and histogram plots showing the highest distribution of immune cells within 50-200 um and higher counts of T killer cells within 50 um

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/15.png" alt="alt text" title="image Title" />

**Example Region 11: Immune cells (T helper, T killer, T reg, macrophages) and distance to nearest endothelial cell (RGB rendered version)**

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/14.png" alt="alt text" title="image Title" />

---

**Vascular Common Coordinate Framework Visualization - Epithelial Cells**

These interactive plots show the 3D view of the skin and the distribution of p53, DDB2 and Ki67 positive keratinocytes and distance to the skin surface.

External link to the 3D view for epithelial cells:

[Region 1](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_1.html) / [Region 2](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_2.html) / [Region 3](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_3.html) / [Region 4](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_4.html) / [Region 5](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_5.html) /

[Region 7](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_7.html) / [Region 8](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_8.html) / [Region 9](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_9.html) / [Region 10](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_10.html) / [Region 11](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_11.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/epidermis/epidermis_region_11.html)

**Example Region 11: Keratinocytes positive for markers of UV damage (p53), repair (DDB2) and proliferation (Ki67) and distance from skin surface**

Markers of UV damage, repair and proliferation in epidermis and distance to skin surface represented as 3D distance plots from the skin surface and histogram distribution. Region 11 (upper arm, mild sun exposure, 41 years) shows a higher distribution of DDB2 positive keratinocytes within 200 um distance from the skin surface and lower distribution of keratinocytes positive for p53 and Ki67

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/6.png" alt="alt text" title="image Title" />

**Example Region 7: Keratinocytes positive for markers of UV damage (p53), repair (DDB2) and proliferation (Ki67) and distance from skin surface**

Positive keratinocytes were shown as 3D distance plots from the skin surface and histogram distribution. Region 7 (lower forearm, marked sun exposure, 69 years) shows highest distribution of Ki67 positive keratinocytes within 200 µm distance from the skin surface, followed by p53 and lowest DDB2 positive keratinocytes.

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/16.png" alt="alt text" title="image Title" />

---

**Vascular Common Coordinate Framework Visualization - Immune Cell Cluster Density**

These interactive plots show the 3D view of the distribution and clustering of immune cells (T cells). The immune cell cluster view allows for the identification of areas with high immune cell density through the use of heatmap-like bubbles of varying sizes and colors. Large, yellow bubbles indicate a high density of immune cells, while small, dark blue bubbles indicate a lower density.

External link to the 3D view for the immune cells clustering views:

[Region 1](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_1_30.html) / [Region 2](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_2_30.html) / [Region 3](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_3_30.html) / [Region 4](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_4_30.html) / [Region 5](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_5_30.html) /

[Region 7](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_7_30.html) / [Region 8](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_8_30.html) / [Region 9](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_9_30.html) / [Region 10](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_10_30.html) / [Region 11](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_11_30.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/immune_cluster/immune_cluster_region_9_30.html)

Example Region 9: Medium-high immune cluster density plot from region 9 (donor 1, male aged 60 years, sample was from the lower distal arm region, with marked sun exposure).

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/12.png" alt="alt text" title="image Title" />

---

**Statistical comparison between 2D and 3D immune cell counts**

(A) Average number of all T cells within 30 µm of a T helper cell in 2D (red) and 3D (blue) for each region. Overall, the number of immune cells within 30 µm of a T helper cell was higher in 3D compared to 2D with 10-70% more cells found in 3D; (B) Maximum number of immune cells within 30 μm of a T helper cell. There was variation across all regions, for example, in region 7 there was a cluster of 11 immune cells within 30 μm in 3D while just 3 cells were quantified in 2D.

**(A)**
<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/10.png" alt="alt text" title="image Title" />

**(B)**
<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/11.png" alt="alt text" title="image Title" />

Histogram of distance of immune cells (CD68, T helper, T killer, and T reg) to nearest endothelial cell. 3D distance tends to be much shorter (distance was capped at 1000 µm for visualization). The average distance of the nearest endothelial cell to immune cells in 3D was approximately half that found in 2D (~56 µm vs 108 µm on average). Two sample Kolmogorov-Smirnov test was performed to confirm that there is statistically significant difference between the 2D and 3D distributions for total immune cell counts (D =0.43, p-value <2.2e-16).

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/13.png" alt="alt text" title="image Title" />

---

#### **Skin 3D Models**

The CCF 3D Reference Object Library provides anatomically correct reference organs. The organs are developed by a specialist in 3D medical illustration and approved by organ experts.

Initially, reference objects are created using data from the Visible Human male and female datasets provided by the National Library of Medicine. The male dataset comprises 1,871 cross-sections at 1mm intervals for both CT and anatomical images at a resolution of 4,096 pixels by 2,700 pixels. The female data set has the same characteristics as the Visible Human Male but axial anatomical images were obtained at 0.33 mm intervals resulting in 5,189 cross-section anatomical images. The male was white, 180.3 cm (71 inch) tall, 199-pound and was 38 years old. The female was white, 171.2 cm (67.4 inch) tall, obese, and 59 years old.

On March 12, 2022, a total of 50 reference organs--including the human skin--became available in GLB format. Each organ can be viewed and explored using free web browsers such as [Babylon.js.](https://sandbox.babylonjs.com/)

You can explore all the 3D models of the HRA at [https://humanatlas.io/3d-reference-library](https://humanatlas.io/3d-reference-library)

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/8.png" alt="alt text" title="image Title" />

The Visible Human Project skin, female (left) and male (right)

---

**Future work: Immune cells 3D mesh view**

These interactive plots show the 3D representation of a set of triangles with vertices that outline the immune cells. This part is our future work and not included in the paper. These visualizations allow for the observation of the spatial distribution of immune cells within a skin sample through the use of 3D meshes and polygons. These distributions highlight the differences in both the spatial arrangements and overlap of various types of immune cells. The 3D meshes and polygons are created based on the spatial coordinates of the immune cells, and the shape of the mesh can also be influenced by the parameter alphahull.

External link to the 3D mesh view for the immune cells:

[Region 1](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_1.html) / [Region 2](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_2.html) / [Region 3](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_3.html) / [Region 4](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_4.html) / [Region 5](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_5.html) /

[Region 7](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_7.html) / [Region 8](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_8.html) / [Region 9](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_9.html) / [Region 10](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_10.html) / [Region 11](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_11.html)

[<img alt="alt_text" width="84px" src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/button_load.png" />](https://hubmapconsortium.github.io/vccf-visualization-release/html/3d_mesh/3d_mesh_region_9.html)

**Example Region 9: 3D mesh view from region 9 (donor 1, male aged 60 years, sample was from the lower distal arm region, with marked sun exposure).**

<img src="https://raw.githubusercontent.com/hubmapconsortium/vccf-visualization-2022/main/docs/images/17.png" alt="alt text" title="image Title" />

---
