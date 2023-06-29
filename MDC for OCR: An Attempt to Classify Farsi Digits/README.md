A Minimum Distance Classifier attempts to classify an unlabelled sample to a class that minimizes the distance between the sample and the class in multi-feature space. As minimising distance is a measure for maximizing similarity, MDC actually assigns data to its most similar category.
While MDC might look too basic, it works pretty well in some problems. One of them could be Optical Character Recognition (OCR), where the goal is to distinguish handwritten or printed text characters inside digital images of documents. Here, we aim to apply this technique to the problem of Farsi digits classification. We use a dataset named Hoda, which contains 102353 samples of digits written by candidates of the Karshenasi Arshad entrance exam in their registration forms, Figure 2. You are given a shorter version of this dataset in which the images are binary.

a. Use the training set to calculate the prototype of each class. Display the results.
b. Now use the test samples to evaluate your MDC classifier. Report the error, and display five
erroneous predictions.
