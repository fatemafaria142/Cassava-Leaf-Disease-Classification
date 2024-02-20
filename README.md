# Cassava Leaf Disease Classification

## Overview
This project focuses on classifying cassava leaf diseases using various transformer models. The dataset consists of five distinct folders, each representing a specific disease affecting cassava plants: bacterial_blight, brown_streak_disease, green_mottle, mosaic_disease, and healthy.

## Models Used
1. [Vision Transformer (ViT)](https://huggingface.co/docs/transformers/model_doc/vit)
2. [Swin Transformer](https://huggingface.co/docs/transformers/model_doc/swin)
3. [SwiftFormer](https://huggingface.co/docs/transformers/model_doc/swiftformer)
4. [Pyramid Vision Transformer (PVT)](https://huggingface.co/docs/transformers/model_doc/pvt)
5. [PoolFormer](https://huggingface.co/docs/transformers/model_doc/poolformer)

## Results

| Model                        | Accuracy | Precision | Recall | F1 Score |
|------------------------------|----------|-----------|--------|----------|
| Vision Transformer (ViT)     | 0.7160   | 0.7131    | 0.7160 | 0.7052   |
| Swin Transformer             | 0.7560   | 0.7633    | 0.7560 | 0.7532   |
| SwiftFormer                  | 0.7280   | 0.7309    | 0.7280 | 0.7285   |
| Pyramid Vision Transformer   | 0.7660   | 0.7649    | 0.7660 | 0.7637   |
| PoolFormer                   | 0.7420   | 0.7453    | 0.7420 | 0.7428   |

## Dataset
The dataset can be found [here](https://www.kaggle.com/datasets/nirmalsankalana/cassava-leaf-disease-classification).
