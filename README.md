# Brain-Tumor-Classification-with-ConvNeXt-Variants

This repository contains the implementation of a deep learning project for classifying brain tumors using various ConvNeXt models. The project explores the performance of different ConvNeXt variants (e.g., Tiny, Small, Base, and Large) on a brain tumor dataset.



Brain tumor classification is a crucial task in medical imaging. This project leverages ConvNeXt, a family of convolutional neural network models inspired by modern transformer architectures, to classify brain tumors effectively. The work evaluates the strengths and weaknesses of different ConvNeXt variants on the dataset.


- Implementation of ConvNeXt variants: Tiny, Small, Base, and Large.
- Preprocessing pipeline for medical imaging datasets.
- Visualization of training metrics (accuracy and loss).
- Comparative performance analysis of ConvNeXt models.

Dataset
The dataset used for this project consists of brain MRI scans labeled for tumor classification. 

 Prerequisites
- Python 3.8 or above
- PyTorch 1.13 or above
- CUDA (optional for GPU support)

Results
The project achieved the following results on the validation set:
- ConvNeXt-Tiny: Train Acc: 87.55%, Test Acc: 80.70%
- ConvNeXt-Small: Train Acc: 44.19%, Test Acc: 43.33%
- ConvNeXt-Base:Train Acc: 97.27%, Test Acc: 94.97%
- ConvNeXt-Large:Train Acc: 86.80%, Test Acc: 83.07%



