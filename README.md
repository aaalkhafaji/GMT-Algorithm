# GMT-Algorithm
Python implementation of the Galois-Morphological Transform for 2D images
# The Galois-Morphological Transform (GMT)

This repository contains the Python implementation of the Galois-Morphological Transform (GMT) applied to 2D digital images, as discussed in the paper:
**"The Galois-Morphological Transform: Algebraic and Spectral Symmetries in Morphological Dynamics."**

### Contents
* `gmt_vision.py`: A Python script leveraging NumPy and OpenCV to simulate the Galois-Fourier isomorphism, decomposing an image into its invariant mass orbit and structural texture orbits.
* `a4.jpg`: The sample image used for the transformation.

### How to Run
1. Ensure you have Python installed along with `numpy`, `opencv-python`, and `matplotlib`.
2. Run the script in the same directory as the image:
   `python gmt_vision.py`
