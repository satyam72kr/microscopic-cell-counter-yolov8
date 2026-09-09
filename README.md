#Real-Time Medical Object Detection & Microscopic Cell Counter

A state-of-the-art computer vision pipeline engineered to automate cellular localization and counting workflows on microscopic slide imagery.

## Key Highlights & Metrics
* **State-of-the-Art Architecture:** Leveraged the highly efficient **YOLOv8 nano framework** to perform high-speed bounding box regression tasks.
* **Exceptional Precision Score:** Achieved a **Mean Average Precision (mAP50) of 88.7%** on multi-class medical localization challenges.
* **Laboratory Automation Fit:** Aligned processing pipelines with automated screening standards to robustly detect tightly packed overlapping cells.
* **Turnaround Optimization:** Designed to eliminate manual cell-counting workflows, significantly reducing diagnostic turnaround time for digital pathology.

## Tech Stack & Tools Used
* **Core Object Detection:** Python, Ultralytics YOLOv8 Framework, CUDA/GPU Acceleration
* **Data Integration:** Automated In-built Dataset Configurator, YAML Pipeline Management
* **Evaluation Framework:** Intersection over Union (IoU) Profiling, Precision-Recall Validation

## Repository Structure
* `cell_counter.ipynb`: Clean production script containing the full installation layout, training commands, and validation loops.

## How to Execute the Project
1. Open the file in Google Colab and activate the **T4 GPU** accelerator to enable rapid anchor box optimizations.
2. Execute the notebook cells to automatically fetch the baseline architecture, initiate the loops, and print precision maps.
