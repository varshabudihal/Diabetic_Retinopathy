# Diabetic_Retinopathy
## What is Diabetic Retinopathy?
Diabetic retinopathy is caused by damage to the blood vessels in the tissue at the back of the eye (retina). Poorly controlled blood sugar is a risk factor.

This is a Kaggle competition which I implemented as a project. The dataset for this can be found here:
https://www.kaggle.com/c/diabetic-retinopathy-detection

We are provided with a large set of high-resolution retina images taken under a variety of imaging conditions. A left and right field is provided for every subject. Images are labeled with a subject id as well as either left or right (e.g. 1_left.jpeg is the left eye of patient id 1).

A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:

0 - No DR
1 - Mild
2 - Moderate
3 - Severe
4 - Proliferative DR

The data is divided into multiple parts, consisting of 82GB. So I mounted the data onto my Drive and used the link in my notebook.

By doing predictions, I get to know that upto 74% of test data belongs to category number 5, that is, Proliferative DR where the retina is deprived of oxygen causing it to create more blood vessels which fills the black of the retina.
