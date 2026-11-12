# Literature Review: Structural Representations of Atmospheric Systems

Updated: November 12, 2026.

This collection consolidates the literature identified during our investigation of attributed 4D atmospheric graphs for spatiotemporal pattern recognition and machine learning. It contains 27 core papers, plus contextual references below. The objective is to assess existing representations and determine whether explicit structural graphs enable meaningful discovery beyond conventional grid-based methods.

The relevance notes are preliminary research assessments, not established novelty claims. This is a cumulative bibliography from our discussions, not a systematic or exhaustive review. Some publication years and titles are carried forward from earlier notes and should be checked against publisher metadata before formal citation.

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

## 4. Meteorological Structure and Multi-Phenomenon Tracking

| Paper | Year | Relevance |
| --- | --- | --- |
| [Improving the Understanding of Atmospheric River Water Vapor Transport Using a Three-Dimensional Straightened Composite Analysis](https://doi.org/10.1029/2021JD036159) | 2022 | Three-dimensional composites of atmospheric rivers; benchmark for vertical moisture transport organization. |
| [Moisture Transport Axes: A Unifying Definition for Tropical Moisture Exports, Atmospheric Rivers, and Warm Moist Intrusions](https://doi.org/10.5194/wcd-6-431-2025) | 2025 | Physically motivated extraction of moisture transport axes; important prior art for structural representations. |
| [A Three-Dimensional Perspective on Extratropical Cyclone Impacts](https://journals.ametsoc.org/view/journals/clim/33/13/jcli-d-19-0445.1.xml) | 2020 | Three-dimensional cyclone characterization and impacts; motivation for moving beyond surface-based descriptors. |
| [Differentiating Average and Extreme Extra-Tropical Cyclones by Their Vertical Tilt and Potential Vorticity Structure](https://doi.org/10.1029/2025GL119822) | 2026 | Köhler and Sinclair compare vertical tilt and PV structure in ERA5; vertically matched vorticity maxima provide a natural structural baseline. |
| [Warm Conveyor Belt Characteristics and Impacts Along the Life Cycle of Extratropical Cyclones: Case Studies and Climatological Analysis Based on ERA5](https://doi.org/10.5194/wcd-5-537-2024) | 2024 | Trajectory-based identification of ascending airstreams and their organization through cyclone life cycles. |
| [A Composite-Based Analysis of the Dynamical Linkage of Atmospheric Rivers, Warm Conveyor Belts, and Extratropical Cyclones](https://doi.org/10.5194/wcd-7-2043-2026) | 2026 | Ferreira et al. examine coupled moisture transport, ascent, precipitation, and cyclone development; motivates learning configurations of interacting structures. |
| [TempestExtremes v2.1: A Community Framework for Feature Detection, Tracking, and Analysis in Large Datasets](https://doi.org/10.5194/gmd-14-5023-2021) | 2021 | Generalized atmospheric feature detection and tracking; critical baseline against claims of multi-phenomenon generality. |

## 5. Topological Data Analysis and Atmospheric Machine Learning

| Paper | Year | Relevance |
| --- | --- | --- |
| [Topological Data Analysis and Machine Learning for Recognizing Atmospheric River Patterns in Large Climate Datasets](https://doi.org/10.5194/gmd-12-613-2019) | 2019 | Muszynski et al. combine topological descriptors with supervised ML; closest identified precursor at the intersection of atmospheric topology and pattern recognition. |
| [A Topological Perspective on Weather Regimes](https://doi.org/10.1007/s00382-022-06395-x) | 2023 | Strommen et al. use persistent homology to investigate atmospheric regimes in phase space rather than internal physical-space structure. |
| [A Primer on Topological Data Analysis to Support Image Analysis Tasks in Environmental Science](https://doi.org/10.1175/AIES-D-22-0039.1) | 2023 | Environmental image classification using persistent homology and ML, including mesoscale cloud organization. |

## 6. Unsupervised Atmospheric Pattern Discovery and Representation Learning

| Paper | Year | Relevance |
| --- | --- | --- |
| [A Probabilistic View on Modelling Weather Regimes](https://doi.org/10.1002/joc.7942) | 2023 | Variational autoencoders and probabilistic regime discovery; alternative learned representation. |
| [Identifying Climate Patterns Using Clustering Autoencoder Techniques](https://doi.org/10.1175/AIES-D-23-0035.1) | 2024 | Unsupervised pattern discovery from climate simulation fields; potential grid-based ML baseline. |
| [Unsupervised Detection of Large-Scale Weather Patterns in the Northern Hemisphere via Markov State Modelling](https://doi.org/10.1038/s41612-024-00659-5) | 2024 | Discovers recurring atmospheric states and transitions; relevant to temporal pattern recognition. |
| [Weather Regime Diversity, Transitions, and Trends Using Hexagonal Self-Organizing Maps](https://doi.org/10.1029/2025JD044874) | 2026 | Wichrowski et al. learn weather regimes and their diversity and transitions from geopotential height anomalies. |

## 7. Functional Climate Networks

| Paper | Year | Relevance |
| --- | --- | --- |
| [Spatiotemporal Characteristics and Propagation of Summer Extreme Precipitation Events Over United States: A Complex Network Analysis](https://doi.org/10.1029/2020GL088185) | 2020 | Network analysis of synchronized extreme precipitation events and propagation pathways. |
| [Key Propagation Pathways of Extreme Precipitation Events Revealed by Climate Networks](https://doi.org/10.1038/s41612-024-00701-6) | 2024 | Climate networks for identifying propagation pathways of extreme precipitation. |

Functional climate networks typically connect locations through statistical dependence or event synchronization. Our candidate graphs instead encode extracted spatial structures, geometric or topological connectivity, and temporal correspondence. The distinction is important when evaluating prior art.

## 8. Recommended Research Rabbit Seeds

These five papers cover complementary citation networks. The selection favors breadth across the main research questions rather than simply selecting the five most closely related graph papers.

| Priority | Seed | Citation network to explore |
| --- | --- | --- |
| 1 | [Das et al. (2024), Time-varying Extremum Graphs](https://doi.org/10.1111/cgf.15162) | Spatial topology, temporal correspondence, graph construction, splitting and merging. |
| 2 | [Lan et al. (2024), Topological Characterization and Uncertainty Visualization of Atmospheric Rivers](https://doi.org/10.1111/cgf.15084) | Atmospheric skeleton extraction, physical-space topology, geometry preservation, atmospheric river characterization. |
| 3 | [Muszynski et al. (2019), Topological Data Analysis and Machine Learning for Recognizing Atmospheric River Patterns in Large Climate Datasets](https://doi.org/10.5194/gmd-12-613-2019) | Atmospheric topology combined with ML; forward citations that may address 3D, multivariate, or skeleton-based extensions. |
| 4 | [Identifying Climate Patterns Using Clustering Autoencoder Techniques (2024)](https://doi.org/10.1175/AIES-D-23-0035.1) | Unsupervised climate pattern discovery and grid-based representation learning; potential comparison methods. |
| 5 | [Köhler and Sinclair (2026), Differentiating Average and Extreme Extra-Tropical Cyclones by Their Vertical Tilt and Potential Vorticity Structure](https://doi.org/10.1029/2025GL119822) | Meteorological motivation for 3D structure, vertical alignment, and physically meaningful evaluation baselines. |

### Reading priorities and questions

- **Das:** What does the graph actually store? How are temporal edges defined? What geometry is lost?
- **Lan:** What does the atmospheric skeleton preserve? What is lost through vertical integration and geometric simplification?
- **Muszynski:** Which topological descriptors support recognition? Have later papers pursued 3D fields, multivariate topology, or skeletonization?
- **Clustering autoencoders:** How are learned patterns validated? What baseline would allow a fair comparison with graph-derived representations?
- **Köhler and Sinclair:** What information about cyclone organization is omitted by a single vertically tracked axis, and would additional information be meteorologically meaningful?

Correa et al. (2011) remains essential foundational reading, but Das cites it directly, so it need not occupy a separate seed slot. TempestExtremes and CoCoMET are important checks against overstating novelty in detection and tracking. Ferreira et al. (2026) is a promising later seed for interactions among atmospheric structures.

## 9. Research Lineage

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
```

## 10. Questions to Guide the Literature Review

For each paper, identify:

1. **Vertices:** What entities do the vertices represent?
2. **Edges:** What spatial, temporal, or physical relationships are encoded?
3. **Attributes:** What information is associated with vertices and edges?
4. **Geometry:** How much of the original spatial structure is preserved?
5. **Time:** How are temporal relationships and structural evolution represented?
6. **Scales:** Does the representation support multiple spatial or temporal scales?
7. **Analysis:** What computational operations does the representation enable?
8. **Limitations:** What information is lost or cannot be represented?

## 11. Research Rabbit Collections

- Topological graph representations: Morse–Smale complexes, extremum graphs, topological spines, Reeb graphs, merge trees.
- Spatiotemporal feature tracking: temporal correspondence, structural evolution, probabilistic topology tracking.
- Atmospheric structural representations: skeletons, transport axes, cyclone tilt, fronts, object tracking, interacting systems.
- Atmospheric topology and ML: persistent homology, structural features, supervised and unsupervised learning.
- Unsupervised atmospheric pattern discovery: autoencoders, weather regimes, state transitions, structural clustering.
- Functional climate networks: synchronization, statistical dependence, propagation pathways.

## 12. Contextual References

These were discussed during the project but are not part of the 27-paper core bibliography.

| Reference | Relevance |
| --- | --- |
| [Characterizing Sensor Datasets with Multi-Granular Spatio-Temporal Intervals (McGuire, Janeja, and Gangopadhyay, 2011)](https://doi.org/10.1145/2093973.2094045) | Earlier SIGSPATIAL research on spatiotemporal pattern recognition; intellectual lineage for the current data-model direction. |
| [ARTMIP-related dataset article (2025)](https://doi.org/10.1038/s41597-025-06198-9) | Context for atmospheric river detection-method intercomparison; exact title and metadata to verify before formal citation. |
| [TempestExtremes: A Framework for Scale-Insensitive Pointwise Feature Tracking on Unstructured Grids (2017)](https://doi.org/10.5194/gmd-10-1069-2017) | Predecessor to TempestExtremes v2.1 and background on established feature-tracking research. |

The scale-aware perturbation paper [arXiv:2605.00510](https://arxiv.org/abs/2605.00510) belongs primarily to the separate, student-led tornado XAI project. It is retained here as a cross-project pointer, not as core structural-graph literature.

## Research Motivation

The objective is not simply to develop another skeletonization algorithm or visualization technique. The broader research question is whether graph-based data representations can support spatiotemporal pattern recognition by explicitly capturing meaningful structural relationships in complex systems.

Atmospheric fields provide the initial experimental domain. Skeletonization and computational topology provide potential methods for constructing the representation.

The literature review should establish whether existing representations already provide the required functionality and where meaningful opportunities for methodological contributions remain.

## Current Research Questions

- Can a common attributed graph data model represent structurally different atmospheric phenomena without requiring a different schema for each?
- Can graphs preserve internal 3D geometry and topology beyond conventional object descriptors or vertically tracked axes?
- Does unsupervised learning from graph-derived features reveal physically meaningful recurring configurations beyond those found using gridded fields or summary statistics?
- Can spatial, temporal, and cross-variable edges represent interacting atmospheric structures without conflating geometric proximity, feature correspondence, and physical transport?

Potential experimental domains include atmospheric rivers, tropical cyclones, extratropical cyclones, and tornado-producing environments. ERA5 cannot resolve tornado-scale circulation; the last domain concerns the environment rather than the tornado itself. Phenomenon and variable selection should be driven by meteorological literature. Graph generalizability and extraction generalizability are separate questions.

## Open Literature Gaps to Investigate

The literature already establishes atmospheric feature tracking, topological skeleton extraction, topology-based supervised recognition, and unsupervised regime discovery. We have not established whether explicit attributed 3D atmospheric skeleton graphs have already been used for unsupervised spatiotemporal pattern discovery or learning configurations of interacting structures. These are search targets, not verified research gaps.
