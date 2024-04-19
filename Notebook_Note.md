##在jupyter notebook中添加anaconda虚拟环境

conda activate myenv

conda install ipykernel

python -m ipykernel install --user --name=myenv

启动 Jupyter Notebook。在 Notebook 中，您应该能够在 Kernel 菜单下看到 myenv 作为一个选项
