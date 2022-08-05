# Install guide


#### Access the nas164 storage


#### Log in the abs

#### Install Virtualenv

    pip install virtualenv

#### Setting Virtualenv

    virtualenv venv --python=python3.7

#### Virtualenv Environment Setup

    python3.7 -m pip install -upgrade pip
    python3.7 -m pip install torch torchvision torchaudio
    python3.7 -m pip install dgl-cu102 dglgo -f https://data.dgl.ai/wheels/repo.html
    python3.7 -m pip install cppyy


