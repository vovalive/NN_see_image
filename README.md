# NN_see_image

based on https://github.com/ml4a/ml4a-guides/blob/master/notebooks/image-tsne.ipynb
keras application to cluster images using PCA, tSNE and UMAP

the code uses emoji dataset to try clustering images

## the algorythm is following:

- load neural network from keras.applications (here we use Xception)
- remove last layer to produce vector representing how neural net "sees" the image
- run images dataset througth neural network to produce those vector representations and write them to data matrix
- apply different dimensionality reduction methods to the data matrix

## here are some funny examples: 

### Flags
![alt text](https://github.com/vovalive/NN_see_image/blob/master/images/flags.png)

### Females
![alt text](https://github.com/vovalive/NN_see_image/blob/master/images/female.png)

### Males 
![alt text](https://github.com/vovalive/NN_see_image/blob/master/images/male.png)
