# Fine Tuning BERT for Medical Text Analysis

## Description

Combined Dataset Approach

1. Multi-task learning: Train BERT to perform two related but distinct tasks:

- Clinical diagonsis classification using MIMIC-III
- Rhetorical role classification using PubMed RCT

2. Knowledge transfer: Fine-tune BERT first on the larger PubMed RCT dataset to learn medical language patterns, then further fine-tune on MIMIC-III for the specific clinical task
3. Dataset Augmentation: Use PubMed RCT to augment your training data, especially for medical concepts that might be underrepresented in MIMIC-III
4. Comparative analysis: Compare model performance when trained on clinical notes vs research literature analyze how different types of medical texts affect BERT's understanding.

## Project Structure

## Getting Started

### Dependencies

### Installing

## Help

## Authors

[Austin Thapa](https://github.com/austinthapa)
Email: [anilthapa1.at23@gmail.com]()

## License

This project is licensed under MIT License. Please see [LICENSE](https://github.com/austinthapa) for more information.

## Acknowledegments
