# Compress-and-Classify-Hyperspectral-Data-using-GANs

Dataset used here is IndianPines dataset.

Indian Pines is a Hyperspectral image segmentation dataset. The input data consists of hyperspectral bands over a single landscape in Indiana, US, (Indian Pines data set) with 145×145 pixels. For each pixel, the data set contains 220 spectral reflectance bands which represent different portions of the electromagnetic spectrum in the wavelength range 0.4−2.5⋅10−6.

Dataset link - https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes

Initially preprocessed the data using StandardScaler, then extracted the principal components using PCA, and finally divided the data into patches for generator input.


