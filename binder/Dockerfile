FROM pangeo/pangeo-notebook:2c94acd
RUN /srv/conda/envs/notebook/bin/python -m pip install --no-deps git+https://github.com/pangeo-forge/pangeo-forge-recipes.git
RUN /srv/conda/envs/notebook/bin/python -m pip install --no-deps "rechunker>=0.4.2"
RUN /srv/conda/envs/notebook/bin/python -m pip install "fsspec>=2021.6.0"
RUN /srv/conda/envs/notebook/bin/python -m pip install rich
RUN echo $(which mamba)
RUN mamba install -n notebook -c conda-forge rise ipytree

