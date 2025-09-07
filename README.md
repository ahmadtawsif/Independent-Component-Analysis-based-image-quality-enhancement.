# Introduction
In this project the capacity of Independent Component Analysis (ICA) was used to remove noise and artifacts from image.
Here, fastICA algorithm was used to perform the image cleansing task. 

# Independent Component Analysis (ICA)
Independent Component Analysis (ICA) is a computational method used to separate a multivariate signal into statistically independent components, 
often applied in blind source separation problems where the original sources and the mixing process are unknown. Unlike Principal Component Analysis (PCA), 
which finds uncorrelated directions with maximum variance, ICA goes further by identifying non-Gaussian and independent signals. 
This makes it particularly useful in applications such as separating overlapping voices in audio recordings (the “cocktail party problem”), 
removing artifacts from biomedical signals like EEG or fMRI, isolating factors in financial data, and cleaning or enhancing images. 
By leveraging statistical independence, ICA provides a powerful way to uncover hidden structure in complex, mixed datasets.

# Task 
Two source images are linearly mixed and corrupted with Gaussian or log-normal noise to simulate real-world distortions. 
ICA is then applied to the noisy mixtures to exploit the statistical independence of the original sources, successfully unmixing the signals and recovering cleaner versions of the images. 
This shows how ICA can be an effective tool for separating and denoising images in practical scenarios.

# Result
fastICA successfully separated the mixed and noisy images into their independent source components.

Even with Gaussian and log-normal noise, the recovered images preserved the main structures and details of the original sources.

The method demonstrates robustness of ICA for blind source separation and image denoising tasks.
<img width="500" height="500" alt="download" src="https://github.com/user-attachments/assets/8b5382de-a471-4327-86cf-b34b0076be5d" />

