# SSD-GS: Scene-Guided Diffusion Priors for Static-Dynamic Decoupling in Gaussian Reconstruction of Driving Scenes.
The code is coming soon!

### [Project](https://github.com/halfaMango/SSD-GS)     |     [Paper](https://github.com/halfaMango/SSD-GS)
## Requirements
We test our code on Ubuntu 20.04 using Python 3.10 and PyTorch 2.2.0. We recommend using conda to install all the independencies. 


1. Create the conda environment and install requirements. 

```
# Clone the repo.
git clone https://github.com/chengweialan/DeSiRe-GS.git
cd DeSiRe-GS

# Create the conda environment.
conda create -n DeSiReGS python==3.10
conda activate DeSiReGS

# Install torch. 
pip install torch==2.2.0 torchvision==0.17.0 --index-url https://download.pytorch.org/whl/cu118 # replace with your own CUDA version

# Install requirements.
pip install -r requirements.txt
```

2. Install the submodules. The repository contains the same submodules as [PVG](https://github.com/fudan-zvg/PVG).

```
# Install simple-knn
git clone https://gitlab.inria.fr/bkerbl/simple-knn.git
pip install ./simple-knn

# a modified gaussian splatting (for feature rendering)
git clone --recursive https://github.com/SuLvXiangXin/diff-gaussian-rasterization
pip install ./diff-gaussian-rasterization

# Install nvdiffrast (for Envlight)
git clone https://github.com/NVlabs/nvdiffrast
pip install ./nvdiffrast
```
## Train
## Inference
## Citation
## Acknowledgements
