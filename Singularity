Bootstrap: docker

From: continuumio/miniconda3

%files
    environment.yml

%post
    /opt/conda/bin/conda env create -f environment.yml

%runscript
    exec /opt/conda/envs/challenge-engine/bin/python