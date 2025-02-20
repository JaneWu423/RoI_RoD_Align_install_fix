# RoI_RoD_Align_install_fix
A fix to roi_align and rod_align installation

Worked with Pytorch 2.6.0, Python 3.10, and CUDA 12.4 on Ubuntu 22.04

# Installation

First, go into the ```make.sh``` in both ```rod_align``` and ```roi_align``` directory, change the CUDA_HOME to your own cuda installation directory (usually /usr/local/bin). Also change the ```-arch=``` to match your own GPU arch in the ```nvcc``` command.

Then, go back to top level and run command ```bash make_all.sh```.
