readme_content = """
#  Random Contour Expansion for Medical Segmentation

In this project I performed **randomized expansion** of binary segmentation masks obtained  from 3D MRI volumes. The goal is to simulate natural variations or uncertainty in segmentation boundaries while ensuring:

 No shrinkage below the original mask  
 No growth beyond a specified maximum (e.g., 2mm)  
 Controlled randomness for robustness or augmentation

---

##  Features

- Otsu-based binary mask generation from MRI slices  
- Contour expansion by physical distance (in mm) using voxel spacing  
- Random expansion with hard upper and lower limits  
- Batch processing for all image slices  
- Results saved in an output folder and zipped for download (e.g., in Google Colab)



