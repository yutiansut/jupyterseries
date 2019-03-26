sudo /home/quantaxis/anaconda3/bin/pip install jupyter_contrib_nbextensions  -i https://pypi.doubanio.com/simple

jupyter contrib nbextension install –system


sudo /home/quantaxis/anaconda3/bin/pip install jupyterhub-ldapauthenticator


/home/quantaxis/anaconda3/bin/pip install git+https://github.com/jupyterhub/kubespawner.git

sudo /home/quantaxis/anaconda3/bin/jupyter labextension install @oriolmirosa/jupyterlab_materialdarker

sudo /home/quantaxis/anaconda3/bin/jupyterhub -f jupyterhub_config.py  --no-ssl

export PATH=/root/anaconda3/bin:$PATH