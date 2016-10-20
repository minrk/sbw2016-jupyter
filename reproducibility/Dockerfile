# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.

# minimal notebook image from Oct 13 2016
FROM jupyter/minimal-notebook:23dbbebddc3d

RUN conda install -y -c r r-irkernel rpy2

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

RUN git clone https://github.com/minrk/sbw2016-jupyter
