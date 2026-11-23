
# Lab Sheet 3 – Developing a Tiny Transformer Language Model

## Objective
To develop, train, and evaluate a small Transformer-based language model using the TinyStories dataset.

## Technologies Used
- Python
- PyTorch
- Google Colab (GPU)
- Hugging Face Datasets
- NumPy
- Matplotlib

## Dataset
- Dataset: TinyStories
- Stories used: 1,000
- Tokenization: Character-level
- Vocabulary size: 75
- Training split: 90%
- Validation split: 10%

## Model Architecture
- Transformer layers: 2
- Attention heads: 4
- Embedding dimension: 64
- Sequence length: 64
- Total parameters: 113,867

## Training
- Optimizer: AdamW
- Learning rate: 0.001
- Training steps: 500
- Batch size: 32

## Results
- Training loss: 2.0013
- Validation loss: 1.9802
- Perplexity: 7.2441

Both training and validation losses decreased during training, indicating that the model learned character-level patterns.

## Text Generation
The trained model generated text using the prompt "Once upon a time".

The generated text contained recognizable English patterns but was not fully coherent due to the small model size and limited training.

## Temperature Experiment
Three sampling temperatures were tested:
- 0.5: More repetitive output
- 0.8: More varied text
- 1.2: More random and less coherent output

## Evidence
Screenshots of dataset exploration, training, evaluation, and text generation are available in the screenshots folder.

## Files
- notebooks/: Google Colab notebook
- models/: Saved Transformer model
- screenshots/: Practical evidence

## Conclusion
A small Transformer language model was successfully implemented, trained, and evaluated using the TinyStories dataset. The experiment demonstrated next-character prediction, self-attention, model evaluation, and temperature-based text generation.
