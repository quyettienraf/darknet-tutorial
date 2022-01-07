## 1. link git
```bash
https://github.com/AlexeyAB/darknet
```
clone git
```bash
git clone https://github.com/AlexeyAB/darknet.git
```
## 2. check CUDA version
```bash
nvidia-smi
```
## 3. Check cuDNN version
```bash
nvcc --version
```
if you install cuDNN
```bash
sudo apt install nvidia-cuda-toolkit
```
Check where your cuda installation is
```bash
which nvcc
```
## 4. Install libopencv-dev
```bash
sudo apt-get update -y
sudo apt-get install -y libopencv-dev
```
run ``` make ``` in darnet directory
