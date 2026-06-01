# Super-Resolution Dataset Sample

A sample dataset supporting the paper:  
**"[Filling the Gap of Misrsat-2 Images Using Sentinel-2 Super-Resolved Images with Deep Learning Techniques]"**  
*Submitted to Scientific Reports*

---

## 📌 Overview
This repository provides a representative sample of the super-resolved satellite imagery generated in our study. The dataset demonstrates the application of a single-image super-resolution of MisrSat-2 and Sentinel-2 satellite imagery.

---

## 🛰️ Data Description

| Item | Details |
|------|---------|
| Sensors | MisrSat-2, Sentinel-2 |
| Low-Resolution Input Scale | 10m |
| High-Resolution Input Scale |2.5m |
| Number of Sample Patches | e.g., 8 image pairs |
| Format | .TIF |
| Geographic Region | Egypt |

---
## Repository Structure
├── Dataset Sample/LR/ # Low-resolution input patch samples.
├── Dataset Sample/HR/ # High-resolution reference patches.
├── Automatic_coregisterationSample # Sample before and after automatic co-registration.
├── test cases output # Sample of testing the RCAN final model on different areas.
└── README.md
## Full Dataset Access
The complete dataset is available upon reasonable request due to MisrSat-2 data  
policy restrictions imposed by the Egyptian Space Agency.  
Please contact: **B.Elgetan63952@student.aast.edu**
