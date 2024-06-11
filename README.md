# Underwater_Image_Enhancement

Underwater Image Enhancement aims to improve the visual quality of images taken underwater. Due to the absorption and scattering of light, underwater images often suffer from issues like color distortion, low contrast, and blur. This repository contains various techniques and algorithms designed to address these problems and produce clearer, more vibrant underwater images.

<b>Features</b>

<u>Color Correction:</u> Adjusts the color balance to correct the blue/green color cast typical in underwater images.

<u>Contrast Enhancement:</u> Increases the contrast to make objects in the image more distinguishable.

<u>Dehazing:</u> Reduces the haze effect caused by particles in the water.

<u>Noise Reduction:</u> Removes or reduces noise to improve image clarity.

<u>Sharpness Enhancement:</u> Enhances the sharpness of the image to highlight details.

<u>Depth-Based Adjustment:</u> Applies depth-aware techniques for more accurate enhancement.


<b>Algorithms</b> 

<u>Histogram Equalization:</u> Enhances contrast by stretching the intensity distribution.

<u>White Balance Adjustment:</u> Corrects color by normalizing the image based on white color references.

<u>CLAHE (Contrast Limited Adaptive Histogram Equalization):</u> Improves local contrast and is particularly effective in enhancing the visibility of edges.

<u>Dark Channel Prior:</u> Utilized for dehazing by estimating the transmission map.

<u>Bilateral Filtering:</u> Smoothens images while preserving edges.

<u>Retinex Algorithms:</u> Models the way human eyes perceive images to enhance details and dynamic range.

<u>Autoencoders:</u> For more enahcnement latest deep learning technique.

<u>SRCNN:</u> Super Resolution Convolutional Neural Network.


<b>Usage
Prerequisites</b>

Python 3.7+

OpenCV

NumPy

Matplotlib

Scikit-Image




<b>Clone the repository:</b>

git clone https://github.com/ria-kalra/underwater-image-enhancement.git


<b>Install the required packages:</b>

pip install -r requirements.txt

<b>Running the Enhancement</b>

python enhance.py 

--input path_to_underwater_image 
--output path_to_save_enhanced_image


<b>Contributions</b> are welcome! Please submit a pull request or open an issue to discuss potential improvements or new features.


This project is licensed under the <b>MIT License</b>.

