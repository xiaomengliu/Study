```
### setup fastai conda environment in vs code on my macbook
### fastai support python <= 3.11
### fastai support numpy <= 1.23
### run in the terminal

conda create -n fastai python=3.11.13 
conda activate fastai 
conda install ipython  
conda install -c fastai -c pytorch fastai
conda install numpy=1.23.5 --force-reinstall

### 查看当前工作目录
import os
print(os.getcwd())
```
