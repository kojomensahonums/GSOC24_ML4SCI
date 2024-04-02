# GSOC24_ML4SCI

This repository contains submissions to ML4SCI Organisation for Google Summer of Code 2024.

### Description of Notebooks 
```
1. DeepLense_Common_Test.ipynb contains solution for Common Test I which involved classifying images into 3 classes; no substructure, subhalo substructure, and vortex substructure. A VGG-16 model was built and trained with the provided training data.
2. Lens_finding_Baseline.ipynb contains solution for Specific Test II which involved classifying images as containing Strong Gravitational Lenses or not. The image dataset of Infrared filter was used for training. A VGG-16 model was built and trained upon the easy folder dataset.
3. Image_classification_with_no_labels_Roboflow.ipynb contains solution for a semi-supervised approach of classifying images as lenses but without using labelled data. YOLOv8 model was used here for training and prediction.
```

### Description of Excel Sheet
```
improved_results.csv is an additional submission file within which predictions of the YOLOv8 model was compared against reference predictions provided in the hard folder dataset.
