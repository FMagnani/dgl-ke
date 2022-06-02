This version is not official. 

Conda **always** installed the **stable** version, even if I was asking for the **latest**!!!  
Therefore, I had to **manually** download the latest into my local directory.  
  
Anyway, it still gave me problems... maybe, being the latest, it had some bugs.  
In any case, since the problematic code was related to things that I did not need at the time (in particular: built-in datasets), I simply **DELETED** it.  
  
If you really need the code related to the built-in datasets (as FB15k-237, FB15K, wiki-something etc) you have two possibilities:  
1- Download them separately and then process them as external datasets (some additional work is needed in this case)  
2- Try to download the latest version and use it (maybe, at the time you are reading this message, all works well finally)  
In particular, I had these problems in March 2022. You can check if the repo has been updated in the meanwhile.  

### How to install this version
For my pc the following works (You can change the name of the env in the first line of `environment.yml`):  
`conda activate NAME`  
`git clone https://github.com/FMagnani/dgl-ke.git`  
`cd dgl-ke/python`  
`python3 setup.py install`  
