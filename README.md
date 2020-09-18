# Notebook for playing around with the SITH neural network later for modeling a gambling task

## Setup Instructions
1) [Install miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) if you don't already have conda
2) [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if you don't already have git
3) Clone this repository: `git clone https://github.com/nimh-comppsych/qm_tutorials.git`
4) Set-up a conda environment and install packages:  
  ```cd qm_tutorials;
     conda create -p ./env python numpy matplotlib pandas scipy jupyter notebook;
     conda activate ./env
     conda install pytorch torchvision -c pytorch
     pip install pyro-ppl
     mkdir code
     cd code
     git clone --single-branch --branch pipify https://github.com/Shotgunosine/SITH_Layer
     pip install -e ./SITH_Layer
     cd ..
```
5) Start a juypter notebook server: `jupyter notebook`
6) Open up the notebooks in the notebooks directory