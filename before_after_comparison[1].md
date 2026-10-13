# LoRA Fine-Tuning: Before vs After Comparison

## Model and Training Configuration
- Base model: Qwen/Qwen2.5-0.5B-Instruct
- Fine-tuning method: LoRA with 4-bit model loading
- LoRA rank: 8
- Learning rate: 0.0002
- Epochs: 3
- Training examples: 108
- Evaluation examples: 12
- Final training loss: 0.69805
- Training runtime: 108.14 seconds

## Results

### Explain Python in simple words.

**Before fine-tuning:**


**After fine-tuning:**
Python is a programming language used for automation, data analysis, and application development.


### What is machine learning?

**Before fine-tuning:**


**After fine-tuning:**
Machine learning enables computers to learn patterns from data and make predictions.


### What is overfitting?

**Before fine-tuning:**


**After fine-tuning:**
Overfitting occurs when a model fits training data too closely and performs poorly on unseen examples.


### Explain a Python function.

**Before fine-tuning:**


**After fine-tuning:**
A Python function is a reusable block of code defined using the def keyword.

## Conclusion

The model was fine-tuned using LoRA on a small instructional dataset. The tested outputs after fine-tuning are concise and relevant to the four prompts. This is a qualitative comparison; four examples alone do not establish general performance improvement. A larger, diverse evaluation set is needed for a stronger conclusion.