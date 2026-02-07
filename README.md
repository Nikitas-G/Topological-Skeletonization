# Biomimetic Design Thinking: Roots to Routes

This repository contains the computational framework for extracting structural patterns from natural venation systems to inform sustainable textile design. This project is part of the research submitted to the *Cumulus Athens 2026 Conference*.

## Overview
The core objective is to integrate *Biomimicry* into the *Design Thinking* process. By using topological skeletonization, we translate biological "Roots" (venation patterns) into parametric "Routes" (design scaffolds). This method prioritizes material efficiency and structural integrity at the earliest stages of the design process.

Key Features
* Skeletonization: Extracts the 1-pixel structural core of organic patterns.
* Topological Analysis: Automatically identifies junctions (branching points) and endpoints.
* Structural Scaffolding: Provides a digital map for sustainable material distribution.

Technical Requirements
* Python 3.x
* NumPy
* Matplotlib
* Scikit-image
* SciPy
* Pillow (PIL)

Usage
1. Upload your biological reference image (e.g., `Roots.jpg`).
2. Run the extraction script to generate the topological map.
3. The script will output a visualization highlighting *Structural Junctions* (red) and *Endpoints* (blue).

Research Context
This work positions biomimetic reasoning as a practical means of embedding sustainability within the design process itself, rather than treating it as an external corrective concern.

License
MIT License
