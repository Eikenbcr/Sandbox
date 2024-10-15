# Instructions to setup PyTorch environment on Anaconda  
1.) Open the Anaconda Prompt
  
2.) Update the Anaconda install
```
conda update --all
```
  
3.) Create pytorch environment
```
conda create --name pytorch
```
  
4.) Activate the new environment
```
conda activate pytorch
```
  
5.) Install PyTorch with conda
```
conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia
```
  
6.) Install matplotlib for data visualization
```
conda install matplotlib
```
  
7.) Install plotly for data visualization
```
conda install plotly
```
  
8.) Install seaborn for data visualization
```
conda install plotly
```
  
9.) Open Anaconda Navigator and select the <i> pytorch </i> environment on the homepage
  
10.) Press the <i> Install </i> button for Jupyter Notebook

You now have an environment called <i> pytorch </i> in the Anaconda Navigator that can be launched with Jupyter Notebook
