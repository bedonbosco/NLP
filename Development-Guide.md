# Getting Started

Install gcc g++

```
apt-get update
apt-get install gcc g++
```
Install anaconda 2 - 4.4.0 

```
apt-get update --fix-missing && apt-get install -y wget bzip2 ca-certificates \
  libglib2.0-0 libxext6 libsm6 libxrender1 \
  git mercurial subversion
echo 'export PATH=/opt/conda/bin:$PATH' > /etc/profile.d/conda.sh && \
  wget --quiet https://repo.continuum.io/archive/Anaconda2-4.4.0-Linux-x86_64.sh -O ~/anaconda.sh && \
  /bin/bash ~/anaconda.sh -b -p /opt/conda && \
  rm ~/anaconda.sh
```

Create environment

```
conda create -n underthesea python=3.4
source activate underthesea
pip install tox
conda install virtualenv
```

Run tests

```
git clone https://github.com/magizbox/underthesea
tox
```