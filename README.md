# Hallucination Reduction in Multimodal LLMs using Knowledge Graphs

## Project Overview

This project aims to improve medical image understanding by integrating Knowledge Graph embeddings with Vision Transformer (ViT). DenseNet121 is used as the baseline model, while ViT + TransE represents the proposed hybrid model.

## Objectives

• Classify medical images into anatomical regions.

• Compare DenseNet121 with ViT + TransE.

• Study the impact of Knowledge Graph integration.

## Dataset

Classes:

• Lung

• Abdomen

• Brain_Tissue

• Pelvic Cavity

• Brain

Training Images : 406

Testing Images : 174

## Models

### Traditional Model

DenseNet121

### Proposed Model

Vision Transformer (ViT)

+

TransE Knowledge Graph Embeddings

## Results

DenseNet121

Accuracy : 90.8%

ViT + TransE

Accuracy : 99.43%

## Technologies

Python

PyTorch

Transformers

Knowledge Graph

TransE

Google Colab

Streamlit

## Future Scope

• Larger datasets

• Real-time clinical deployment

• Integration with Medical LLMs
