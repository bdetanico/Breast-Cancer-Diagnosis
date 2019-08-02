# Project: Breast Cancer Diagnosis - EDA and Machine Learning

The dataset, found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29, consists of features which were computed from digitized images of fine needle aspirate (FNA) procedure of breast mass. The features describe characteristics of the cell nuclei present in the images.

Ten real-valued features are computed for each cell nucleus. The following nuclear features were analyzed:

	a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)

The dataset has the following attribute information:

**(a) Number of instances: 569**

**(b) Number of attributes: 32** 

1. ID

2. diagnosis: The diagnosis of breast tissues (M = malignant, B = benign) - Class distribution: 357 benign, 212 malignant

3. radius_mean: mean of distances from center to points on the perimeter
4. texture_mean: standard deviation of gray-scale values
5. perimeter_mean: mean size of the core tumor
6. area_mean
7. smoothness_mean: mean of local variation in radius lengths
8. compactness_mean: mean of perimeter^2 / area - 1.0
9. concavity_mean: mean of severity of concave portions of the contour
10. concave points_mean: mean for number of concave portions of the contour
11. symmetry_mean
12. fractal_dimension_mean: mean for "coastline approximation" - 1

13. radius_se: standard error for the mean of distances from center to points on the perimeter
14. texture_se: standard error for standard deviation of gray-scale values
15. perimeter_se
16. area_se
17. smoothness_se: standard error for local variation in radius lengths
18. compactness_se: standard error for perimeter^2 / area - 1.0
19. concavity_se: standard error for severity of concave portions of the contour
20. concave points_se: standard error for number of concave portions of the contour
21. symmetry_se
22. fractal_dimension_se: standard error for "coastline approximation" - 1

23. radius_worst: "worst" or largest mean value for mean of distances from center to points on the perimeter
24. texture_worst: "worst" or largest mean value for standard deviation of gray-scale values
25. perimeter_worst
26. area_worst
27. smoothness_worst: "worst" or largest mean value for local variation in radius lengths
28. compactness_worst: "worst" or largest mean value for perimeter^2 / area - 1.0
29. concavity_worst: "worst" or largest mean value for severity of concave portions of the contour
30. concave points_worst: "worst" or largest mean value for number of concave portions of the contour
31. symmetry_worst
32. fractal_dimension_worst: "worst" or largest mean value for "coastline approximation"

Breast cancer is the most-common invasive cancer in women and affect about 12% of women worldwide (McGuire, A; Brown, JA; Malone, C; McLaughlin, R; Kerin, MJ (22 May 2015). "Effects of age on the detection and management of breast cancer". Cancers. 7 (2): 908–29. doi:10.3390/cancers7020815).

The fine needle aspiration (FNA) procedure helps establish the breast cancer diagnosis. Together physical examination of breasts and mammography, FNAC can be used to diagnose breast cancer with a good degree of accuracy.

A well-described characteristics in terms of the cell nuclei through digitized image, including the establishment of patterns/models, can helps improve breast cancer diagnosis.

![**Figures 1, 2 and 3.** Digital images from a breast FNA. M. W. Teague, W. H. Wolberg, W. N. Street, O. L. Mangasarian, S. Labremont, and D. L. Page. Indeterminate fine needle aspiration of the breast: Image analysis aided diagnosis. Cancer Cytopathology 81: 129-135, 1997. W. N. Street. Xcyt: A System for Remote Cytological Diagnosis and Prognosis of Breast Cancer. Management Sciences Department. University of Iowa, Iowa City, IA.](https://i.imgur.com/GDZSUKn.jpg)

**Objective**: Analyse cell nuclei characteristics, and if possible, identify patterns related to the diagnosis of breast tissues (malignant or benign). Additionally, it will be proposed a machine learning models for diagnosis.
