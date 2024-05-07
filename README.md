# Food Identification and Recipe Generation

Created two separate transfer learning architectures (ResNet-50 and EfficientNetB1) to identify food in images. The EfficientNetB1 architecture performed better, achieving an accuracy of 74.05% across 101 different foods. 

Visualized the accuracy, loss, top-5 accuracy, highest f1-score and precision of the top 5 classes, and top 5 predictions by the model on test images.

A customized recipe of the identified food is generated using Gemini.

## Dataset

I have used the [Food101 Dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) for model training.
