# CP2K-compiled

Compiled CP2K

## Packages included

As [install](https://github.com/cp2k/cp2k/blob/master/INSTALL.md) stated, there are several
packages needed to be install before compiling the CP2K.
Some are included in this compiling:

* FFTW
* libint
* libxc
* libsmm
* libxsmm
* spglib

Noted that Intel(R) MKL replace blas/lapack, blacs/scalapack so they are not needed


And some are not included:

* CUDA
* ELPA
* PEXSI
* QUIP
* PLUMED
* SIRIUS
* FPGA

If you want to use part of these packages, you have to compile yourself.



## Installation

If the program ends with .gz, then `gzip -d $FILENAME` do uncompress it and run.



## cp2k.7.0_centos.7.6.1810_intel.18.0.0_glibc.2.17-260.popt

* cp2k: 7.0 (git:c67de69)  (Sep 30, 2019)
* OS: centos.7.6.1810
* compiler: intel 18.0.0
* env: intel 18.0.0
* glibc 2.17-260



## cp2k.7.0_ubuntu.16.04_intel.18.0.0_glibc.2.27.popt

* cp2k: 7.0 (git:c67de69)  (Sep 30, 2019)
* OS: ubuntu.16.04
* compiler: intel 18.0.0
* env: intel 18.0.0
* glibc 2.27



