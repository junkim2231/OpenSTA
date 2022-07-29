# OpenSTA

## Setup

It's a repository of contents that I studied to do research

#### 1. install Virtualenv
    sudo pip install virtualenv
    
#### 2. Settings Virtualenv
    sudo virtualenv venv --python=python3.7
    
#### 3. Install OpenSTA 
 Access the link below and you'll find an installation guide for OpenSTA.
 
 [OpenSTA Setup](https://github.com/jaeyongchung/OpenSTA/blob/KKA/README_dataset.md)
  
#### 4. Virtual Environment Setup 

    python3.7 -m pip install -upgrade pip
    python3.7 -m pip install torch torchvision torchaudio
    python3.7 -m pip install dgl-cu102 dglgo -f https://data.dgl.ai/wheels/repo.html
    python3.7 -m pip install cppyy
    
    
#### 5. Setting VLSI Gate Sizing with ML 
##### OpenSTA path needs to be reestablished.

    vim staev.py
    vim datadump.py
    
Change shared_libsd in stave.py to build.  
    
#### 6. Check 
    python3 ./OpenSTA/build/STA_example.py 
    python3 ./VLSI-gate-sizing-with-ml/datadump.py
    
***

### Error

#### Error1.
Problem: you Can't find the Header.h (Python3.6 or 3.7)

Solution: Check the version problem (Python3.6 or 3.7)

    vim ./CMakeLists.txt
    
    
    

