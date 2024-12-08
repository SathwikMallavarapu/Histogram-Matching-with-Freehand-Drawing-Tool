# Histogram Matching with Freehand Drawing Tool

## Team Members
- Sathwik Mallavarapu

## Software Used
- **Operating Systems**: Windows
- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Image Processing Libraries:** OpenCV, PIL (Pillow)
- **Development Environment:** Visual Studio Code

## Project Overview
This project focuses on the development of a Python-based graphical user interface (GUI) application for interactive image processing, specifically targeting histogram matching. Histogram matching adjusts the color distribution of one image to resemble that of another. This application features a freehand drawing tool, enabling users to intuitively mark areas for localized histogram matching.

### Key Features
- **Freehand Drawing Tool**: Allows users to sketch directly on the image for localized processing.
- **Histogram Matching**: Real-time color distribution adjustment using OpenCV's LAB color space.
- **Basic Image Editing**: Supports image loading, drawing, clearing, and exporting results.
- **User-Friendly Interface**: Provides responsive and intuitive buttons for seamless operation.

## Functional Requirements
1. **Load and Display Images**
   - Load a target and reference image from local storage.
   - Display both images within the GUI.
   
2. **Freehand Drawing Tool**
   - Draw directly on the image to select regions for processing.
   - Options to clear/reset drawings.

3. **Histogram Matching**
   - Match the histogram of the user-selected region with the reference image.
   - Apply real-time adjustments for instant feedback.

4. **Export Results**
   - Save the processed image to the local system in supported formats (e.g., JPG, PNG).

5. **User Interface**
   - Intuitive design with clear buttons for loading, drawing, resetting, and exporting.


## Installation Guide
1. Clone this repository:
   ```bash
   git clone https://github.com/SathwikMallavarapu/Histogram-Matching-with-Freehand-Drawing-Tool
   cd histogram-matching-tool

## Install dependencies:
opencv-python==4.5.5.64, 
Pillow==8.4.0,
numpy==1.21.5, 
matplotlib==3.5.1, 

## Run the application:
python main.py

## Expected Output
**Input**: Images in PNG or JPG formats with dimensions up to 1920x1080.
**Output**: Processed images with localized histogram-matched sections in the same format as input.

## References and Resources
## Python Libraries and Documentation
1. **OpenCV Documentation**  
   - URL: [https://docs.opencv.org/](https://docs.opencv.org/)  
   - Description: Comprehensive guide to OpenCV, used for image processing and histogram matching.

2. **Pillow (PIL) Documentation**  
   - URL: [https://pillow.readthedocs.io/](https://pillow.readthedocs.io/)  
   - Description: Used for image manipulation and compatibility with standard formats like JPG and PNG.

3. **NumPy Documentation**  
   - URL: [https://numpy.org/doc/](https://numpy.org/doc/)  
   - Description: Essential for numerical computations, including pixel manipulation.

4. **Matplotlib Documentation**  
   - URL: [https://matplotlib.org/stable/contents.html](https://matplotlib.org/stable/contents.html)  
   - Description: Used for visualizing histogram data during development and debugging.

## Articles and Tutorials
1. **Introduction to Histogram Matching in OpenCV**  
   - Author: PyImageSearch  
   - URL: [https://pyimagesearch.com/](https://pyimagesearch.com/)  
   - Description: A beginner-friendly introduction to the concepts and implementation of histogram matching using OpenCV.

2. **Color Space Transformations in OpenCV**  
   - Author: OpenCV Tutorials  
   - URL: [https://opencv-python-tutroals.readthedocs.io/](https://opencv-python-tutroals.readthedocs.io/)  
   - Description: Guide to LAB color space transformations used in this project for accurate histogram matching.

## GUI and Application Development
1. **Tkinter GUI Programming by Example**  
   - Author: David Love  
   - URL: [https://realpython.com/python-gui-tkinter/](https://realpython.com/python-gui-tkinter/)  
   - Description: Useful resource for building the GUI using Tkinter.


## Acknowledgments
1. **Stack Overflow**  
   - URL: [https://stackoverflow.com/](https://stackoverflow.com/)  
   - Description: For troubleshooting and resolving technical issues during development.

2. **Open Source Community**  
   - Description: Thanks to the open-source contributors for maintaining these libraries and tools.


## Notes
- If you use additional external resources, make sure to update this file to include the citation.
- All code implementations follow the usage guidelines provided in the official documentation of the libraries mentioned above.


## Comments and Documentation
The code is well-commented for readability and understanding.
A step-by-step guide for usage is included within the help.md file.

## Future Scope
Add advanced image filters such as sharpening and blurring.
Enable batch processing for multiple images simultaneously.
Integrate with cloud storage platforms for saving and retrieving images.
