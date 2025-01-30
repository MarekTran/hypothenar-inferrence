# Hypothenar Hand Keypoint Inference

## Overview
This repository contains the code and data for hypothenar hand keypoint inference as part of the research project on automatic hand landmark detection for leprosy diagnosis.

The paper, "Automatic Hand Landmark Detection for Leprosy Diagnosis: Comparison of Output Adaptation Techniques for Hand Keypoint Prediction," is available in the TU Delft repository:

[**TU Delft Repository - Hypothenar Hand Keypoint Inference Paper**](https://repository.tudelft.nl/record/uuid:c22a52f5-decb-40c6-a5cd-934c59d266e4)

## Setup
To set up the environment and run the code, follow these steps:

### 1. Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

## Project Structure
```
├── hagrid/data/annotations/    # Dataset labels and notebook
├── hand-keypoints/             # Dataset labels and notebook
├── our_hands_dataset/          # Dataset labels and notebook
├── output/                     # Processed output data
├── hand_landmarker.task        # First draft of landmarking task
├── hpi_female_df.csv           # Dataset for female hands
├── hpi_male_df.csv             # Dataset for male hands
├── main.ipynb                  # Main implementation notebook
├── pyproject.toml              # Configuration file
├── requirements.txt            # Python dependencies
├── research_pipeline.ipynb     # Research process notebook
```

## Citation
If you use this work, please cite the paper using the provided TU Delft repository link above.

## Contact
Feel free to contact me on this GitHub account.

