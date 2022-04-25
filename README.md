## Advanced Lane Finding - ASU Image Processing Project Phase 1 submission


The Project
---

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.


## Usage:

### 1. Set up the environment 
`conda env create -f environment.yml`

To activate the environment:

Window: `conda activate laneDetection`


### 2. Run the pipeline:
```bash
python main.py INPUT_IMAGE OUTPUT_IMAGE_PATH
python main.py --video INPUT_VIDEO OUTPUT_VIDEO_PATH
```

### 3. Contributures:
```
Ahmed Ezz El-Deen Mahmoud -    1700121
Ahmed Ashraf Hassan -          1700030
Ahmed Gamal Hassan -           17t0008 
```
