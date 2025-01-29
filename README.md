HybridUNet is a deep learning model designed for accurate and efficient 3D medical image segmentation using the BraTS2020 dataset. It combines EfficientNet for robust 2D spatial feature extraction and ConvLSTM for capturing temporal (volumetric) dependencies, making it well-suited for brain tumor segmentation.

Key Features:
✅ Hybrid Architecture: Integrates EfficientNet (2D) and ConvLSTM (3D) for superior feature learning.
✅ Optimized for Performance: Uses a lightweight yet powerful encoder to reduce computational overhead.
✅ Handles Class Imbalance: Employs a combined Dice + Focal loss function to improve tumor region segmentation.
✅ Robust Preprocessing: Normalization, resizing, and one-hot encoding for optimized model input.
✅ IoU-Based Evaluation: Achieves ~0.78 IoU for tumor regions, ensuring accurate segmentation.
✅ PyTorch Implementation: Efficiently trained on NVIDIA GPUs with memory-aware optimizations.

Future Enhancements:
🔹 Implement gradient checkpointing and mixed precision training to optimize memory usage.
🔹 Use high-memory GPUs for improved model training.
🔹 Incorporate advanced data augmentation for better generalization.

This project addresses the challenges of 3D medical segmentation, including computational constraints, imbalanced data, and complex tumor structures, making it a valuable tool for medical AI research.

🚀 Check out the implementation and contribute!
