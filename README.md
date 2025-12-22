# Space Object Tracking

A lightweight project for detecting and tracking space objects in image data.

This repository contains a Jupyter notebook and sample data that demonstrate how to identify and track objects (e.g., streaks, centroids) in astronomical or space imagery using classical image processing techniques. It’s designed as a starting point for experiments in space object detection and tracking.

---
<img width="640" height="647" alt="single_streak_detection" src="https://github.com/user-attachments/assets/2a55e011-e9f1-4383-bd17-f0277cce46ae" />


## Repository Contents

- **`main.ipynb`** — Core notebook with detection and visualization logic.  
- **`environment.yml`** — Conda environment specification for easy setup.  
- **Sample data** — Example images and CSV files used for demonstration.

---

## Setup

Create and activate the (lightweight) Conda environment:

```bash
conda env create -f environment.yml
conda activate envname
```

## How to Run

Follow these steps to set up and run the project locally:

**Clone the repository**
```bash
git clone https://github.com/rkarmaka98/space-object-tracking.git
cd space-object-tracking
```

## Dependencies

This project uses a focused set of image-processing libraries to keep the environment lightweight and reproducible.

### Conda packages

These are defined in environment.yml and will be installed automatically when creating the env:

* Python 3.10 — Base language
* NumPy — Numerical operations
* OpenCV — Image loading and processing
* scikit-image — Additional image-processing utilities
* Matplotlib — Visualization
* Example environment.yml
