# sage_installation
All commands  in one place for building sagemath on Ubuntu.  


SageMath official website

http://www.sagemath.org

For any  doubts  refer to the following  page.

http://doc.sagemath.org/html/en/installation/source.html#system-specific-requirements


All commands  :
-----

# Installation of pre-requisites

```sudo apt-get install binutils pixz gcc g++ gfortran make m4 perl tar \
  git patch openssl libssl-dev libz-dev bc libbz2-dev liblzma-dev libgmp-dev \
  libffi-dev libgf2x-dev libcurl4-openssl-dev curl yasm


sudo apt install texlive ffmpeg dvipng imagemagick  openssh-server openssh-client  tk tk-dev```


# Change x.y in the following to the specific version
-----

```tar xvf sage-x.y.tar

cd sage-x.y

make -jN #  N is the number of cores

./sage -i pyopenssl```

# Create link 

```ln -s /path/to/sage-x.y/sage /usr/local/bin/sage```

# Using  via jupyter

```./sage  -n  jupyter```


jupyter notebook```
