---
title: "PII Data Detection"
date: 2024-01-15
description: "Kaggle PII Data Detection — synthetic data generation, DeBERTa NER, ONNX ensemble"
tags: ["kaggle", "nlp", "ner", "deberta", "onnx"]
---

## Overview

Detecting personally identifiable information (PII) in student essays using named entity recognition. The challenge required identifying and classifying PII tokens across thousands of documents with high precision and recall.

## Approach

- **Synthetic data generation** to augment limited training data with realistic PII patterns
- **DeBERTa-based NER models** fine-tuned for token-level PII classification
- **ONNX optimization** for inference speed without sacrificing accuracy
- **Ensemble strategy** combining multiple model checkpoints

## Result

121/2048 🥉

- **Public leaderboard:** 0.970
- **Private leaderboard:** 0.956

## Links

- [GitHub Repository](https://github.com/Galliard7/pii-data-detection)
