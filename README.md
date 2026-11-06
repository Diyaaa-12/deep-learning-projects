# Deep Learning Projects

Deep-learning notebooks covering CNNs for vision, RNNs/LSTMs/GRUs for text, and generative and graph models. They start with backpropagation from scratch and end with VAEs, GANs and GCNs. Built with **TensorFlow/Keras** and **PyTorch**.

## Case studies

| Project | Notebook | Approach | Result |
|---|---|---|---|
| **Handwritten digit recognition** | [`digit_recoginition_case_study_1…`](digit_recoginition_case_study_1_202401100300108.ipynb) | CNN (Conv2D + BatchNorm + Dropout) with data augmentation | **99.1%** validation accuracy |
| **CIFAR-10 image classification** | [`cifar10-case-study-2…`](cifar10-case-study-2-202401100300108.ipynb) | CNN with BatchNorm + Dropout on 10 object classes | **73.5%** test accuracy |
| **Brain tumor detection (MRI)** | [`Tumor_detection_case_study_3…`](Tumor_detection_case_study_3_202401100300108.ipynb) | Binary CNN classifier with `ImageDataGenerator` preprocessing | **~96%** test accuracy |

## Labs

| # | Topic | Notebook |
|---|---|---|
| 1 | Deep-learning libraries: TensorFlow/Keras vs PyTorch, a first neural network in each | [`DL_LAB_1`](202401100300108_DL_LAB_1.ipynb) |
| 2 | A 2-layer neural network with backpropagation written from scratch in NumPy | [`DL_LAB_2`](Diya_DL_LAB_2.ipynb) |
| 3 | CNNs on CIFAR-10 | [`dl-lab-3`](202401100300108-dl-lab-3.ipynb) |
| 4 | Sequence models for tweet sentiment: **SimpleRNN vs LSTM vs GRU** (LSTM +4.5 pts over RNN) | [`dl-lab-4`](202401100300108-dl-lab-4.ipynb), [`diya-lab-4`](202401100300108-diya-lab-4.ipynb) |
| 5 | LSTM sentiment classifier on IMDB reviews, **85.6%** test accuracy | [`DL_lab_5`](202401100300108_DL_lab_5.ipynb) |
| 6–7 | Text cleaning, TF-IDF (1–2-grams) and a LinearSVC baseline for tweet sentiment, with confusion matrix and top-feature analysis | [`DL_lab_6_7`](202401100300108_DL_lab_6_7.ipynb) |
| 8 | Generative and graph models: **VAE** with latent-space visualisation, **GAN** for image synthesis, **GCN** on the Cora citation graph (78% test accuracy) | [`DL_lab_8`](202401100300108_DL_lab_8.ipynb) |

## Run

Each notebook runs on Kaggle, Colab or a local Jupyter install:

```bash
pip install tensorflow torch torchvision torch_geometric scikit-learn pandas matplotlib seaborn
```

Datasets: MNIST-style digits, CIFAR-10 (built into Keras), Brain MRI, IMDB 50K reviews, and Twitter airline sentiment (Kaggle).

## Stack

Python · TensorFlow / Keras · PyTorch · PyTorch Geometric · scikit-learn · NumPy · pandas · matplotlib
