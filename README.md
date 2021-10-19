# audio_udl
A general audio embedding model for the HEAR 2021 challenge. 
In short, the model uses a modified BERT transformer and CNN encoder (like wav2vec 2), with a special head and loss formulation to learn from unlabeled audio.

## Installation
The package is installed with `python -m pip install <this repo path>` . 

If that does not work out of the box, it might mean that you don't have the right cuda drivers of some kind of another.
If CUDA and cuDNN versions are giving one problems, then consider installing pytorch and associated CUDA drivers seperately.
Concretely, here are the versions of pytorch and cuda toolkit (as conda packages) that should work:
- `torch==1.9.1`
- `cudatoolkit=11.3.1`
- `cudnn=8.2.1=cuda11.3_0`

Other packages are much simpler and should be installed automatically during package installation.

## Trained model weights
The trained weights are available as a github release on this repository. Namely, [TODO link] provides the checkpoint for the trained model. 

## Questions & Troubleshooting
If there are any questions or problems, please raise a github issue on this and I'll attend to it as soon as possible.
