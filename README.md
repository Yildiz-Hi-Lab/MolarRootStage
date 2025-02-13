# Root Development Stages Dataset

## Overview
This dataset was created to develop a convolutional neural network (CNN)-based end-to-end learning architecture for predicting the root development stages of permanent first molar teeth using panoramic radiographs. The dataset consists of 1629 first molar images labeled according to the Cvek classification.
![ExamlpeImagesShownV2](https://github.com/user-attachments/assets/10bc73db-7f56-4630-87b9-d0489abfda03)

## Dataset Composition
The dataset is divided into five distinct subsets (DB-1 to DB-5) based on root development stages and whether the apical foramen is open or closed:
- **DB-1**: Root development stage classification
- **DB-2**: Root development stage classification
- **DB-3**: Root development stage classification
- **DB-4**: Binary classification (open vs. closed apical foramen)
- **DB-5**: Enhanced binary classification (open vs. closed apical foramen)

![DataSetInfoV2](https://github.com/user-attachments/assets/5dd75715-1111-42e3-b784-7903696b28c0)

## Data Collection and Preprocessing
- **Tooth Patches Extraction**: The YOLO approach was used to crop teeth patches from panoramic radiographs.
- **Stage Prediction Models**: VGG-19, InceptionV3, and EfficientNetB models were employed for classification tasks.
- **Optimizer**: The Adamax optimizer with a learning rate of 10⁻³ yielded the best results.
![aa_ornek_dis](https://github.com/user-attachments/assets/295efb52-d219-4c62-8341-5a775052e514)

## Performance Metrics
- **First molar detection**: Precision (98.4%), Recall (97.6%)
- **Classification accuracy**:
  - DB-1: 64.21%
  - DB-2: 62.66%
  - DB-3: 69.64%
  - DB-4: 84.57%
  - DB-5: 94.89%

## Potential Applications
This dataset and the associated CNN models provide a valuable tool for dental diagnostics, particularly in assisting clinicians with treatment planning based on root development stages.

## Citation
If you use this dataset in your research, please cite our work:
```
@article{your_citation,
  author = {Your Name(s)},
  title = {End-to-End CNN-Based Detection of Permanent First
Molars and Prediction of Root Development Stages
from Panoramic Radiographs},
  journal = {Your Journal},
  year = {202X},
  volume = {X},
  number = {X},
  pages = {XX-XX},
  doi = {DOI_HERE}
}

