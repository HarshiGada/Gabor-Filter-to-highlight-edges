# Gabor-Filter-to-highlight-edges
Use Gabor filter to highlight edges

This experiment explores the use of Gabor filters for edge detection. Gabor filters are particularly useful for texture analysis and edge detection in specific orientations and frequencies.

### ✅ Task 1: Generate Gabor Filter with a Set of Parameters
- Create a Gabor filter using a fixed set of parameters.
- Visualize the filter to understand its shape and orientation.

### ✅ Task 2: Change Parameter Values and Observe the Effect
- Modify parameters like:
  - Wavelength (`lambda`)
  - Orientation (`theta`)
  - Standard deviation (`sigma`)
  - Aspect ratio (`gamma`)
  - Phase offset (`psi`)
- Observe and visualize how the filter shape and its response to an image change with each parameter.

### ✅ Task 3: Apply Gabor Filter to Extract Hidden Image
- Use the Gabor filter to process the provided image.
- Extract the "hidden" image pattern by choosing appropriate filter parameters.

### ✅ Task 4: Apply a Set of Filters to Highlight Edges in Different Directions
- Apply a bank of Gabor filters with different orientations.
- Combine the results to highlight edges in multiple directions.

---

## 🛠️ Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `matplotlib`
  - `opencv-python` (`cv2`)
  - `scikit-image` (optional, for utility functions)

---
