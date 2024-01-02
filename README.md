# Image Denoising using Autoencoder 
in this repository, we will build 22 different models in order to find the best archetichture that remove noises very well  from given images.
TODO: Image of denoising and predicted value
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



