# Kidney-Stone-Recognition-using-machine-learning

## Overview
This project focuses on detecting kidney stones using image processing and machine learning techniques. The implementation involves preprocessing ultrasound images, applying various filtering techniques, and ultimately detecting the presence of kidney stones.

## Features
- **Image Preprocessing**: Enhancing image quality using filters.
- **Thresholding & Segmentation**: Applying Otsu's thresholding for better segmentation.
- **Noise Removal**: Utilizing Gaussian and Median filters.
- **Stone Detection**: Identifying and marking kidney stones in ultrasound images.

## Dataset
The project uses ultrasound images of kidneys for training and testing. The preprocessing pipeline includes converting images to grayscale, thresholding, noise removal, and filtering.

## Workflow
1. **Input Image**: Load the ultrasound image.
2. **Preprocessing**: Apply grayscale conversion and noise reduction.
3. **Thresholding**: Use Otsu’s method for segmentation.
4. **Filling Operation**: Enhance the detected regions.
5. **Final Preprocessing**: Refine the image.
6. **Filtering**: Apply Gaussian and Median filters for better feature extraction.
7. **Stone Detection**: Identify and highlight kidney stones.

## Dependencies
Ensure you have the following libraries installed:
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Scikit-image

Install dependencies using:
```bash
pip install opencv-python numpy matplotlib scikit-image
```

## Usage
Run the main script to process an ultrasound image:
```bash
python kidney_stone_detection.py --image input_image.jpg
```

## Results
### Preprocessing Steps
![Preprocessing Steps](https://github.com/user-attachments/assets/cd849989-535b-4864-a5c3-a7631210c37a)

### Filtering Techniques
![Filtering Techniques](https://github.com/user-attachments/assets/13538ae4-7348-4b57-aa33-d91a6af4e020)


### Final Detection
![Final Detection](https://github.com/user-attachments/assets/de9e859f-71de-44b6-96f4-d66ad6144390)


- The first image shows the different stages of preprocessing.
- The second image applies Gaussian and Median filters.
- The third image (final_detection.jpg) detects kidney stones.

## Contribution
Feel free to contribute by improving detection accuracy, optimizing preprocessing techniques, or experimenting with deep learning models.

## License
This project is licensed under the MIT License.
