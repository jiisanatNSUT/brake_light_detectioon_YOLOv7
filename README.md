# brake_light_detectioon_YOLOv7

Implementation of **Forward vehicle brake light detection for avoiding road 
accidents using Yolov7 and IR sensor**

DOI: https://doi.org/10.1007/s11042-024-19427-x

### Project Structure

```bash
brake_light_detection_YOLOv7
│
├── README.md
├── requirements.txt
├── data                        
│   ├── raw                     # Folder for raw dataset files (small or a sample of data)
│   ├── processed               # Pre-processed dataset used in training (small samples for repo)
│   └── download_script.sh      # Script to download full dataset
│
├── src
│   ├── data_processing         # Scripts for dataset processing and annotation
│   │   └── annotation_tool.md  # Guide for annotation with MakesenseAI
│   ├── models                  # Model training and testing code
│   │   ├── yolov7              # YOLOv7 model-specific scripts and configs
│   │   └── ir_sensor           # Code for integrating IR sensor with brake light detection
│   └── utils                   # Helper functions and utilities
│
├── notebooks                   # Jupyter notebooks for experimentation and visualization
│   └── data_exploration.ipynb  # Notebook for exploring dataset characteristics
│
├── configs                     # Configuration files (e.g., YOLOv7 training config, hyperparameters)
│
└── results                     # Folder for storing experiment results, logs, and model checkpoints
    ├── logs
    └── checkpoints

```