### Class-Incremental Learning for Skin Cancer Detection

This project focuses on class-incremental learning for multi-class skin lesion classification using dermoscopic images from the ISIC dataset.

Three continual learning techniques — Learning without Forgetting (LwF), Dynamic Expandable Representation (DER), and Dark Experience Replay++ (DER++) — are evaluated using Vision Transformer (ViT), DenseNet121, and ConvNeXt architectures.

The study aims to reduce catastrophic forgetting while enabling models to learn new skin lesion classes sequentially.

**Best Result:** DER++ with Vision Transformer achieved 83.90% task-aware accuracy.

#### Repository Structure

- `DER/` – Dynamic Expandable Representation
- `DER++/` – Dark Experience Replay++
- `LWF/` – Learning without Forgetting
