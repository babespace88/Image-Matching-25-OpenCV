# Image-Matching-OpenCV



Dataset ---> https://www.kaggle.com/competitions/image-matching-challenge-2025

Model --->  ALIKED and LightGlue, and DINO , on GPU. 

Notebook Solution ---> https://github.com/babespace88/Image-Matching-25-OpenCV/blob/main/image-matching-challenge-2025.ipynb


------------------------------------------------------------------------------------------------------------------------------


The challenge is to:


Group together the photos that belong to the same scene or object.

Ignore the unrelated (outlier) photos.

For each group, reconstruct the 3D scene and figure out where each photo was taken from (its camera position and direction).


----------------------------------------------------------------------------------------------------------------------------------


From the results mean :


ETs_another_et_another_et001.png_public: unique ID for the image

ETs: from the ETs dataset

cluster0: assigned to scene/cluster 0 (so grouped with other images of the same scene)

another_et_another_et001.png: actual image file

0.999800777;-0.003973104;0.019560673;0.003576425;0.999788088;0.020272831;-0.019637074;-0.020198835;0.999603117: rotation matrix (3x3)

-2.066643869;-1.589019150;2.083108070: translation vector (camera location)
