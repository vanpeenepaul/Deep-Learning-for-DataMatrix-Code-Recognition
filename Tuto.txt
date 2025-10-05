## Prerequisites

### Dataset
To reproduce the experiments, you will need a dataset structured as follows:
- 6 folders containing DataMatrix code images
- One annotation file in JSON COCO format per folder

**If your dataset is not in this format**, refer to script `(1)` to adapt your data. This script contains conversion utilities I used to make my dataset compatible.

## Reproducing the Experiments

### Training
To reproduce and understand the training process:

1. Run scripts `(2)`, `(3)`, and `(4)` in order
2. Each cell is commented to facilitate understanding
3. For more theoretical details, refer to the "Development of Python Scripts" section of the report

### Prediction
To load weights from a previous experiment and predict cell positions on new DataMatrix codes:
- Run script `(5)`

### Visualization
To visualize the implemented concepts on your dataset images:
- Run program `(0)`

## Additional Documentation

For a thorough understanding of the implementation, consult the attached report, particularly the "Development of Python Scripts" section.

## Supervision

Work completed under the supervision of Sarra Laksaci.
