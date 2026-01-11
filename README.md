# Image-Enhancement-and-Edge-Detect-on-Methods-for-L-cense-Plate-Process-ng
A classical image processing project for "BASIC METHODS AND PRINCIPLES IN IMAGE PROCESSING" course. This project implements plate localization by benchmarking pipelines like LoG, Gaussian-Sobel, and Gaussian-Canny with geometric filtering and success rate analysis, strictly avoiding AI models.
# Project Overview
The main goal was to benchmark different filtering and edge detection combinations to achieve the highest accuracy in complex environments. The pipeline includes:

# Preprocessing: 
Grayscale conversion and noise reduction via Gaussian and Bilateral filters.

# Feature Extraction: 
Comparative analysis using LoG (Laplacian of Gaussian), Sobel, and Canny Edge Detection.

# Localization: 
Identifying candidates through Contour Analysis, Geometric Filtering (Aspect Ratio & Area), and Morphological Operations.

# Output: 
Precise masking and cropping of the detected plate region.

# Success Rate Analysis
Various pipelines like Gaussian-Canny and Sobel-Gaussian were tested to evaluate their performance against different backgrounds (e.g., textures, shadows, and cobblestones), ensuring a robust non-AI solution for plate localization.
