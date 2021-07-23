# Temporal-Convolution Resnet (Pytorch Ver)
- [Official](https://github.com/hyperconnect/TC-ResNet)  
- [TC-Resnet Paper](https://arxiv.org/pdf/1904.03814.pdf)  
  
Impelmentation of Keyword Spotting Speech Neural Network  
Original repository is tensorflow version  
So, This repository gives you pytorch version  
# Requirements
```
pytorch == 1.8.0 torchaudio == 0.8.0
or
pytorch == 1.9.0 torchaudio == 0.9.0
tqdm
einops
numba == 0.48
librosa == 0.7.2
```
# Setting Enviorments
First, Create conda enviorment
```
conda create -n speech python=3.8
```
Second, Install some packages
```
conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch -c conda-forge
pip install numba==0.48
pip install librosa==0.7.2
pip install tqdm 
pip intsall einops
```
or, You select option
```
conda env create -f pakages.yml
```
# Preparing Dataset
```
bash download.sh
```
# Training model
```
python model_train.py
```