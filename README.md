This project is focused on building an efficient deep learning model to classify electronic waste (e-waste) images into various categories like Battery, Keyboard, Mobile, Mouse, PCB, Printer, and more. It utilizes transfer learning with EfficientNetV2B0 and is deployed via a Gradio web interface for real-time testing.


---

📌 Features

✅ E-Waste image classification using EfficientNetV2B0 (Transfer Learning)

✅ Dataset pre-processing with data augmentation

✅ Training/validation accuracy and loss visualization

✅ Model saving in .keras format

✅ Interactive Gradio interface to test your own e-waste images

✅ Output visualizations (sample predictions, class distributions, training graphs)

✅ Auto-overwriting and saving of plots/images on each run



---

🧠 Model Summary

Base model: EfficientNetV2B0

Architecture: Sequential with global average pooling, dropout, and dense layers

Optimizer: Adam

Loss function: Categorical Crossentropy

Accuracy: ~97–98% across training/validation/test sets (sample run)
