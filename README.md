# IMDB Transformer Text Classifier

Transformer-based sentiment classifier trained on the IMDB movie review dataset using **PyTorch** and **TorchText**.

- Model:
    - Custom TransformerEncoder

    - Positional Encoding

    - Token-level self-attention visualisation

    - Accuracy tracking + early stopping

    - Inference for custom text input

## Features

- Loads IMDB dataset (torchtext or CSV export)

- Builds vocabulary (20k most frequent tokens)

- TransformerEncoder with:

    - Multi-Head Self-Attention

    - Positional Encoding

    - LayerNorm + Dropout

- Training loop with:

    - Adam optimizer

    - CrossEntropyLoss

    - Early stopping

    - Checkpoint saving

- Visualization:

    - Training curves

    - Attention heatmaps

## Output Example

```
text_example = "The movie was absolutely fantastic! I loved every part of it."
```

**Predicted label**: pos
**Confidence**: 0.9967