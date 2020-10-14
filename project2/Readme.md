Github link for Project 1 https://github.com/idaf-ai/sensor-embeddings

Project 2.
AutoEncoder

This project is composed of two parts, PCA analysis and auto encoder.

The data is in the data folder, with the training file compressed due to file upload size.

The PCA analysis is done on the PCA.ipynb Jupyter notebook. The number of dimensions was scaled from 2 to 500, with increments selected manually.

Once the training and test data is reduced to the specified dimensions, it was applied to a optimized SVC model and the accuracy and variance is recorded.

The same analysis is done using auto encoders with 1 layer and 2 layers.

The 1 layer auto encoder had better performance than the 2 layers.

After the comparison was done, the tuning program was run to identify an optimal number of dimensions in the range of 80 to 100 dimensions.

Several optimization functions were also tested. Adam, Stochastic gradient descent (SGD), RMS Prop, and Adamax.

The RMS Prop and Adamax performed better than Adam, which performed better than SGD.

