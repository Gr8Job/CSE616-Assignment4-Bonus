# CSE616 Bonus Assignment4
This notebook implements a simple GAN network of 1D latent space. The GAN learns a predefined data distribution  and generates data from a learned distibution  which is very close to the real data distribution. 
The implementation was done based on the example found in the below link:

https://www.tensorflow.org/guide/keras/writing_a_training_loop_from_scratch#end-to-end_example_a_gan_training_loop_from_scratch

Below are the main results of the excercise showing the two distributions $P_{data}(x)$ & $P_{model}(x)$ at the begining and at the end of the training:

![image](https://user-images.githubusercontent.com/19870905/170834601-ef93a5d0-3472-4872-b263-efc11f2361b8.png)

![image](https://user-images.githubusercontent.com/19870905/170834538-b0956052-75e2-4a96-870f-1722e325203d.png)
