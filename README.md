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
  ![Input Image](results/1.png "Sample output")

Technologies
	•	Programming Language: Python
	•	Deep Learning Framework: TensorFlow/Keras
	•	Other Libraries: NumPy, Pandas, Matplotlib
	•	Tools: Jupyter Notebook

License

This project is licensed under the MIT License. See the LICENSE file for details.

