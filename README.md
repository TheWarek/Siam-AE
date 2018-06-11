# Siam-AE

Siamese autoencoder

Cosine distance metrics

Loss = similarity between patches + reconstruction error


usage:
run.py -s <stacks> -d <dataset>( H5PY format only NHWC) -S (to train SAE) -A (to train AE) -n (to include noise in batch)


## Requirements

your own dataset in h5py format (or default on MNIST) :)