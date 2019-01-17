# cond-pgan
### This is part of the code to reproduce the results for the paper "Skin Lesion Synthesis with Generative Adversarial Networks" in ISIC Skin Image Analysis Workshop and Challenge @ MICCAI 2018.

In this repository, we present our modifications to Karras et al. 's [PGAN](https://research.nvidia.com/publication/2017-10_Progressive-Growing-of).
The code is heavily based in the author's original.

To run, clone Karras et al. 's [repository](https://github.com/tkarras/progressive_growing_of_gans), and replace their network.py and loss.py files with ours.
The modifications introduce code to concatenate labels in different layers from both discriminator and generator. Conditional generation benefits from it greatly. 

For more details refer to our paper "Skin Lesion Synthesis with Generative Adversarial Networks" in ISIC Skin Image Analysis Workshop and Challenge @ MICCAI 2018.
