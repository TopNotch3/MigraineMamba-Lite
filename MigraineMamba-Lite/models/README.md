# Models Directory

This directory contains trained machine learning models.

## Model Files (Will be created during development)
- mamba_final.pkl - Final trained Mamba model
- ssl_final.pkl - Self-supervised learning model
- baseline_models.pkl - Baseline comparison models

## Model Information
- *Architecture*: Bidirectional Mamba with SSL pre-training
- *Input*: Temporal trigger sequences
- *Output*: 7-day migraine risk prediction
- *Performance*: [To be filled after training]

## Usage
Models are loaded by the Flask API for making predictions.
See ../src/api/ml_service.py for implementation details.
