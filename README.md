# FFB (Fresh Fruit Bunches) Classification with ResNet50 & Knowledge Distillation

This project focuses on the fine-grained classification of **Fresh Fruit Bunches (FFB)** using deep convolutional neural networks. A ResNet50 backbone was used as the base model to establish performance benchmarks. Further experiments were conducted with larger models and knowledge distillation techniques to explore the trade-off between model size, accuracy, and memory efficiency — with a goal toward real-world deployment on resource-constrained systems.

---

## Project Highlights

- **Dataset**: A curated dataset of oil palm Fresh Fruit Bunch images labeled by ripeness or class.
- **Model**: ResNet50 used as the baseline classifier.
- **Model Scaling**: Evaluation of larger models with higher memory footprints to compare classification performance.
- **Knowledge Distillation**: Implementation of various teacher-student training approaches to compress large models into efficient versions.
- **Performance Metrics**: Accuracy, F1-score, and confusion matrices were used to assess and visualize model performance.
- **Visualization**: Included tools for inspecting misclassifications and model confidence.

