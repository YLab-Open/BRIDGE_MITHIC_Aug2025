# BRIDGE_MITHIC_Aug2025
Materials for MITHIC event (Aug 18, 2025).

## Resource 

**Paper BRIDGE**: Benchmarking Large Language Models for Understanding Real-world Clinical Practice Text (https://arxiv.org/abs/2504.19467)

**Github repo**: BRIDGE (https://github.com/YLab-Open/BRIDGE)

**Dataset**: BRIDGE-Open (https://huggingface.co/datasets/YLab-Open/BRIDGE-Open)

**Leaderboards**: BRIDGE-Medical-Leaderboard (https://huggingface.co/spaces/YLab-Open/BRIDGE-Medical-Leaderboard)


## Download and organize files
(Optional) A. Download the dataset from Hugging Face via python script

See dataset_download.py for more details. (Requirement: pip install huggingface_hub)

(Optional) B. Manually Download the dataset from Hugging Face

1. Web: https://huggingface.co/datasets/YLab-Open/BRIDGE-Open/tree/main

2. Manually download **"Dataset.zip"** and **"Examples.zip"** files

3. Extract them to the **"dataset_raw"** directory

Finally, the directory structure should look like this:
```
dataset_raw/
├── task_1.SFT.json
├── task_1.SFT.json
└── example/
    ├── task_1.example.json
    ├── task_1.example.json
```