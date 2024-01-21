# EDA and ML Classification on a Brain Tumor MRI Kaggle Dataset
---
### Dataset Description
This dataset comprises features extracted from brain MRI, containing first and second order statistical measures of the image. The fearures are categorized as follows:

**First-Order Features:**
- Mean: Average intesity of pixel values in the image
- Variance: Measur of the spread of pixel values around the mean
- Standard Deviation: Square root of the variance and degree of variation
- Skewness: Measure of the asummetry of the pixel value distribution
- Kurtosis: Measure of the tailedness and shape of the pixel value distribution

**Second-Order Features:**
- Contrast: Measure of the intesity variation between neighboring pixels
- Energy: Sum of the squared elements in the image, indicating image uniformity
- ASM (Angular Second Moment): Measure of the intensity variation between neighboring pixels
- Entropy: Measure of the randomness or uncertainty in pixel values
- Homogeneity: Indicates the closeness of pixel values in the image
- Dissimilarity: Measures the difference between neighboring pixel values
- Correlation: Describes the linear relationship between pixel values
- Coarseness: Reflects the granularity and roughness of the image

The dataset includes an "Image" column specifying the image name and a "Class" column indicating whether the image contains a tumor or not (1 = Tumor, 0 = Non-Tumor). The goal is likely to use these features to predict the presence or absence of a brain tumor in medical imaging.
