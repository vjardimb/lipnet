# LipNet on Tensorflow

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

LipNet is an end-to-end sentence-level lipreading model that decodes text from the movement of a speaker's mouth. This repository contains our implementation of LipNet, designed to provide state-of-the-art lipreading capabilities.

## Introduction

Lipreading is the art of decoding spoken language solely from observing the movements of the speaker's lips. Traditional methods separated this problem into two stages: feature engineering and prediction. More recently, deep learning has enabled end-to-end trainable lipreading models. However, existing end-to-end models have primarily focused on word classification, leaving sentence-level sequence prediction largely unexplored. LipNet, introduced in this repository, aims to bridge this gap by enabling end-to-end sentence-level lipreading, emphasizing the importance of capturing temporal context for improved lipreading performance.

## Features

- End-to-End Lipreading: LipNet enables end-to-end lipreading, mapping variable-length video sequences to text.
- Spatiotemporal Convolutions: The model uses spatiotemporal convolutions to capture both spatial and temporal features.
- Recurrent Networks: LipNet incorporates recurrent networks to model temporal dependencies.
- Connectionist Temporal Classification: Training with the CTC loss enables sentence-level sequence prediction.
- Superior Accuracy: LipNet achieves state-of-the-art accuracy in sentence-level lipreading, outperforming previous word-level methods.


