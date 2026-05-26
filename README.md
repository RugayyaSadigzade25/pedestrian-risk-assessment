# Pedestrian Risk Assessment for Autonomous Vehicles

A multi-stage pedestrian risk assessment pipeline integrating YOLOv8m detection, SAM2 segmentation, and a rule-based risk scoring method. Evaluated on selected clips from the JAAD and PIE datasets.

## Notebooks

- `Jaad.ipynb` — YOLOv8m and SAM2 evaluation on the selected JAAD clip
- `PIE.ipynb` — YOLOv8m and SAM2 evaluation on the selected PIE segment
- `JAAD&PIE_results.ipynb` — Combined results and confusion matrices
- `RiskAssessment_PIE.ipynb` — Annotation-driven risk assessment on PIE set03/video_0006
- `JAAD_RiskAssessment_CantBeDone.ipynb` — JAAD risk assessment attempt (not completed due to missing numerical vehicle data)

## Datasets

This repository does not include dataset files. Download JAAD and PIE from their official sources:
- JAAD: https://data.nvision2.eecs.yorku.ca/JAAD_dataset/
- PIE: https://data.nvision2.eecs.yorku.ca/PIE_dataset/

## Requirements

- Python 3.x
- Google Colab
- ultralytics
- opencv-python
- numpy
- pandas
