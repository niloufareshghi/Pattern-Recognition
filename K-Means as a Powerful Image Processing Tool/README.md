Despite its simplicity, K-Means can be applied to various machine learning tasks. From document classification and data analysis to fraud detection and collaborative filtering, this algorithm still challenges even newly introduced methods in different applications, which many of which are known to be state-of-the-art.
The goal of this problem is to get you more familiar with some of the things you can do with K-Means in the area of image processing. Given below are three different, but structurally similar image processing tasks and you are required to propose a method to solve them using K-Means.

a. Color Extraction is the process of identifying and extracting key colors in images. It gives a better visual understanding of images while providing significant features for other computer vision tasks.
Load the image “trump_tie_1.jpg“. Use K-Means to extract its 3, 5, 7, and 9 main colors.
Display these colors properly in separate square shapes.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/a31bea28-bf07-40c5-aec0-9d0ef425751d)

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/e0c9cdb7-49df-46c6-b017-29f22b1d14dd)



b. Image Segmentation is a common technique in image processing in which the goal is to
divide an image into multiple parts or regions, often based on the characteristics of the
pixels in the image.
Load the image “trump_tie_2.jpg“. Use K-Means to divide the given image into 3, 5, 7, and
9 partitions.

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/21305ef5-d652-4f49-a9e2-11eb9cfa111a)

9 Partitions:

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/77063ced-3c0d-403f-866e-2c8ffea463f9)


c. Image Compression refers to techniques used for minimizing the size of an image using the
image data which are repeated in the image.
Load the image “trump_tie_3.jpg“. Use K-Means to reduce the size of the input image to
%50, %75, %90, and %97 of the original image size (in KB).

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/3adfa596-d3cd-4d0f-a582-c4037fe6f40d)

size = 145612

For a reduction to 50% of the original image size

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/e518b7a8-c93e-4feb-a52c-ce63d9b16e88)

size = 70526

