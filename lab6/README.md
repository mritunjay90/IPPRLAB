# Lab Report: Image Processing and Computer Vision Experiments

## Abstract
This report summarizes the practical work completed in the IPPR lab, covering image segmentation, face detection, and SIFT-based keypoint detection. The experiments demonstrate basic image processing techniques using OpenCV and Python.

## Objectives
- Understand image preprocessing and transformation techniques.
- Apply segmentation methods to identify regions of interest.
- Detect faces in video frames using Haar cascades.
- Extract and visualize SIFT keypoints from an input image.

## Methodology
The experiments were implemented using Python and OpenCV. The workflow included:
1. Loading and preprocessing images.
2. Applying grayscale conversion, filtering, and edge detection.
3. Performing segmentation and connected component analysis.
4. Detecting faces from video frames.
5. Using SIFT to detect and display keypoints.

## Experimental Setup
The following Python libraries were used:
- OpenCV
- NumPy
- Matplotlib
- SciPy
- scikit-image

Install dependencies using:

```bash
pip install opencv-python numpy matplotlib scipy scikit-image
```

## Results and Observations
- Segmentation produced meaningful connected components from the processed image.
- Face detection successfully marked detected regions in the video frame.
- SIFT detected a large number of keypoints, which were visualized on the input image.

## Conclusion
The laboratory exercises provided a practical introduction to fundamental image processing and computer vision tasks. The results show how basic operations such as filtering, segmentation, detection, and feature extraction can be combined to analyze digital images effectively.

## Notes
- The Lab 6 notebooks require the relevant image and video files to be present in the same folder as the notebook.
- The SIFT example expects the file `home.jpg` to be available.
