# Deep Learning Demo Projects

A portfolio of hands-on Python projects exploring the building blocks of modern computer vision and deep learning. The code grew out of class projects and coursework; this repository presents the technical work as a progression of experiments, from classical classifiers to generative and multimodal models.

## Project sequence

| Project | Topics | Main code |
| --- | --- | --- |
| [01 · Classical and neural classification](projects/01-classical-and-neural-classification/) | k-nearest neighbors, linear SVM and softmax, image features, fully connected networks, optimization, gradient checking | `classifiers/`, `features.py`, `layers.py`, `optim.py` |
| [02 · Convolutional networks](projects/02-convolutional-networks/) | convolution and pooling, normalization, dropout, CNNs, recurrent models for image captioning | `classifiers/`, `layers.py`, `fast_layers.py`, `rnn_layers_pytorch.py` |
| [03 · Transformers and self-supervision](projects/03-transformers-and-self-supervision/) | attention, transformer classifiers, vision transformers, image captioning, SimCLR-style contrastive learning | `classifiers/transformer.py`, `transformer_layers.py`, `simclr/` |
| [04 · Generative and multimodal models](projects/04-generative-and-multimodal-models/) | denoising diffusion, U-Net, CLIP/DINO feature use, image retrieval and lightweight adaptation | `gaussian_diffusion.py`, `unet.py`, `clip_dino.py` |

## How to explore

Each project directory contains Python implementation modules. Start with the named model or algorithm file, then follow its imports into layers, utilities, and training code. These are educational implementations, not packaged libraries; the original course notebooks, datasets, grading tools, and submission instructions are intentionally excluded.

The code expects common scientific Python and PyTorch packages. Exact dependencies and dataset setup vary by project and hardware, so install only what the implementation you are exploring imports. No datasets or pretrained weights are bundled.


## Scope

The implementations are intended for study and demonstration. Some modules may depend on course-specific data layouts or include incomplete experimental work. Review the relevant file before using it in another project.
