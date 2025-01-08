Polyp Segmentation Using U-Net

Overview

This project utilizes the U-Net architecture for segmenting polyps from medical images. Accurate polyp segmentation is crucial for early detection and diagnosis of diseases like colorectal cancer. The model was trained and evaluated on a dataset of medical images and corresponding masks.

Dataset:

CVC-ClinicDB Dataset: https://polyp.grand-challenge.org/CVCClinicDB/
Libraries/Modules:

Libraries/Modules
	•	Image Processing: Pillow (PIL)
	•	Numerical Computing: NumPy
	•	Deep Learning: TensorFlow/Keras
	•	Data Handling: pandas, glob
	•	Data Splitting: scikit-learn (train_test_split)
	•	Progress Monitoring: tqdm
	•	Visualization: Matplotlib




Results
	•	Performance Metrics:
	•	Dice Coefficient: 92%
	•	IoU: 89%
	•	Sample Outputs:
	•	Input Image:


 - **Original Image, Ground Truth Mask, Predicted Mask:**:
  ![Output](results/1.png "Sample output")

Technologies
	•	Programming Language: Python
	•	Deep Learning Framework: TensorFlow/Keras
	•	Other Libraries: NumPy, Pandas, Matplotlib
	•	Tools: Jupyter Notebook

 
Copyright
	•	Images from the folder ‘Original’ are the property of Hospital Clinic, Barcelona, Spain.
	•	Images from the folder ‘Ground Truth’ are the property of Computer Vision Center, Barcelona, Spain.
Referencing

If using this dataset or referencing this work, please cite:

	Bernal, J., Sánchez, F. J., Fernández-Esparrach, G., Gil, D., Rodríguez, C., & Vilariño, F. (2015). WM-DOVA maps for accurate polyp highlighting in colonoscopy: Validation vs. saliency maps from physicians. Computerized Medical Imaging and Graphics, 43, 99-111.

