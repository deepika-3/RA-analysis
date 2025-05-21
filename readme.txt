readme_content = """
# MRI Knee Image Segmentation

This project performs automatic segmentation of knee MRI images using Otsu's thresholding.

Required  Files

- `main.py`: Processes and segments the MRI `.nii.gz` image.
- `mail.py`: Sends the segmented output as a zip file via email.
- `3702_left_knee.nii.gz`: Input MRI image file.

##  How to Use

1. Install dependencies:

pip install numpy matplotlib scikit-image nibabel
