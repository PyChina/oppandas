# oppandas
> optimization pandas demo case


## Jupyter
conda update -n base -c defaults conda
conda search "^python$"

jupyter notebook --generate-config
>>> jupyter notebook password

conda create -n myenv python=3.8
conda env remove --name py3122

༼…/oppandas ༽on  main [!?] via 🅒 py3122 

conda install matplotlib pandas jupyter

conda install -c conda-forge webcolors uri-template jsonpointer jsonschema isoduration fqdn 
conda install -c conda-forge jupyter_contrib_nbextensions 

conda install -c conda-forge jupyterthemes 

conda install -c conda-forge jupyter-resource-usage 

conda install memory_profiler
from memory_profiler import profile as mprof

jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user

𝄢 conda install -c conda-forge jupyterthemes

import jupyterthemes as jt
!jt -t solarizedl -T -N -kl