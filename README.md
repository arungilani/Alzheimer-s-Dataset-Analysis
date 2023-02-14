# Alzheimer-s-Dataset-Analysis
This is a beginner level Data Science project in where I did some exploratory data analysis and machine learning on a dataset determining if someone had Alzheimer's or not.
# The dataset
The dataset was downloaded from this github- https://github.com/deepak525/Dementia-Classification-Compare-Classifiers

### Understanding the data
-The dataset includes the longitudinal collection of 150 samples aged 60 to 96. Each person had an mri scan done 2-3 times, for a total of 373 imaging sessions. 

-72 of the subjects were grouped as 'Nondemented' throughout the study.

-64 of the subjects were grouped as 'Demented' at the time of their initial visits and remained so throughout the study.

-14 subjects were grouped as 'Nondemented' at the time of their initial visit and were subsequently characterized as 'Demented' at a later visit. These fall under the 'Converted' category.

| COL  | Description                         |
|------|-------------------------------------|
| EDUC | Years of Education                  |
| SES  | Socioeconomic Status                |
| MMSE | Mini Mental State Examination       |
| CDR  | Clinical Dementia Rating            |
| eTIV | Estimated Total Intracranial Volume |
| nWBV | Normalize Whole Brain Volume        |
| ASF  | Atlas Scaling Factor                |

**Clinical Info:**
- MMSE - Mini-Mental State Examination score (range is from 0 = worst to 30 = best)
- CDR - Clinical Dementia Rating (0 = no dementia, 0.5 = very mild AD, 1 = mild AD, 2 = moderate AD)
- Derived anatomic volumes
- eTIV - Estimated total intracranial volume, mm3
- nWBV - Normalized whole-brain volume, expressed as a percent of all voxels in the atlas-masked image that are labeled as gray or white matter by the automated tissue segmentation process
- ASF - Atlas scaling factor (unitless). Computed scaling factor that transforms native-space brain and skull to the atlas target (i.e., the determinant of the transform matrix)
