I've been having trouble importing tensorflow into jupyter notebooks in pycharm

https://intellij-support.jetbrains.com/hc/en-us/community/posts/360000905459-Selecting-custom-specified-kernel-in-Jupyter-Notebook-using-Pycharm

Change "myenv" to your python environment name below.  This seems to properly set some kind of configuration...

source activate myenv
python -m ipykernel install --user --name myenv --display-name "Python 3.11 (intro_to_linear_algebra)"
Got it from:

https://stackoverflow.com/questions/39604271/conda-environments-not-showing-up-in-jupyter-notebook
