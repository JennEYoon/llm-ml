# My Notes, from Raschka, Build a LLM From Scratch

Book GitHub at https://github.com/rasbt/LLMs-from-scratch

### Setup notes, August 2024:  

Book setup detailed instructions:  
https://github.com/rasbt/LLMs-from-scratch/tree/main/setup  

My notes:  
Python v 3.10 or 3.11 supported   
PyTorch v 2.4.0 stable supported (both gpu and cpu detected)  
Numpy latest 1.x supported, 1.26.4 Feb 2024. v 2.x NOT Supported!  
cuda 12.4 if gpu computer (also supports cuda 11.8, 12.1, 12.4)

Use requirements.txt to install libraries after creating a new miniconda environment.  

1) Create a new miniconda environment named "llm" and python "3.11" version.   
`conda create --name llm python=3.11`  
    my env name is "llm"  
    my python version is "3.11"
Activate new conda env `conda activate llm`  
     

3) Git clone from author's repo to your local repo.
   Change directory to new repo folder.  
```
git clone https://github.com/rasbt/LLMs-from-scratch.git
cd LLMs-from-scratch
```   

3) install rest of python libraries using requirements.txt or individually using conda install.  
`which pip` (to check for correct path)  
`pip install -r requirements.txt`  
OR use conda, `conda install <libr1> <libr2> ...`  




 
