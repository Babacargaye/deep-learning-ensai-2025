# Deep Learning Project - ENSAI 2025

## Flower Classification & NLP Tasks

This repository contains our Deep Learning course project report for ENSAI 3A (2025).

### Authors
- Babacar Gaye
- Imane Baladi

### Project Structure

```
├── [Report_Notebook].ipynb    # Main report with all questions
├── .gitignore                 # Git ignore file
└── README.md                  # This file
```

### Questions Covered

1. **Question 1: Flower Image Classification**
   - SimpleCNN (from scratch)
   - SimpleMLP (baseline)
   - ResNet18 (transfer learning)

2. **Question 2: Noun-Verb Classification**
   - GRU + GloVe (pretrained embeddings)
   - GRU + Trainable embeddings
   - LSTM + Trainable embeddings

3. **Question 3: Small Project**
   - [To be completed]

### Dataset Sources

- **Flowers**: [TensorFlow Flower Photos](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz) (Creative Commons BY 2.0)
- **Noun-Verb**: [Google Research Datasets](https://github.com/google-research-datasets/noun-verb)
- **GloVe**: [Stanford NLP GloVe](https://nlp.stanford.edu/projects/glove/)

### Requirements

- Python 3.8+
- PyTorch
- torchvision
- pyconll
- matplotlib
- numpy
- tqdm

### How to Run

1. Clone this repository
2. Install dependencies: `pip install torch torchvision pyconll matplotlib numpy tqdm`
3. Open the notebook and run all cells (data will be downloaded automatically)

### License

This project is for educational purposes (ENSAI Deep Learning Course 2025).
