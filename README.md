pyrnn
=====

Python bindings for RNNLIB

Alex Graves, RNNLIB: A recurrent neural network library for sequence learning problems

http://sourceforge.net/projects/rnnl/

To make RNNLIB, cd to RNNLIB/

You will need to verify that your system has the necessary tools for building
RNNLIB, I have added a get_prereqs_ubuntu.sh script that should download the
correct libraries for Ubuntu 13.04. Instructions for other OSes are welcome.

Now run the following commands in the RNNLIB/ directory.

./configure

make

Once the library is complied, the examples in RNNLIB/examples/ should be usable.
You may need to install netcdf4, numpy, and scipy.

pip install netcdf4 numpy scipy
