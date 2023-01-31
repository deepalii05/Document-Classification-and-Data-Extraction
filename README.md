# Document-Classification-and-Data-Extraction
We proposed a model that takes a pdf or image consisting of multiple documents and identifies the set of documents present in the pdf. 
This is done by splitting the input PDF into single pages. Each individual page is classified into its respective document type using the CNN model. 
Then we leverage OCR (optical character recognition) to extract data from each document. 
This is proposed for five documents (Aadhar, PAN, driver's license, passport, and voter ID). 
The input pdf must have a single document on one page, except for the front and back of the same document
