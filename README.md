# NN_see_image
keras application to cluster images using PCA, tSNE and UMAP

the code uses emoji dataset to try clustering images

## the algorythm is following:

- load neural network from keras.applications (here we use Xception)
- remove last layer to produce vector representing how neural net "sees" the image
- run images dataset througth neural network to produce those vector representations and write them to data matrix
- apply different dimensionality reduction methods to the data matrix

## here are some funny examples: 

### Flags
![alt text](https://raw.githubusercontent.com/vovalive/NN_see_image/blob/master/images/flags.png)

### Females
![alt text](https://raw.githubusercontent.com/vovalive/NN_see_image/blob/master/images/female.png)

### Males 
![alt text](https://raw.githubusercontent.com/vovalive/NN_see_image/blob/master/images/male.png)
