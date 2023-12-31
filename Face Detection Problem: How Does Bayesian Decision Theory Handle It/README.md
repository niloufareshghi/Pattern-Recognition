So far you have probably got familiar enough with the Bayesian Decision Theory to know what to
expect from it. If the decision problem is posed in probabilistic terms and all relevant probability
values are known, BDT allows one to take optimal decisions that minimize errors by choosing the least
risky class. Although in many practical classification problems, these conditions are not fulfilled and
therefore BDT won’t be effective, there are still some applications where it may come in handy.

Face Detection (not to be mistaken with Face Recognition) is the process of identifying and locating
human faces in digital images and videos. It is often the first step in many face-related machine
vision applications such as face recognition, emotion detection, gender detection, etc. Now we are
going to find out how BDT deals with this problem in practice.
You are given a customized dataset divided into two ‘train and ‘test’ sections. The train set consists
of 50 face images alongside the corresponding face masks. These binary masks indicate face pixels
with white (or binary value 1) and non-face pixels with black (or binary value 0).

a. First assume images in the training set. Considering two classes for each pixel, ‘face’ and
‘non-face’, use the provided masks to find the class priors.

b. We want to model the class-conditional probability density of each class using a univariate
Gaussian. Find the mean and variance of both class-conditional densities.

c. Apply your classifier on the test images and display the results. Also, report the test error
using the given masks.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/f27275de-7215-442b-8d06-bd96d446e001)

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/361779a7-83ee-4381-a0f4-dcded58cd32d)

*error = 0.090503162380861*

d. Compute a confusion matrix for your classifier.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/ab04950c-0849-4cf9-b463-af373221ab3d)
