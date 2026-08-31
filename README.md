# Fracture Detection using YOLOv8

An AI-assisted system for detecting bone fractures in X-ray images, built as part of the **Seasons of Code (SoC), IIT Bombay**: "AI for Healthcare" project.

## Overview
This project trains a **YOLOv8** object detection model to identify fractures in X-ray images, with the goal of supporting faster and more consistent preliminary screening.

## Contents
- `Fracture Detection Report.pdf` — full project report covering methodology, dataset, training process, and results.
- `SoC_Final_25B2251.ipynb` — Jupyter notebook with the data preprocessing, model training, and evaluation code. 

## Approach
1. **Dataset cleaning** — curated and preprocessed a real-world X-ray dataset for training.
2. **Model training** — fine-tuned YOLOv8 for fracture detection.
3. **Evaluation** — assessed model performance using confusion matrix analysis.
4. **Keypoint-based alignment analysis** — a custom method built to assess fracture severity/displacement beyond simple detection.

## Details
See `Fracture Detection Report.pdf` for the full write-up, including dataset details, training configuration, and results.
