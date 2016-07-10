Autoencoders
============

This repository is a Torch version of [Building Autoencoders in Keras](http://blog.keras.io/building-autoencoders-in-keras.html), but only containing code for reference - please refer to the original blog post for an explanation of autoencoders. The following models are implemented:

- **AE**: Fully-connected autoencoder
- **SparseAE**: Sparse autoencoder
- ~~**CAE**: Contractive autoencoder *(bonus)*~~
- **DeepAE**: Deep (fully-connected) autoencoder
- **ConvAE**: Convolutional autoencoder
- **UpconvAE**: Upconvolutional autoencoder - also known by [several other names](https://github.com/torch/nn/blob/master/doc/convolution.md#spatialfullconvolution) *(bonus)*
- **DenoisingAE**: Denoising (convolutional) autoencoder
- ~~**Seq2SeqAE**: Sequence-to-sequence autoencoder~~
- **VAE**: Variational autoencoder
- **AdvAE**: Adversarial autoencoder *(bonus)*

There models 

Requirements
------------

The following luarocks packages are required:

- mnist
- rnn (for Seq2SeqAE)
- dpnn (for VAE)

Todo
----

- Use dpnn for DenoisingAE with WhiteNoise and Clip
- Build visualisations