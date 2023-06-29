In Kernel Density Estimation, the Smoothing Parameter or Bandwidth controls the number of
samples or window of samples used to estimate the probability for a new point. While a large
window may result in a coarse density with little detail, a small window may also have too much
detail and not be smooth or general enough to correctly cover new or unseen examples.
In this problem, we are to investigate the importance of this parameter in practice.
Consider the following two probability density functions:

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/1fa48047-9122-40f7-9b4e-3b59652dec6c)

a. Sketch the PDFs.

b. Generate n i.i.d samples from the given PDFs, assuming N = {10, 100, 1000}.

c. For a univariate Gaussian kernel, it is often recommended to select h* = 1.06sˆN-1 5,
where h* is the optimal choice of bandwidth, n is the number of samples, and sˆ is the
estimate of the standard deviation of the samples. Calculate the sample standard deviation, sˆ. For each, estimate the optimal value for bandwidth, h*(n).

e. Summarise your results by plotting the two PDF estimates. For each of the given densities, you need to have 9 plots overall (18 in total). Overlay each plot with the ground truth densities. 
