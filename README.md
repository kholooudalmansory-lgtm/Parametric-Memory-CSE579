# Parametric-Memory-CSE579

This repository contains the implementation files for the CSE579 final project.

## Project Overview

This project compares parametric memory methods and a retrieval-based baseline for question answering. The implemented approaches include LoRA, AdaLoRA, QLoRA, and a RAG-based baseline.

## Dataset

This project uses the SQuAD dataset for extractive question answering. The dataset consists of context passages, questions, and corresponding ground-truth answers.
The dataset is used for training, evaluation, and comparison between the implemented methods, including LoRA, AdaLoRA, QLoRA, and the RAG-based baseline.

## Code Files

- rag_squad.ipynb: Implements the retrieval-based baseline using RAG.
- mistral_7b_lora.ipynb: Implements LoRA fine-tuning for the Mistral-7B model.
- mistral_7b_ada_lora.ipynb: Implements AdaLoRA fine-tuning for the Mistral-7B model.
- mistral_7b_qlora.ipynb: Implements QLoRA fine-tuning for the Mistral-7B model.

## Evaluation

The models are evaluated using Exact Match, F1 Score, Substring Accuracy, latency, generalization, and forgetting.


## Notes

The notebooks were developed and tested in a Python environment.
