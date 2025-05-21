readme_content = """
# MRI Knee counter Expansion

 Contour Expansion for MRI Segmentation

This project performs **automated segmentation and contour expansion** of 
2D MRI slices extracted from 3D `.nii.gz` medical images. 
It includes:

- Otsu-based mask generation (threshoulding) 
- Binary mask expansion (e.g., 2mm)  
- Randomized contour adjustment (for clear visualization) 
- Batch processing and output visualization  
- Automatic ZIP and download ( Google Colab)

 work  by steps:

Load 3D MRI (`.nii.gz`) and extract 2D slices  
2. Compute binary mask using **Otsu’s method**  
3. Expand mask using **voxel spacing**  
4. Generate **randomized contour** between original and expanded mask  
5. Save and zip all slices

