# ISAnet
Current unsupervised denoising methods overlook signal sparsity, suffering from redundant parameters, low interpretability, weak noise suppression and severe signal leakage. This paper proposes ISANet, an unsupervised denoising network based on interpretable sparse attention U-Net. 
## Main file

This model consists of the following components:
- Data module：`seis2dsyn.mat`, `seis3dsyn.mat`, `real2d.mat`, `real3d.mat`
- Code module：ISANET network and PatchUnet network, corresponding to `ISANET xx.ipynb` and `PatchUnet xx.ipynb` respectively.The `zzlb xx.ipynb` file contains the median filtering codes, which correspond to the four datasets separately.
- Visualization module：`Visualization.ipynb` for the visualization of network parameters.
