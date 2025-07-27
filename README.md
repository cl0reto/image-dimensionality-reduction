# Image Dimensionality Reduction

A Python project for converting RGB images to grayscale and binary formats. Uses luminance calculation for grayscale conversion and thresholding for binary conversion. Includes functions to save the processed images. Built with NumPy and PIL (Python Imaging Library).

## Features

- **Grayscale Conversion**: Uses `0.299*R + 0.587*G + 0.114*B` for accurate luminance.
- **Binary Thresholding**: Converts grayscale to binary with adjustable threshold (default: 128).
- **No Setup**: Runs directly in Colab — no `pip install` needed.

## How to Use in Colab

1. **Upload Images**:  
   - Add your image to Colab’s file system (e.g., `img/lenna-original.png`).
   - Update code according your file path.

3. **Run Conversion**:
```python
 from main import RGB2Gray, RGB2Binary

 # Convert to grayscale (saves to 'lenna-gray.png')
 RGB2Gray('img/lenna-original.png', 'img/lenna-gray.png')

 # Convert to binary with custom threshold (saves to 'lenna-binary.png')
 RGB2Binary('img/lenna-original.png', 'img/lenna-binary.png', threshold=150)
```

4. **Download Results**:
Right-click output files in Colab’s file explorer to download.

## Example Outputs

### Original

![Lenna original](https://github.com/user-attachments/assets/e2a4a95d-82da-4f38-9ee1-cfea388c769e)

### Grayscale

![Lenna gray](https://github.com/user-attachments/assets/8172b74d-01ff-47cd-95b8-d614e68a79ac)

### Binary

![Lenna binary](https://github.com/user-attachments/assets/9caf73d3-32da-4c08-bead-8c5eae99edef)

## Notes

- **Paths**: Update file paths to match your Colab environment.
- **Threshold**: Adjust `threshold` in `RGB2Binary()` for lighter/darker binary images.
