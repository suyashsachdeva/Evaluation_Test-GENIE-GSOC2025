# Evaluation_Test-GENIE-GSOC2025: Deep Graph Anomaly Detection with Contrastive Learning for New Physics Searches

This project, under the GENIE Collaboration for Google Summer of Code 2025, aims to develop a graph-based anomaly detection framework using contrastive learning techniques to identify novel physics signals in high-energy particle collision data.

## 🔬 Problem Statement

Current new physics searches often rely on model-specific simulations, which may miss unforeseen or anomalous events that don’t conform to expected signatures. To overcome this, we propose a model-independent approach using graph neural networks (GNNs) and contrastive learning to detect statistically anomalous patterns in subatomic collision events.

## 🚀 Project Goals

- Construct graph representations of detector data (ECAL, HCAL, and Track images) from LHC experiments.
- Apply contrastive learning to learn discriminative latent representations that separate nominal and anomalous events.
- Design an anomaly scoring method to flag rare or unexpected physics signatures.
- Evaluate performance using synthetic benchmarks and real experimental data.

## 🎯 Deliverables

- Preprocessing pipeline to convert 3-channel calorimeter/track data into spatial-temporal graphs.
- A contrastive learning framework for training deep GNNs on event data.
- Anomaly detection module that ranks events by deviation from learned normal behavior.
- Validation on simulated and experimental LHC datasets.
- Documentation, visualization tools, and reproducible training scripts.

This framework will help facilitate data-driven discovery in high-energy physics by identifying subtle deviations in detector signals that could indicate new particles or interactions.

