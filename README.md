# ML4DQM – Vision Transformer Based Classification

This repository contains the solution for the ML4SCI ML4DQM evaluation test.

## Task
Classify HCAL DigiOccupancy images from two CMS runs using a Vision Transformer (ViT).

## Approach
- Data preprocessing with log normalization and min–max scaling
- Stratified subsampling to handle memory constraints
- Vision Transformer (ViT-Tiny, Patch16) for classification
- Evaluation using Accuracy, ROC Curve, and AUC

## Results
- Validation AUC ≈ 1.0
- Test AUC ≈ 1.0
- Strong separability between the two runs

## Notes
Due to computational constraints, experiments were performed on a representative stratified subset of the data.
