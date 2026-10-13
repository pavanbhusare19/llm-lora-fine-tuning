# LoRA Fine-Tuning Project

## Overview
Fine-tuning Qwen2.5-0.5B-Instruct using LoRA and 4-bit model loading.

## Configuration
- Base model: Qwen/Qwen2.5-0.5B-Instruct
- Method: LoRA / PEFT
- LoRA rank: 8
- Learning rate: 0.0002
- Epochs: 3
- Training examples: 108
- Evaluation examples: 12
- Final training loss: 0.69805
- Training runtime: 108.14 seconds

## Files
- `train.jsonl`: Original training data
- `train_chat.jsonl`: Chat-formatted dataset
- `before_results.json`: Baseline outputs
- `after_results.json`: Fine-tuned outputs
- `before_after_comparison.md`: Prompt comparison
- `training_loss_curve.png`: Training loss visualization
- `training_logs.json`: Trainer logs

## Evaluation
Four prompts were compared before and after fine-tuning. The comparison is qualitative and does not establish general performance improvement. The dataset is small and should be reviewed for diversity before drawing broader conclusions.

## Reproducibility
The training notebook and environment setup should also be included in the repository.
