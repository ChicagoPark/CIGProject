# CIGProject

Problem solving techniques

Magnetic Resonance Imaging(MRI) reconstruction = Inverse problem


[Terminology Definition]
1. P: Sampling operator
2. F: Fourier transform
3. x: input image
4. e: noise vector


Role of CNN(f_theta): 
input data of CNN: `x_hat` through inverse Fourier transform
Output data of CNN: x
Recover image x from y

How to get zero-filled images

Zero-Fill
Zero-Filling is the process of adding data points to the end of the FID before Fourier Transform.

Zero-Filling can improve data quality by increasing the amount of points per ppm in the processed data to better define the resonance. The added data points have 0 amplitude so the only change of the processed data is more discreet data points.

The Zero-Fill menu is located under the Processing tab then Zero-Fill/LP. LP is Linear Prediction which is discussed here:


[Things to do]
1. Check the format of the dataset
2. Define the role of Fourier transform
3. Check how to 
