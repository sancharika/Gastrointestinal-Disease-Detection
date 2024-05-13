# Gastrointestinal Disease Detection with Multi-Model Approach

## Overview:
This project focuses on the development of a robust computer-aided detection system for gastrointestinal (GI) diseases utilizing a multi-model approach. Leveraging the Kvasir dataset, which contains annotated images of the GI tract, the system employs deep learning models such as DenseNet 121, VGG19, ResNet50, detectron2, and maskrcnn for accurate disease detection. Additionally, the RGB images are converted to HSV and YUV color spaces to enhance performance. Augmentation techniques are also applied to increase the diversity of the training data.

## Dataset Description:
The Kvasir dataset comprises images of the GI tract, meticulously annotated and verified by experienced endoscopists. It includes various classes representing anatomical landmarks, pathological findings, and endoscopic procedures. Anatomical landmarks encompass Z-line, pylorus, and cecum, while pathological findings include esophagitis, polyps, and ulcerative colitis. Furthermore, sets of images related to lesion removal procedures are provided. The dataset contains images of varying resolutions, organized into separate folders based on content. Some images feature a green picture-in-picture overlay depicting the endoscope's position and configuration within the bowel, aiding interpretation.

## Models Used:

1. DenseNet 121
2. VGG19

3. ResNet50
4. Detectron2

5. Mask R-CNN

## Approach:
The project adopts a multi-model approach to enhance disease detection accuracy within the GI tract. Each model is trained on the Kvasir dataset, leveraging its diverse classes and annotations. Additionally, RGB images are transformed into the HSV and YUV color spaces to exploit potential performance improvements. Augmentation techniques such as rotation, flipping, and scaling are applied to increase the diversity of the training data. By incorporating various deep learning architectures, color space conversions, and augmentation, the system aims to achieve superior performance in both single and multi-disease detection scenarios.

## Readme File Contents:

1. Introduction: Overview of the project, objectives, and dataset description.
2. Dataset Preparation: Details on the Kvasir dataset, including class distribution, annotation process, and folder organization.

3. Models Used: Description of the deep learning models employed, including DenseNet 121, VGG19, ResNet50, Detectron2, and Mask R-CNN.
4. Approach: Explanation of the multi-model approach, augmentation techniques, and the rationale behind incorporating color space conversion.

5. Implementation: Instructions on setting up the project environment, training the models, and evaluating performance metrics.
6. Results: Discussion of the results obtained, including accuracy rates and detection capabilities.

7. Conclusion: Summary of findings, limitations, and potential future enhancements.
8. References: Citations for datasets, models, and relevant literature.

## Conclusion:
The Multi-Model Approach for Gastrointestinal Disease Detection project showcases the effectiveness of utilizing diverse deep learning models, color space conversions, and augmentation techniques for accurate and efficient disease detection within the GI tract. Through meticulous dataset preparation, model training, and evaluation, the system aims to contribute to advancements in medical imaging analysis and improve healthcare outcomes.
