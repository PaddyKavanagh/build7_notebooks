# build7_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (build 7) for MIRI data within python. 

Build 7 of the JWST calibration pipeline can be installed into an Anaconda environment as follows:

conda create -n jwstb7 --file <URL>

where <URL> is for Linux and OSX, respectively:

http://ssb.stsci.edu/conda/jwstdp-0.7.0rc/jwstdp-0.7.7-linux-py27.0.txt

http://ssb.stsci.edu/conda/jwstdp-0.7.0rc/jwstdp-0.7.7-osx-py27.0.txt

The CRDS context should be set to jwst_0303.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0303.pmap"

