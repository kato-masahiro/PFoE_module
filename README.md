# PFoE_module  
Implementing a "Particle filter on Episode (PFoE)"
====

### Python module for implementing a PFoE.   
[PFoE algorithm was proposed by Ueda et al. in 2016](https://link.springer.com/chapter/10.1007/978-3-319-48036-7_54) to let robots learn episodic tasks.   
In this repository,the Python module ```pfoe.py``` provides functions for implementing the PFoE algorithm.  

## Install  
#### Obtaining modules  
```
$ git clone https://github.com/kato-masahiro/PFoE_module
```
#### Copy modules  
After cloning , you should to copy the three necessary codes```pfoe.py```,```functions.py```,```likelihood_function.py``` to the directory of your Python project.  
```
$ cd ./PFoE_module
$ cp *.py  << YOUR PROJECT'S DIRECTORY'S PATH >>
```

## Usage  
```pfoe.py``` is the body of this module.  
Likelihood function is defined in ```likelihood_function.py``` then please edit this.  
I showed concrete usage in ```example.py```. please refer to.  
## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[kato-masahiro](https://github.com/kato-masahiro)
