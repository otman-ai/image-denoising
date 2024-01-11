# Image Denoising using Autoencoder 

In this Reposrity,I used Autoencoder to test 22 differents models to find the best architechture that suite image denoising problem. I tries Convolution Neural Network with different parametres (kernel size, filter) as well as Fully connected layer with different Hidden unites.

The notebook contains all the code without the logs because I have trouble with timout in colab (Runing the notebook may take more then 6 hours that is why you find only the logs of the first 13 models ) . SO I highly recommand you if you have GPU in your local machine and you want to see all the results of each model, run all the cells .

Make sure you have installed all the libraries :
## Dataset
We used Two different datasets from [kaggle](https://www.kaggle.com),  [Smartphone Image Denoising Dataset (SIDD)](https://www.kaggle.com/datasets/rajat95gupta/smartphone-image-denoising-dataset) and 
[Super Resolution Benchmarks](https://www.kaggle.com/datasets/jesucristo/super-resolution-benchmarks) . 
The first one has the noised already but for the  second one(Super Resolution Benchmarks) I have to build function that added noises to each one of the entire dataset. 
We merge the two after adding noises to the second one and then we implement `tf.data.Dataset.from_tensor_slices` to load the data to the models .

if you prefer to work on kaggle you can check the notebook [here](https://www.kaggle.com/code/otmanheddouch/image-denoising-using-autoencoder/notebook?scriptVersionId=157356759)

## Notebook 
Tensorflow is the framework that we used in the notebook, and we manage to build 22 different models to see what architechture will suite image denoising problem .

### Evaluation 
for evaluation we use Mean square error (MSE) and Mean absolute error (MAE)
TODO: metrics results
TODO : bar chart 
## Useful Resources :
* [Using Autoencoder to denoise images](https://medium.com/@otmanheddouchai/autoencoder-3ab170b1842d)
* [An Introduction to Autoencoders](https://arxiv.org/pdf/2201.03898.pdf)



