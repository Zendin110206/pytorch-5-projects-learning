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

## Expected layout

```text
data/
├── README.md
└── rice-type-classification/
    └── riceClassification.csv
```
