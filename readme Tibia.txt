readme_content = """
#  # Tibia Landmark Detection & Mask Generation

This project performs **segmentation mask generation and deformation** 
for the tibia bone using synthetic 3D data. It includes:
- Original tibia mask
- Expanded masks (2 mm and 4 mm)
- Two randomized (elastically deformed) masks

All masks are saved as `.nii.gz` files and exported as a ZIP file.

## 📁 Outputs
Each of the following masks is saved in the `output_masks` directory: and downloaded that for later use.

- `Original_Mask.nii.gz`
- `Expanded_2mm_Mask.nii.gz`
- `Expanded_4mm_Mask.nii.gz`
- `Randomized_Mask_1.nii.gz`
- `Randomized_Mask_2.nii.gz`

## 🧰 Requirements

I have used **Google Colab** and  installed the following 
Python packages 


pip install numpy nibabel scipy

