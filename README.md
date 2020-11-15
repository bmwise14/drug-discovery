**TLDR**
- **The Original Repository has not been updated, so many of its features no longer run. The paper will highlight information that the system does.**

At my internship at OneThree Biotech in Summer 2018, I extracted structural features from simplified molecular-input line-entry system (SMILES) data on drugs with known blood-brain barrier passage labels (binary). 

I created a CNN classifier which used structural features of the images generated from these SMILES. 

I also created a random forest classifier for use with chemical descriptors of the drugs. I then ensembled those results with a logistic regression using the probabilities of each model. We created a simple webpage that puts all of this work together. Please read the paper for more information. Thanks!

