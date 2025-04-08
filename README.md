#  Comical Image Captioning

This notebook was developed and executed on **Kaggle** using the **GPT T4x2 Accelerator**, which provides dual NVIDIA T4 GPUs for faster model training and inference.

## Overview

This notebook demonstrates:
- Image caption generating through finetuning BLIP base model on NY dataset.
- Fine-tuned on 100 datapoints only.

## Hardware Used

- **Platform**: Kaggle Kernels
- **Accelerator**: GPT T4x2 (Dual NVIDIA T4 GPUs)
- **RAM**: 52 GB
- **GPU Memory**: ~32 GB (2 x 16 GB)

## Results

BertScored gave 0.83 f1-score to the generated model. 


## Scope of improvements

- An obvious improvement is fine-tuning the model on larger dataset. 
- Employing other features as context in fine-tuning. 
- Can try more advanced model than BLIP, especially those curated on comical, black and white images. 
- Can come up with comical centric evaluation metric to evaluate the model better. 