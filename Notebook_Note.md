## 在jupyter notebook中添加anaconda虚拟环境

创建一个虚拟环境myenv或者选择已有环境

激活环境conda activate myenv

conda install ipykernel

python -m ipykernel install --user --name=myenv

启动 Jupyter Notebook。在 Notebook 中，您应该能够在 Kernel 菜单下看到 myenv 作为一个选项

创建虚拟环境：python3 -m virtualenv name-venv
