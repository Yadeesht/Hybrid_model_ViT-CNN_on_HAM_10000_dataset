# Hybrid_model_ViT-CNN_on_HAM_10000_dataset

Project Title: Skin Lesion Classification using CNN + Vision Transformers (ViT)

About the Project
This project aims to develop an efficient skin lesion classification model using the HAM10000 dataset. Skin cancer detection is a challenging task due to the high variability in lesion appearance, including differences in color, texture, and shape. Early and accurate diagnosis can significantly improve treatment outcomes and patient survival rates.

To improve classification accuracy and generalization, the project explores three different model architectures:

ViT from Scratch: A Vision Transformer model trained from scratch on the HAM10000 dataset to learn patterns directly from the data.
Pretrained ViT: A Vision Transformer model pretrained on a large dataset and fine-tuned on the HAM10000 dataset to leverage existing knowledge and improve convergence.
CNN + ViT Hybrid: A hybrid model where a CNN extracts low-level spatial and texture-based features, which are then passed to a Vision Transformer for deeper contextual understanding and classification.
The models were evaluated based on accuracy, precision, recall, and F1-score to measure both overall performance and the model’s ability to handle class imbalance. The hybrid CNN + ViT model demonstrated improved robustness and accuracy, highlighting the benefits of combining convolutional feature extraction with the attention-based learning capability of transformers.

This project contributes to the field of medical image analysis by enhancing the accuracy and reliability of automated skin cancer diagnosis using state-of-the-art deep learning techniques. 🚀
