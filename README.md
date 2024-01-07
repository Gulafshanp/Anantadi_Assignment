# Image Object Extraction using Thresholding

This Python script demonstrates object extraction from an image using thresholding techniques in the OpenCV library. It allows users to load an image, perform thresholding to create a binary mask, and extract a specific object from the image based on the generated mask.

## Overview
The script provides functionalities to load an image, convert it to grayscale, create a binary mask through thresholding, and extract the object of interest from the image. It displays both the original image and the extracted object using Matplotlib for visualization.

## Features
- Load an image and convert it to grayscale.
- Apply thresholding to create a binary mask for object extraction.
- Extract the object from the original image based on the generated mask.
- Visualize the original image and the extracted object side by side.

## Installation
To use this script, ensure you have Python installed. Install the required libraries using pip:

```bash
pip install opencv-python matplotlib
```
## Usage
- Replace the placeholder `image` variable with the path to your desired image file.
- Run the Python script using any Python IDE or from the command line:

## Functionality
- **Image Loading:** The script loads the specified image using OpenCV (cv2) and converts it from BGR to RGB color space.
- **Grayscale Conversion:** Converts the loaded RGB image into a grayscale image using cv2.cvtColor().
- **Thresholding:** Performs thresholding to create a binary mask (cv2.threshold()).
- **Object Extraction:** Utilizes the binary mask to extract the desired object from the original image using cv2.bitwise_and().
- **Visualization:** Displays the original image and the extracted object using Matplotlib for easy comparison.
Examples
The examples directory contains sample images and their corresponding extracted objects obtained using the script.

## Customization
- Adjust threshold values `(cv2.threshold())` in the script to fine-tune object extraction based on image characteristics.
- Explore other image processing techniques in OpenCV for more advanced object extraction methods.

## Contributing
- Contributions are welcome! If you have suggestions, improvements, or feature requests, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License]().
