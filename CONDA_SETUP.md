```sh
conda create -n skimtut
conda activate skimtut
conda install python scikit-image
conda install jupyterlab jupytext -c conda-forge
#if not already set up in base environment:
#conda install -n base -c conda-forge widgetsnbextension
conda install ipywidgets
cd $HOME/.vim
mkdir plugin
cd plugin
wget https://raw.githubusercontent.com/goerz/jupytext.vim/master/plugin/jupytext.vim
```
