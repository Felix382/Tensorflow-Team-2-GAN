# Tensorflow-Team-2-GAN

The skript is designed to use shared folders from google drive. The CT Scans from this folder have been copied into github in folder "CT_COVID".

The code heavily relies on the Google tutorial on Deep Concolutional GANs as published at https://www.tensorflow.org/tutorials/generative/dcgan. In fact, we only changed some minor but crucial things, in particular we go without the drop-out option, because every single pixel contains information.

The CT scans we used as input to our GAN are taken from to open data sets:
- https://www.kaggle.com/luisblanche/covidct
- https://github.com/ieee8023/covid-chestxray-dataset

We trained the model for about 13500 epochs with some for us pretty good result. An animated GIF thats frame are taken every 50 epochs showes the improvements and the instability beyond 6000 epoch (the earlier ones got lost). 

![CT-DCAGAN-GIF](dcgan.gif)

