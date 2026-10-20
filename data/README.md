# Data

The datasets come from Kaggle and are **not** stored in this repo. Everything in this folder except this README is ignored by Git.

## Setup

You need a Kaggle account and an API token. Follow the [Kaggle API docs](https://github.com/Kaggle/kaggle-api) to create one and save it on your machine (for example `~/.kaggle/kaggle.json`). Never commit that file. It's your personal key.

## Download

Run these from the repo root.

### 01 · Rice type classification

```bash
uv run kaggle datasets download mssmartypants/rice-type-classification -p data/rice-type-classification --unzip
```

Source: [Rice type classification](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification) by mssmartypants

### 02 · Animal faces

```bash
uv run kaggle datasets download andrewmvd/animal-faces -p data/animal-faces --unzip
```

Source: [Animal Faces](https://www.kaggle.com/datasets/andrewmvd/animal-faces) by andrewmvd

### 03 · Bean leaf lesions

```bash
uv run kaggle datasets download marquis03/bean-leaf-lesions-classification -p data/bean-leaf-lesions-classification --unzip
```

Source: [Bean Leaf Lesions Classification](https://www.kaggle.com/datasets/marquis03/bean-leaf-lesions-classification) by marquis03

### 04 · Quran recitations (audio)

```bash
uv run kaggle datasets download mohammedalrajeh/quran-recitations-for-audio-classification -p data/quran-recitations-for-audio-classification --unzip
```

Source: [Quran recitations for audio classification](https://www.kaggle.com/datasets/mohammedalrajeh/quran-recitations-for-audio-classification) by mohammedalrajeh (about 2.3 GB)

### 05 · News headlines for sarcasm detection

```bash
uv run kaggle datasets download rmisra/news-headlines-dataset-for-sarcasm-detection -p data/news-headlines-dataset-for-sarcasm-detection --unzip
```

Source: [News Headlines Dataset For Sarcasm Detection](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection) by rmisra

The BERT model itself (`bert-base-uncased`, about 440 MB) is downloaded from Hugging Face the first time the notebook runs and is cached outside this repo.

## Expected layout

```text
data/
├── README.md
├── animal-faces/
│   └── afhq/
│       ├── train/   (cat, dog, wild)
│       └── val/     (cat, dog, wild)
├── bean-leaf-lesions-classification/
│   ├── train.csv, val.csv
│   ├── train/   (angular_leaf_spot, bean_rust, healthy)
│   └── val/     (angular_leaf_spot, bean_rust, healthy)
├── news-headlines-dataset-for-sarcasm-detection/
│   └── Sarcasm_Headlines_Dataset.json, Sarcasm_Headlines_Dataset_v2.json
├── quran-recitations-for-audio-classification/
│   ├── files_paths.csv
│   └── Dataset/Dataset/   (12 reciter folders with .wav files)
└── rice-type-classification/
    └── riceClassification.csv
```
