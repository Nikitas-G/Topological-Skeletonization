Topological Skeletonization for Biomimetic Textile Design

## Research Context
This repository contains the computational framework developed for the paper **"Roots to Routes: Integrating Biomimetic Reasoning in Design Thinking"**, submitted to the **Cumulus Athens 2026 Conference**. 

The study explores the transition from biological structural analysis (Roots) to parametric design output (Routes) through the lens of material efficiency and zero-waste manufacturing.

## Abstract
This project operationalizes a biomimetic design methodology by extracting topological data from natural venation systems. Using skeletonization algorithms and neighborhood-count convolutions, the framework identifies critical structural nodes. These data points are subsequently utilized to generate geometric scaffolds suitable for additive manufacturing, specifically targeting 3D knitting path optimization.

## Core Methodology
The framework is structured into four distinct computational phases:

1.  **Image Processing**: Grayscale conversion and Otsu thresholding of biological references.
2.  **Topological Skeletonization**: Morphological reduction of organic forms to a 1-pixel structural backbone using the scikit-image library.
3.  **Feature Extraction**: Identification of structural junctions and terminals via 3x3 convolution kernels.
4.  **Geometric Synthesis**: Generation of a Delaunay triangulation mesh to facilitate variable density material distribution.

## Technical Specifications and Dependencies
The implementation is written in Python The following scientific libraries are required:

* **NumPy**: Array manipulation and numerical analysis.
* **SciPy**: Spatial algorithms and convolution operations.
* **Scikit-image**: Morphological skeletonization and image filtering.
* **Matplotlib**: Technical visualization and data plotting.
* **Pillow (PIL)**: Image I/O operations.

Installation of requirements:
```bash
pip install numpy scipy scikit-image matplotlib pillow
