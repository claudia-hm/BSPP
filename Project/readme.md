# Final project: Bayesian Logistic Regression 

## How to run the code
  1. Create (```virtualenv <name>```) and activate (```source <name>/bin/activate```) your virtual environment. 
  2. Install all the required packages with ```pip install -r requirements.txt```
  3. Create jupyter kernel from your virtual environment with the command ```ipython kernel install --user --name=<name>```
  4. Open Jupyter as usual, and change your kernel to ```<name>```
  5. To delete your new kernel use ```jupyter-kernelspec uninstall <name>```
  
  Also, to use pystan inside jupyter notebook we need to paste this cell at the beginning of your notebook 
  ```
  import nest_asyncio
  nest_asyncio.apply()
  del nest_asyncio
  ```
  Please, run the notebook 'Testing pystan 3.4.0.ipynb' to check that everything is working.
