# RF-DETR-for-Object-Detection
Building an object detection system using the RF-DETR (Receptive Field Enhanced Detection Transformer) model.


## RF-DETR Ship Detection

This project implements object detection for various ship types using the RF-DETR (Receptive Field Enhanced Detection Transformer) model. The model is trained on a custom dataset of annotated ship images in COCO format using Roboflow.

### Ship Classes

The dataset includes 10 classes:
- Bulk Carrier
- Container Ship
- General Cargo
- Oil Products Tanker
- Passengers Ship
- Tanker
- Trawler
- Tug
- Vehicles Carrier
- Yacht

## Dataset

- **Roboflow Dataset Link**: [DatasetShips](https://universe.roboflow.com/visocomputacional/datasetships)

## Model

- **Model**: RF-DETR Medium
- **Framework**: PyTorch
- **Format**: COCO
- **Training Epochs**: 50

```
## Folder Structure
.
├── DatasetShips-1/
│ ├── train/
│ ├── valid/
│ └── test/
├── rfdetr_output/
│ └── model weights and logs
├── visualize_predictions.py
├── train_model.py
└── README.md
```
