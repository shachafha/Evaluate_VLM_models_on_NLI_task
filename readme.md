# Evaluate_VLM_models_on_NLI_task

This repository contains resources and code for evaluating Visual Language Models (VLMs) on the abductive Natural Language Inference (NLI) task, focusing on visual reasoning. The goal is to assess how different VLM models perform in reasoning about image-based premises and hypotheses.

## Repository Structure

- **`results files/`**: Contains model evaluation results and accuracy metrics.
- **`analysis files/`**: Stores intermediate analysis data and logs.
- **`Poster.pdf`**: Final poster summarizing the project, task, models, and results.
- **Notebooks**:
  - `create_analysis_files.ipynb`: Prepares data for analysis.
  - `Midjourney prompt creator.ipynb`: Generates images prompts for the dataset creation.
  - `Inference.ipynb`: Performs inference using the VLMs.
  - `combine_images.ipynb`: Combines evert triple to one image.

## Dataset

The dataset contains 64 examples of images paired with textual premises and hypotheses. 
56 examples were selected from an existing dataset across various reasoning categories, with 8 additional handcrafted examples.

## Models Tested

The evaluation includes several VLM models, including 
HuggingFaceM4_idefics2-8b, 
google_paligemma-3b-mix-224, 
openbmb_MiniCPM-Llama3-V-2_5-int4, 
and microsoft-Florence-2-large -> microsoft-Phi-3-mini-4k.
