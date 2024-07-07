# opencv_build_conda_orin


Use this script to build OpenCV from source on an NVIDIA Jetson Orin, in a conda envrionment. 

Building OpenCV from source, allows to enabled OpenCV with Gstreamer.

Remeber to downgrade libffi if you get problems importing OpenCV with: 

conda install libffi==3.3
