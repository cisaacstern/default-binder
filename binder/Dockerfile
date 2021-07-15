FROM pangeo/pangeo-notebook:2c94acd
RUN /srv/conda/envs/notebook/bin/python -m pip install git+https://github.com/pangeo-forge/pangeo-forge-recipes.git
RUN echo $(which mamba)
RUN mamba install -n notebook -c conda-forge rise ipytree
