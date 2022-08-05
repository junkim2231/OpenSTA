# Install guide


### Add to server IP

#### Access the NAS and enter the IP of the server
    
    sudo vi /etc/exports/
  
####   Enter the appropriate server and insert the NAS's IP and path
  
    sudo mount -t nfs (IP_Add):/volume1/supersusers/ /nas164/

#### Access the nas164 storage

#### Log in the abs

#### 1. Install Virtualenv

    pip install virtualenv

#### 2. Setting Virtualenv

    virtualenv venv --python=python3.7

#### 3. Start Virtualenv

    source ./venv/bin/activate

#### Virtualenv Environment Setup

    python3.7 -m pip install -upgrade pip
    python3.7 -m pip install torch torchvision torchaudio
    python3.7 -m pip install dgl-cu102 dglgo -f https://data.dgl.ai/wheels/repo.html
    python3.7 -m pip install cppyy


