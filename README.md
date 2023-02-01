# Document-Classification-and-Data-Extraction
We proposed a model that takes a pdf or image consisting of multiple documents and identifies the set of documents present in the pdf. 
This is done by splitting the input PDF into single pages. Each individual page is classified into its respective document type using the CNN model. 
Then we leverage OCR (optical character recognition) to extract data from each document. 
This is proposed for five documents (Aadhar, PAN, driver's license, passport, and voter ID). 
The input pdf must have a single document on one page, except for the front and back of the same document.
With respect to gains of 0.6923 and losses of 0.8340, our data classification model achieved
0.7342 accuracy on the training set and 0.7736 accuracy on the validation set.

