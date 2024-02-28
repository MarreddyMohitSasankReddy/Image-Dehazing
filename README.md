# Image Dehazing with DCP Morphology and CAP HLP

## Overview
This study explores the effectiveness of two dehazing methods—DCP Morphology and CAP HLP—alongside the integration of Contrast Limited Adaptive Histogram Equalization (CLAHE) for image enhancement. DCP Morphology utilizes mathematical morphology for haze reduction, while CAP HLP employs haze-line and colour attenuation priors. The addition of CLAHE aims to further improve local contrast. Metric analysis, including PSNR (Peak Signal-to-Noise Ratio), SSIM (Structural Similarity Index), and VIF (Visual Information Fidelity), is conducted to quantitatively assess the performance of these techniques. Results from diverse hazy images provide insights into the strengths and limitations of each method, offering practical guidance for image dehazing in various applications.

## Features
- Evaluation of DCP Morphology and CAP HLP dehazing methods
- Integration of Contrast Limited Adaptive Histogram Equalization (CLAHE) for image enhancement
- Quantitative analysis using PSNR, SSIM, and VIF metrics
- Comparison of results across diverse hazy images
- Practical insights for image dehazing in various applications

## Dependencies
- Python 3.x
- OpenCV
- NumPy
- SciPy
- Matplotlib

## Usage
1. Clone the repository:

```bash
git clone https://github.com/MarreddyMohitSasankReddy/Image-Dehazing.git
