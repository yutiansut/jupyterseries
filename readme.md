# JUPYTER 系列的设置

## 一些常用的命令
```
sudo /home/quantaxis/anaconda3/bin/pip install jupyter_contrib_nbextensions  -i https://pypi.doubanio.com/simple

jupyter contrib nbextension install –system

sudo /home/quantaxis/anaconda3/bin/pip install jupyterhub-ldapauthenticator

/home/quantaxis/anaconda3/bin/pip install git+https://github.com/jupyterhub/kubespawner.git

sudo /home/quantaxis/anaconda3/bin/jupyter labextension install @oriolmirosa/jupyterlab_materialdarker

sudo /home/quantaxis/anaconda3/bin/jupyterhub -f jupyterhub_config.py  --no-ssl

export PATH=/root/anaconda3/bin:$PATH

pip install jupyterthemes
sudo /home/quantaxis/anaconda3/bin/jt -t monokai -f fira -fs 10  -cellw 90% -N

```

## 常见的踩坑指南


1. jupyterhub如果在启动了jupyterlab以后, lab需要给一个config文件来自行配置