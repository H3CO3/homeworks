# ## Install 下载Python和IDE 
Windows直接exe一路点下一步安装, 注意：永远不建议使用最新版本    
[windows64-Python3.9-exe][https://www.python.org/ftp/python/3.9.12/python-3.9.12-amd64.exe], 或者[官网下载](https://www.python.org/downloads/)  
附cmd命令行检测安装成功的方法: 
```bash
python --version
```
如果不想用命令行跑的话永远建议整个VS Code  
[官网下载](https://code.visualstudio.com/)  
打开.py文件右下角会自动弹出是否下载python扩展包的提示，或者左边工具栏打开扩展包目录(ctrl+shift+x)，搜索python下载扩展包(就叫Python，什么Python Extension Pack, Python Environment暂时不用管)  

## Library 库
命令行使用pip下载包
```bash
pip install (lib)
```
常用库：numpy, matplotlib, pandas, tensorflow, torch

## Debug 编译
如果是.py文件后缀名的程序：  
1. VS Code 快捷键F5开始debug，弹出来的Debug Configuration选Python File  
2. 或者直接命令行：
```bash
python (your file)
```
如果是Notebook：  
首先下载一下notebook环境：
```bash
pip install notebook
```
1. 然后用IDE打开notebook
2. 或者用默认浏览器打开：
```bash
jupyter notebook (your file)
```

## Machine Learning Beginning 机器学习起步
[sklearn官网api (推荐)](https://scikit-learn.org/stable/modules/classes.html)
```bash
pip install scikit-learn scipy matplotlib
```
[Tensorflow官网教程](https://www.tensorflow.org/tutorials/quickstart/beginner)  
```bash
pip install tensorflow
```
或者看本notebook
```
