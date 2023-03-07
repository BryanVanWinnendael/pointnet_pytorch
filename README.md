# Python 3.7.16

This is a windows installation of [Pointnet.pytorch](https://github.com/fxia22/pointnet.pytorch).

# Installation

## WSL:

https://itsfoss.com/install-bash-on-windows/#:~:text=Bash%20on%20Windows%20provides%20a,shell%20you%20find%20on%20Linux.

```bash
sudo apt install g++
```

## Install data:

https://shapenet.cs.stanford.edu/ericyi/shapenetcore_partanno_segmentation_benchmark_v0.zip
and unzip in /scripts

## Install python packages:

```bash
pip install -r requirements
pip install torch -f https://download.pytorch.org/whl/torch_stable.html
```

## Install CUDA:

install CUDA https://developer.nvidia.com/cuda-downloads

## Build:

In /utils

```bash
bash build.sh
```

# Usage

In /utils

```bash
python train_segmentation.py --dataset path_to_shapenetcore_partanno_segmentation_benchmark_v0 --nepoch=num --workers=0
```

```bash
python train_segmentation.py --dataset path_to_shapenetcore_partanno_segmentation_benchmark_v0 --nepoch=num --workers=0
```
