# EFDL

This folder contains a minimal, clean, and ready-to-run implementation for full-cycle motion tracking regularization using Bspline, based on NVIDIA Modulus.

Further details will be provided upon publication.

## Folder Structure

- `motionTrackRegularization.py`: Main script for motion tracking regularization.
- `modulusDL/`: Minimal required custom modules for the main script.
- `conf/`: Example configuration file(s).
- `TRAINING_SET/`: Place your training data here (see below).
- Other files: Example mesh and STL files for demonstration.

## Installation

Install all required Python dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Prepare your configuration file in `conf/config_motionTrackRegularization.yaml`.
2. Place your training data (e.g., Bspline coefficient files) in `TRAINING_SET/`.
3. Run the main script and you will get motion tracking regularization results.

```bash
python motionTrackRegularization.py
```

## Data Preparation

- The script expects pairwise Bspline coefficient files

