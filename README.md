# VAE
Implementation of Variational Auto Encoder (VAE) on mnist data



#### Model:

  + Variational Auto Encoder is one of the powerful generative models
  + In this project I have used MNIST dataset which can be available in pytorch datasets, to train the model and generate similar new digits
  + Used Conv layers to extract features in encoder  and deconv layers to upsample in decoder
  
#### Evaluation :

  + We can see the quality of images generated in analysis file during training. Actually it generated very good samples for just 20 epochs. 
  + I also plotted Tsne, to see how latent data is distributed. We can see in analysis file that similar digits are clustered together in latent
    space.
  + I further evaluated model (how good latent representation) by training SVM classifier and got very good results.
  
  
  
  
You can access weights of the final best model from here (https://drive.google.com/file/d/1-8W_uzkwxUl0EJliEWD-Lp0TC9ffFtxO/view?usp=sharing)
