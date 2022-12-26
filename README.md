# Generating Sounds with Neural Network
The project was build using Vanilla Autoencoder and its updated version variational Autoencoder(VAE)from Scratch. Mnist Dataset was tested on vanilla Autoencoder
and then a dataset of spoken digits from 0-9 was used and generated using VAE ![spoken digits](https://github.com/Jakobovski/free-spoken-digit-dataset)


Technology used to in this project are python, librosa(audio processing library), Tensorflow, Keras. The target of this project was to generate sound through Latent Space representation. For testing purpose dataset consisting of spoken digits from 0-9 was used and reconstructed through a VAE based architecture. Sound can be used as raw-audio or in the form of Spectrograms. As in the work done WaveNet: (https://arxiv.org/abs/1609.03499) where a raw audio was used to generate sound. Some Challenges to generate sound from raw audio are Difficult to capture long-range dependencies like pitch, Melody, Rhythm, Timbre, Harmony, Structure. Also, it is computationally expensive and generation is slow

