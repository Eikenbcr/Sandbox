# Instructions to setup PyTorch environment on Anaconda  
1.) Open the Anaconda Prompt
  
2.) Update the Anaconda install
```
conda update --all
```
  
3.) Create pytorch environment
```
conda create --name skorch
```
  
4.) Activate the new environment
```
conda activate skorch
```
  
5.) Install PyTorch with conda
```
conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia
```

6.) Install skorch for scikit support
```
conda install -c conda-forge skorch
``` 

7.) Install matplotlib for data visualization
```
conda install matplotlib
```
  
8.) Install plotly for data visualization
```
conda install plotly
```
  
9.) Install seaborn for data visualization
```
conda install seaborn
```
  
10.) Open Anaconda Navigator and select the <i> skorch </i> environment on the homepage
  
11.) Press the <i> Install </i> button for Jupyter Notebook

You now have an environment called <i> skorch </i> in the Anaconda Navigator that can be launched with Jupyter Notebook
