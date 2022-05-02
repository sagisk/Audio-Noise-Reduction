# Audio-Noise-Reduction

In this project we are trying to filter out the noise from the input signal while simultaneously avoiding the degrading of the signal quality. For this purposes we are using a U-Net type convolutional autoencoder.
The model is trained on a publicly available audio dataset at https://datashare.ed.ac.uk/handle/10283/2791. The dataset contains 11572 records in the short .wav format. It contains the clean versions of the audio records as well as the corresponding versions of the noisy audio records.

The project has a accompanying article on medium.com written by me: https://medium.com/@sriskandaryan/autoencoders-demystified-audio-signal-denoising-32a491ab023a
