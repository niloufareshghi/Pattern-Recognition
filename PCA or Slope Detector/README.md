One of the most critical tasks in Image Preprocessing is extracting the slope of objects according to the horizontal or vertical axis. You will be faced with implementing a PCA-based solution to this
problem.

a. Load RGB base.jpg image and convert it to a grayscale single channel image. Different approaches exist that address the mentioned conversation. One of them is averaging the
triple channels.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/6c43a095-71a1-4b1a-8fcf-0a06642edf01)


b. Now, you should detect pixels of the watch. To aim this, with a threshold, convert the grayscale image to a binary image(0 or 255).

c. You map the watch's pixels to R2 space in this step. You can extract horizontal and vertical indexes of pixels that are in the watch`s area. Now you have a dataset that has two features
(indexes). plot the obtained dataset.

d. Implement the PCA and perform it on the dataset and obtain eigenvectors and eigenvalues; plot the obtained eigenvectors and points in one graph. Discuss the eigenvalues and corresponding eigenvectors.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/86b40914-7eec-4a53-b160-b43095966881)


e. Using the eigenvectors, calculate the slope of the watch based on the horizontal axis. repeat these steps for all test images.

![test1](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/c2a99b2e-06cf-4ff3-8f70-e0ee76aa18fc)


![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/1c1fcfef-fcdb-467d-94b9-174748431704)
