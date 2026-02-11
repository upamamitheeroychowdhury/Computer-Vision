# Homework 1 — Introduction to Image Processing Using Python

This repository contains my solutions for **Homework 1: An Introduction to Image Processing Using Python** based on the AIML GitHub tutorials.

All problems were implemented using Python and Jupyter Notebook with NumPy, Matplotlib, and supporting utilities from the AIML tutorials.

---

## 📂 Repository Contents

- `HW_1.ipynb` — Main Jupyter notebook with all solutions
- Generated images — Saved outputs for each problem
- GIF / video — Output for Problem 6
- PDF — Exported notebook (for submission)

---

# Problem 1 — Basic Image Representations

Created using the interactive image editor:

- Binary image
- Grayscale image
- Color image

Screenshots and explanations are included in the notebook.

---

# Problem 2 — Contrast of Image Patches

Implemented grayscale patch examples:

- Minimum non-zero contrast example
- Maximum contrast example
- Constant patches on zero background (5, 10, 100, 200, 250)
- Log transform with different C values
- Side-by-side comparisons
- Visibility ranking table with justification

Discussion included on perceptual visibility vs mathematical contrast.

---

# Problem 3 — Images Through Activation Functions

Constructed patch images and demonstrated:

- ReLU with bias removing low-intensity patch
- Sigmoid with bias suppressing low-intensity patch

Visual results and explanations included.

---

# Problem 4 — Max Pooling and Downsampling

Covered grayscale morphology concepts:

- Dilation = max pooling (stride 1)
- Verified with Python experiments
- Rolling-ball analogy sketches
- Hole filling using larger kernels
- Derived minimum kernel size formula
- Downsampling hole removal sketch
- Showed relation between max-pooling on −I and erosion
- Implemented erosion using max-pooling

Both math derivations and code outputs included.

---

# Problem 5 — Image Segmentation Using Histograms

Histogram-based thresholding used to segment:

- Bear
- Yellow-like skin
- Minion clothes

For each case included:

- Histogram screenshot
- Input image
- Binary mask
- Segmented output

---

# Problem 6 — Video Creation

Created a NumPy-based animation with:

- 20 frames
- Two moving objects
- Sinusoidal motion
- Saved as GIF and video

Notebook and output video included.

---

## ▶️ How to Run

Open the notebook:

