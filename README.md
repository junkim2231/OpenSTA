# OpenSTA

# Preparation process for code execution

It's a repository of contents that I studied to do research

#### 1. install Virtualenv
    sudo pip install virtualenv
    
#### 2. Settings Virtualenv
    sudo virtualenv venv --python=python3.7
    
#### 3. Install OpenSTA 
 Access the link below and you'll find an installation guide for OpenSTA.
 https://github.com/jaeyongchung/OpenSTA/blob/KKA/README_dataset.md
  
#### 4. Virtual Environment Preparation Process

    python3.7 -m pip install -upgrade pip
    python3.7 -m pip install torch torchvision torchaudio
    python3.7 -m pip install dgl-cu102 dglgo -f https://data.dgl.ai/wheels/repo.html
    python3.7 -m pip install cppyy
    python3.7 ./OpenSTA/build/STA_example.py 

***

### Error

#### Error1.
Problem: you Can't find the Header.h

Solution: Check the version problem

    vim ./CMakeLists.txt
    
    
    

