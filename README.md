# DNA Sequence Classification Using Deep Learning

This repository contains the implementation of a  project focused on classifying human DNA sequences into functional gene families using deep learning models, specifically LSTM and Transformer architectures.

## Project Overview

The objective of this project is to explore the use of deep learning techniques in bioinformatics by classifying DNA sequences based on their functional characteristics. The dataset used contains DNA sequences from humans, chimpanzees, and dogs, but the final focus was solely on human DNA due to better results.

## Dataset

- Source: Kaggle
- Contents: DNA sequences from three species (Human, Chimpanzee, Dog)
- Final Focus: Classification of **human** DNA sequences into **six gene families**:
  - G-Protein Coupled Receptors (GPCRs)
  - Tyrosine Kinase
  - Tyrosine Phosphatase
  - Synthase
  - Ion Channel
  - Transcription Factor

## Data Preprocessing

- Outlier detection and removal
- Handling missing values
- Exploratory Data Analysis (EDA)
- Sequence length distribution visualization

## Models Used

- **LSTM (Bidirectional)**: Achieved 73.06% accuracy with low loss (0.0868)
- **Transformer-based model**: Achieved 74.77% accuracy but with higher loss (1.7148)

## Tools & Technologies

- Python
- PyTorch
- Pandas, Matplotlib, Seaborn (for EDA)

## Conclusion

This project demonstrates the potential of deep learning models in the classification of biological sequences. While both models performed well, further optimization and regularization can improve Transformer generalization.

## Authors

- **Sara Alsanajleh**  
- **Ghada Abu Shaqra**  
Department of Computer Science, Jordan University of Science and Technology

