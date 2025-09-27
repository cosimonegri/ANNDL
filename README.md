# Artificial Neural Networks and Deep Learning Challenges
Project for the _Artificial Neural Networks and Deep Learning_ course held at Politecnico di Milano in the academic year 2024-2025 by Professor Boracchi and Professor Matteucci.

> 🏆 This project received a perfect evaluation

## Table of contents
- [Challenge 1: Blood Cells Classification](#blood-cells-classification)
- [Challenge 2: Martian Terrain Semantic Segmentation](#martian-terrain-semantic-segmentation)
- [Team](#team)

# Blood Cells Classification

## Dataset
<img  width="100%" alt="bloodcells-dataset-sample" src="https://github.com/user-attachments/assets/cd951b17-030c-4c4c-8db0-9a2c7363093d" />
<br />
<br />

- **Image Size:** 96x96
- **Color Space:** RGB (3 channels)
- **Number of Images:** 13,759
- **Number of Classes:** 8

## Methodology
  - Built an initial Convolutional Neural Network (CNN)
  - Implemented techniques such as regularization and augmentation
  - Moved to Transfer Learning and Fine Tuning

## Results
The model we submitted achieved an 89% accuracy on the test set.

Check out the final [`report`](./Blood%20Cells%20Classification/report.pdf).

# Martian Terrain Semantic Segmentation

## Dataset
<img width="100%" alt="mars-dataset-sample" src="https://github.com/user-attachments/assets/616317cc-405d-412f-9ac2-2e46a02df745" />
<br />
<br />

- **Image Size:** 64x128
- **Color Space:** Grayscale (1 channel)
- **Number of Images:** 2,615
- **Number of Classes:** 5 (Background, Soil, Bedrock, Sand, Big Rock)

## Methodology
- Built an initial U-Net Convolutional Neural Network
- Implemented techniques such as oversampling and augmentation

## Results
The model we submitted achieved a 64% mean IoU (excluding the background class) on the test set.

Check out the final [`report`](./Martian%20Terrain%20Semantic%20Segmentation/report.pdf).

Check the competition on [kaggle](https://www.kaggle.com/competitions/an-2-dl-2024-2025-homework-2/overview).

# Team
[Luca Bordin](https://github.com/lucabord)<br />
[Mattia Menegale](https://github.com/mattymene)<br />
[Cosimo Giovanni Negri](https://github.com/cosimonegri)<br />
