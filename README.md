# cse428_ImageProcessingProject_Segmentation-Classification_Unet_V1

For this project, I implemented both **U-Net** and **Attention U-Net** architectures for **image segmentation and classification** using **PyTorch**.

🔍 What I worked on:
• Implemented **Base U-Net** for semantic image segmentation
• Upgraded the architecture to **Attention U-Net** for improved feature focus and segmentation performance
• Added a **classification head** to the encoder output for simultaneous classification and segmentation
• Worked with **NumPy**, **PyTorch**, and deep learning pipelines for training and evaluation

📊 Metrics & Evaluations Used:
• Mean Intersection over Union (**mIoU**)
• Dice Coefficient
• Pixel Accuracy
• Classification Accuracy
• Precision
• Recall
• F1 Score
• Loss curve analysis across training and validation phases

⚙️ Techniques & Concepts Used:
• Encoder-decoder architecture
• Attention mechanisms
• Image augmentation
• Binary segmentation masking
• Multi-task learning (segmentation + classification)
• Optimizers and hyperparameter tuning
• Epoch-wise performance tracking

Currently, the models were trained for only **10 epochs**, so this is still a work in progress. Over the next few days, I’ll be moving the training pipeline to **Kaggle GPU** and increasing training to **20+ epochs** to further improve segmentation accuracy and overall model performance.

This project gave me deeper hands-on experience with computer vision, deep learning architectures, and practical model evaluation.

