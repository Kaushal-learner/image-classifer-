# image-classifer-
Build a robust and generalizable image classifier using deep learning.  Improve performance using supervised contrastive learning.
🧠 Approach
Backbone: ResNet-18 architecture
Augmentations:
Custom data augmentations during training
TenCrop Test Time Augmentation (TTA) during inference for enhanced robustness
Loss Function: Combination of Supervised Contrastive Loss and CrossEntropy Loss
Training Strategy:
Per-epoch random stratified dataset splitting to maintain class balance
Both encoder and classifier trained using the full dataset
Training Framework: PyTorch
Platform: Google Colab GPU.
I was able to achieve 99.67 percent validation accuracy with the help of my model. 
