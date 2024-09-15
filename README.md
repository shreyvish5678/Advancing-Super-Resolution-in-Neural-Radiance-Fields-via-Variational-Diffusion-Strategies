# Installation

```bash
git clone https://github.com/shreyvish5678/Advancing-Super-Resolution-in-Neural-Radiance-Fields-via-Variational-Diffusion-Strategies
cd Advancing-Super-Resolution-in-Neural-Radiance-Fields-via-Variational-Diffusion-Strategies

conda create --name nerf-sr-vsd
conda activate nerf-sr-vsd

pip install -r requirements.txt
```
Please look through the following projects and install their dependencies as well: [pytorch3d](https://github.com/facebookresearch/pytorch3d), [tinycudann](https://github.com/NVlabs/tiny-cuda-nn), and [threestudio](https://github.com/threestudio-project/threestudio)

# Running

Configure everything in your config file, such as `path/to/config.yaml`, such as dataset directory, the method you want to utilize, and hyperparameters, and then run the following:
`python launch.py --config path/to/config.yaml --train`

The testing and training results should both be generated.
