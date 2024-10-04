# Descriptors-Compression-By-Autoencoder
We study a compression strategy for local descriptors using SURF (Speeded Up Robust Feature), which is a faster version of SIFT (Scale Invariant Feature Transform). In order to address this task, we implemented a Variational Autoencoder (VAE) model and the generated descriptor were trained with the images of dataset of Portello and Castle from https://github.com/openMVG/SfM_quality_evaluation/tree/master/Benchmarking_Camera_Calibration_2008. The testing process was done on dataset FountainP-11 and Tiso from https://drive.google.com/drive/folders/1mg54KIq6wAC8Z6ZJ2c8JH-hO28tudGu-?usp=sharing.
Once we generated the descriptors feature and a matching process, we performed a sparse reconstruction using SfM (Structure from Motion) to create a 3D visualization of the descriptors. To produce the images reconstruction we used COLMAP only for the test set.
## Language:
Python
