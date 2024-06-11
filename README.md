# Underwater_Image_Enhancement
Overview
Underwater Image Enhancement aims to improve the visual quality of images taken underwater. Due to the absorption and scattering of light, underwater images often suffer from issues like color distortion, low contrast, and blur. This repository contains various techniques and algorithms designed to address these problems and produce clearer, more vibrant underwater images.

Features

Color Correction: Adjusts the color balance to correct the blue/green color cast typical in underwater images.
Contrast Enhancement: Increases the contrast to make objects in the image more distinguishable.
Dehazing: Reduces the haze effect caused by particles in the water.
Noise Reduction: Removes or reduces noise to improve image clarity.
Sharpness Enhancement: Enhances the sharpness of the image to highlight details.
Depth-Based Adjustment: Applies depth-aware techniques for more accurate enhancement.


Algorithms 
Histogram Equalization: Enhances contrast by stretching the intensity distribution.
White Balance Adjustment: Corrects color by normalizing the image based on white color references.
CLAHE (Contrast Limited Adaptive Histogram Equalization): Improves local contrast and is particularly effective in enhancing the visibility of edges.
Dark Channel Prior: Utilized for dehazing by estimating the transmission map.
Bilateral Filtering: Smoothens images while preserving edges.
Retinex Algorithms: Models the way human eyes perceive images to enhance details and dynamic range.

Usage
Prerequisites

Python 3.7+

OpenCV

NumPy

Matplotlib

Scikit-Image


Installation

Clone the repository:
sh
Copy code
git clone https://github.com/ria-kalra/underwater-image-enhancement.git
cd underwater-image-enhancement

Install the required packages:
sh
Copy code
pip install -r requirements.txt

Running the Enhancement
sh
Copy code
python enhance.py --input path_to_underwater_image --output path_to_save_enhanced_image

Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss potential improvements or new features.

License
This project is licensed under the MIT License.

