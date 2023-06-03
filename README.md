# Brain-Disorder-Detection-in-MRI-Images
Detecting the occurance of Alzheimers in RAW as well as FSL(fMRI Software Library) Processed images using 2D-CNN and Transfer learning models like VGG16 and ResNet 50

## Data Aquisition: 
The OASIS cross-sectional dataset is composed of MRI scans from a total of 416 individuals, whose ages range from 18 to 96 years old. Each participant underwent between 3 and 4 T1-weighted MRI scans in a single scan session. All of the individuals included in the dataset are right-handed and consist of both men and women. Within this dataset, there is a subgroup of 100 individuals over the age of 60 who have received a diagnosis of very mild to moderate Alzheimer's disease. Along with the main dataset, an additional dataset of 20 individuals who have not been diagnosed with dementia and who were imaged during a second visit within 90 days of their first session is also provided. The dataset includes both Raw and FSL-SEG images, with Raw images representing the original, unprocessed data, while FSL-SEG images are brain-extracted and segmented.

The OASIS dataset contains two types of image files: raw MRI images and FSL-SEG images.

Raw MRI images are the original, unprocessed images captured by the MRI scanner. They contain information about the structure and composition of the brain but also include noise and artifacts.

![image](https://github.com/itssaiii/Brain-Disorder-Detection-in-MRI-Images/blob/main/rawimages/OAS1_0001_MR1_mpr-3_anon_sag_66.gif)

FSL-SEG images, on the other hand, are processed and segmented MRI images. They have been run through a software tool called FSL (FMRIB Software Library) which segments the images into different tissue types such as gray matter, white matter, and cerebrospinal fluid (CSF). These images provide a more detailed representation of the brain structure and are commonly used for brain image analysis.

![image](https://github.com/itssaiii/Brain-Disorder-Detection-in-MRI-Images/blob/main/fslimages/OAS1_0001_MR1_mpr_n4_anon_111_t88_masked_gfc_fseg_tra_90.gif)





