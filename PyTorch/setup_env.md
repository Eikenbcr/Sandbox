# Instructions to setup PyTorch environment on Anaconda  
1.) Create venv in Sandbox Repo
```
python -m venv pytorch_env
```  
2.) Activate venv 
```
.\pytorch_env\Scripts\activate
```
  
3.) Install Torch and dependencies
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
```
  
4.) Install pandas
```
pip install pandas
```
  
5.) Install matplotlib
```
pip install matplotlib
```
  
7.) Deativate venv
```
.\pytorch_env\Scripts\deactivate
```

  
8.) In VSCode, press CTRL + SHIFT + P to open Python Commands
  
9.) Select 'Python:Select Interpreter'

10.) Select 'pytorch_env' from the list

The pytorch_env should now be loaded in VSCode. You can open .ipynb files and run them within VSCode. You will also need to install some Jupyter and iPython dependencies. These will be automatically installed when you load the pytorch_env Kernel in the .ipynb file.
