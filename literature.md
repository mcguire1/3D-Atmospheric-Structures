# Literature Review: Structural Representations of Atmospheric Systems

This collection contains papers relevant to the development of a 4D atmospheric graph data model for spatiotemporal pattern recognition. The papers are organized by their relevance to graph representation, atmospheric structural extraction, and foundational computational methods.

## 1. Closest to Our Proposed Graph Representation

| Paper | Year | Relevance |
| --- | --- | --- |
| [Time-varying Extremum Graphs](https://doi.org/10.1111/cgf.15162) | 2024 | Spatial topology and temporal graph relationships, including splits and merges. |
| [Topological Characterization and Uncertainty Visualization of Atmospheric Rivers](https://doi.org/10.1111/cgf.15084) | 2024 | Extracts topological skeletons of atmospheric rivers. |
| [Flexible and Probabilistic Topology Tracking With Partial Optimal Transport](https://doi.org/10.1109/TVCG.2025.3561300) | 2025 | Probabilistic tracking graphs and temporal correspondence between topological features. |
| [A Taxonomy for Feature Tracking in Time-Varying Piecewise-Linear Scalar Fields](https://doi.org/10.1109/TVCG.2026.3747690) | 2026 | Framework for understanding and combining feature-tracking algorithms. |

## 2. Atmospheric Structural Extraction and Tracking

| Paper | Year | Relevance |
| --- | --- | --- |
| [Robust Detection and Visualization of Jet-Stream Core Lines in Atmospheric Flow](https://doi.org/10.1109/TVCG.2017.2743989) | 2018 | Extracts 3D structural centerlines from wind fields. First published online in 2017. |
| [A Ridge-based Approach for Extraction and Visualization of 3D Atmospheric Fronts](https://doi.org/10.1109/VIS55277.2024.00043) | 2024 | Extracts 3D atmospheric structures as surfaces rather than skeletons. |
| [CoCoMET v1.0: A Unified Open-Source Toolkit for Atmospheric Object Tracking and Analysis](https://doi.org/10.5194/gmd-18-5971-2025) | 2025 | Framework for identifying and tracking 2D/3D atmospheric objects over time. |
| [Interactive 3D Visual Analysis of Atmospheric Fronts](https://doi.org/10.1109/TVCG.2018.2864806) | 2018 | Extends objective frontal identification and visualization into three dimensions. |

## 3. Foundational Methods and Implementation

| Paper | Year | Relevance |
| --- | --- | --- |
| [A Topological Approach to Simplification of Three-Dimensional Scalar Fields](https://escholarship.org/uc/item/6mq482jn) | 2006 | Morse–Smale complexes and simplification of 3D scalar-field topology. |
| [Topological Spines: A Structure-Preserving Visual Representation of Scalar Fields](https://ieeexplore.ieee.org/document/6064947) | 2011 | Introduces extremum graphs as sparse structural representations of scalar fields and topological spines as their geometric visualization. |
| [A New Python Library to Analyse Skeleton Images Confirms Malaria Parasite Remodelling of the Red Blood Cell Membrane Skeleton](https://doi.org/10.7717/peerj.4312) | 2018 | Introduces Skan for converting skeletons into graphs and analyzing branch geometry. |

## 4. Suggested Reading Priority

The immediate objective is to understand existing graph data models and determine whether they already support the spatial, temporal, and physical relationships envisioned for this project.

### 1. Correa et al. (2011)

**Topological Spines: A Structure-Preserving Visual Representation of Scalar Fields**

- What does an extremum graph represent?
- How is the graph constructed from the Morse–Smale complex?
- What geometric and topological information is preserved or discarded?
- How does the representation generalize to higher dimensions?

### 2. Das et al. (2024)

**Time-varying Extremum Graphs**

- What does the time-varying extremum graph actually store?
- How are temporal relationships represented?
- How are splitting and merging events handled?
- What information about the original 3D structure is lost?

### 3. Lan et al. (2024)

**Topological Characterization and Uncertainty Visualization of Atmospheric Rivers**

- How are atmospheric skeletons extracted and represented?
- What information does the graph preserve about atmospheric structure?
- What are the limitations of using vertically integrated vapor transport?
- How might the approach extend to vertically resolved atmospheric fields?

### 4. Li et al. (2025)

**Flexible and Probabilistic Topology Tracking With Partial Optimal Transport**

- How are temporal correspondences established?
- How is uncertainty in feature correspondence represented?
- Could probabilistic relationships be incorporated into an atmospheric graph data model?

### 5. CoCoMET (2025)

**A Unified Open-Source Toolkit for Atmospheric Object Tracking and Analysis**

- How does atmospheric object tracking represent physical attributes?
- How are structural evolution, splitting, and merging represented?
- Does the representation preserve internal object geometry?
- How might skeleton graphs complement existing object-based methods?

## 5. Research Lineage

The following papers establish a preliminary methodological lineage:

```text
Morse–Smale Complexes
        |
        v
Extremum Graphs
Correa et al. (2011)
        |
        v
Time-varying Extremum Graphs
Das et al. (2024)
        |
        v
Attributed Spatiotemporal Graphs
for Atmospheric Structural Analysis
(Proposed Research Direction)
