# Contrastive pointclouds
Project for DLAI 2022 at La Sapienza, playing around with contrastive learning and 3d shapes. 

### How to run

Either use Colab or install pytorch and the other dependencies (Pytorch geometric). 
Note that there are 2 versions of the code:
- v1: original version in folder v1 (with pretrained models, saved in a generic format)
- v2: new version, rewritten to work with WANDB 

Note that the second version requires a WANDB account to work and visualize all the graphs. If everything is done correctly, you should see something like this:

![tmp](https://user-images.githubusercontent.com/25869148/189383000-8a69cecc-96bc-4176-b12e-88c2179a074e.png)

### Code attributions

Here are listed code attributions for the notebooks:
- pytorch geometric tutorials: https://pytorch-geometric.readthedocs.io/en/latest/notes/colabs.html
- wandb pytorch integration: https://colab.research.google.com/github/wandb/examples/blob/master/colabs/pytorch/Simple_PyTorch_Integration.ipynb#scrollTo=BR_4QqWX_oA3
- pygCL:https://github.com/PyGCL/PyGCL

Note that while no part of pygCL was used in this repository I still used their code to understand common patterns in contrastive training.
All the other relevant attributions are in the report.
