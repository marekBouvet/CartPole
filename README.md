# Install

Installer environmentet med

```pwsh
conda create -n reinforcement python=3.10
conda activate reinforcement
conda install --file requirements.txt
pip install pygame==2.1.2
pip install Gymnasium==0.26.3
jupyter notebook
```

## dependencies

You need to have swig installed before you install box2d, which by the way cannot be directly installed. It is a c/c++ trasnformer so high level languages like python can talk to programs written in c/c++.  
Install box2d from the github release:

```zsh
pip install https://github.com/pybox2d/pybox2d/archive/refs/tags/2.3.10.tar.gz
```
