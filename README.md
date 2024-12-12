NL-Means Image Denoising

This project implements a Non-Local Means (NL-Means) algorithm in MATLAB to denoise grayscale images by reducing Gaussian noise while preserving fine details.

Features

Implements NL-Means filter for grayscale image denoising.

Utilizes Gaussian kernel for weighted similarity computation.

Handles synthetic and real-world noisy images.

How It Works

Image Input: The algorithm accepts a grayscale image or converts an RGB image to grayscale.

Noise Addition: Gaussian noise is added to simulate a noisy environment for testing.

Gaussian Kernel: A Gaussian kernel is created to compute weighted similarity between pixel neighborhoods.

Denoising Process: Each pixel is updated based on a weighted average of similar pixels within a defined neighborhood.

Output: The denoised image is displayed alongside the noisy input image.

Usage

Clone this repository.

Place your test image (e.g., test.png) in the working directory.

Run the MATLAB script nl_means_denoising.m.

matlab -r nl_means_denoising

Requirements

MATLAB R2021a or later

Files

nl_means_denoising.m: MATLAB script implementing the NL-Means filter.

test.png: Example input image (place your image here).

Results

The denoised image shows significant noise reduction while maintaining sharp edges and fine details. Below is an example comparison:

Noisy Image

Denoised Image





Future Work

Extend to color image denoising.

Optimize computational efficiency for larger images.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

MATLAB documentation for image processing techniques.

Inspiration from various academic papers on NL-Means filtering.

