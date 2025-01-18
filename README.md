YOLOv8 Brain Tumor Detection


Dataset

This project utilizes the Medical Image Dataset: Brain Tumor Detection. The dataset includes labeled MRI scans categorized as tumor or non-tumor.
https://www.kaggle.com/datasets/pkdarabi/medical-image-dataset-brain-tumor-detection/data

To get started, download and organize the dataset into separate folders for training and validation with a clear distinction between classes.

How It Works

	1.	Data Preparation:
Images from the dataset are preprocessed w/ resizing and normalizing, and labeled according to their categories.
	2.	Model Training:
The YOLOv8 model is fine-tuned using the preprocessed dataset, adapting it specifically for brain tumor detection tasks.
	3.	Inference:
The trained model can analyze MRI scans and detect tumor regions, outputting annotated images.


Example Output

![alt text](https://github.com/[KrishayR]/[brain-tumor-detection]/blob/[branch]/image.jpg?raw=true)

Objectives

	•	Reliable Tumor Detection: Create a tool that detects brain tumors with high confidence.
	•	Accessible Workflow: Ensure ease of use for researchers and professionals.
	•	Support Healthcare Decisions: Provide timely insights for medical professionals.
