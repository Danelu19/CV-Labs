# CV-Labs
¡Bienvenido a CV Labs, para proyectos relacionados con la visión por computadora (CV)!

Áreas de Enfoque en:

- Transformers

- Transfer Learning

# CV - Computer Vision Transformer (ViT) - Overview and Implementation

This Python script explores the Vision Transformer (ViT) architecture, focusing on key components such as patching, linear projections, positional embeddings, self-attention mechanism, dot product, normalization (Softmax function), masked multi-head attention, and multi-head attention. Additionally, it provides an illustration of the detailed pipeline and how attention works in ViT.

## Installation

```bash
pip install timm
```

## Components Explored

1. **Patching:** The input image is split into patches using a learnable 2D convolution.
2. **Linear Projections:** A fully connected layer expands the dimension of the patch embeddings.
3. **Positional Embeddings:** Learnable position embeddings are added to the patch embeddings.
4. **Transformer Encoder:** The patch embeddings go through a series of transformer encoders.
5. **Attention Mechanism:** Visualization of attention matrices and how attention works in ViT.
6. **MLP (Classification) Head:** The final classification result is obtained from the transformer's output.

## Important Notes

- Make sure to install the required packages, especially `timm`.
- The script includes visualizations to aid in understanding the ViT components.
- Demo images are fetched from GitHub; ensure their availability for successful execution.
