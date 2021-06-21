```sh
conda create -n skimtut
conda activate skimtut
conda install python scikit-image
conda install jupyterlab jupytext -c conda-forge
cd $HOME/.vim
mkdir plugin
cd plugin
wget https://raw.githubusercontent.com/goerz/jupytext.vim/master/plugin/jupytext.vim
```
