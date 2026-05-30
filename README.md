# Multilingual Image Captioning using Transformer Architecture

A Transformer-based multimodal deep learning research project that generates image captions in **Tamil** and **Telugu** by combining computer vision feature extraction with natural language sequence generation.

---

## Table of Contents

- [Introduction](#introduction)
- [Research Summary](#research-summary)
- [Motivation](#motivation)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Related Works](#related-works)
- [Algorithmic Components](#algorithmic-components)
- [Methodology](#methodology)
- [Results](#results)
- [Future Works](#future-works)
- [References](#references)

## Introduction

This repository contains the research paper for automated image captioning in Tamil and Telugu using transformer-based models. The study documents how modern vision-language architectures can generate accurate, fluent captions for under-resourced Indian languages.

> Note: This repository does not include executable code. It contains only the research paper `Image Captioning Research Paper.pdf` and supporting visual assets in the `images/` folder.

## Research Summary

This research explores an end-to-end Transformer-based approach for multilingual image captioning. It covers dataset preparation, visual feature extraction, caption preprocessing, multimodal fusion, and evaluation. The paper presents this work in a clear, concise, and effective way, highlighting how attention-based models can improve caption generation for Tamil and Telugu.

## Motivation

The primary motivation is to expand image captioning beyond English and traditional CNN-LSTM models. Tamil and Telugu need native-language captioning systems that can handle linguistic complexity, cultural specificity, and low-resource constraints.

## Problem Statement

Traditional image captioning systems are often limited by:

- English-centric design
- CNN-LSTM architectures with weak long-range dependency modeling
- low-resource language challenges for Tamil and Telugu

This project addresses those issues by using a **Transformer-based encoder-decoder architecture** with multi-head attention to generate more context-aware captions in Indian languages.

## Dataset

The research paper is based on translated versions of standard image captioning datasets, adapted for Tamil and Telugu. Key dataset characteristics include:

- multiple captions per image in Tamil and Telugu
- localized wording to preserve natural language quality
- preprocessing for tokenization, padding, and model readiness

## Related Works

This study builds on prior research in:

- Transformer-based image captioning and multimodal modeling
- multilingual vision-language systems
- low-resource language adaptation and transfer learning

The paper compares these methods and explains why transformer-based models are strong candidates for Tamil and Telugu captioning.

## Algorithmic Components

The architecture combines image and text processing modules:

- Vision Encoder: extracts image features using a pretrained CNN backbone
- Caption Tokenizer: converts Tamil and Telugu captions into integer sequences
- Positional Encoding: preserves order and spatial structure for both modalities
- Transformer Encoder-Decoder: learns the mapping between visual features and text tokens
- Attention layers: allow the model to focus on image regions relevant to each generated word

## Methodology

The methodology includes:

- image preprocessing and normalization
- feature extraction using CNN backbones such as InceptionV3, ResNet50, or VGG16
- caption preprocessing with `<start>` and `<end>` tokens, tokenization, and padding
- projecting image features into the same embedding space as text features
- training a Transformer encoder-decoder model for multilingual caption generation
- evaluating captions using standard metrics like BLEU

### Architecture Illustration

The architecture diagram below shows the multimodal Transformer workflow, including the visual feature encoder, feature projection, and text decoder.

![Transformer Architecture](images/Figure1.jpg)

## Results

The paper reports that the Transformer-based approach improves caption quality in Tamil and Telugu when compared to earlier methods. The results section includes both quantitative evaluation and sample predictions.

- stronger caption relevance and fluency in Tamil and Telugu
- improved performance on low-resource dataset translations
- evidence that multimodal attention enhances visual-text alignment


- `images/Figure6.png` and `images/Figure14.jpg` show model results and sample caption predictions.
.





