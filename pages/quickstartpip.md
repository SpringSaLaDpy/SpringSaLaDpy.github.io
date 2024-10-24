---
title: Command line Python
layout: default
permalink: quickstartpip
---

# Quickstart Guide for command line Python
### Use SpringSaLaDpy, not springsaladpy!!!
 
* Download and install [Anaconda Distribution](https://www.anaconda.com/products/distribution) for Python

* Open terminal and type:

```python
pip install SpringSaLaDpy
```
* Create a working directory, where you cloned/copied [https://github.com/SpringSaLaDpy/SpringSaLaDpy_demo/](https://github.com/SpringSaLaDpy/SpringSaLaDpy_demo/).

* Using the terminal, navigate to the working directory and type 

 ```python
import SpringSaLaDpy
python analysis.py
```
or

 ```python
python simulate.py
```

Due to the system configuration, in some cases, you may need to type

```python
python3 ....py
```

* The script should sequentially import the package, run multiple analysis tools, analyze and visualize the data

* **Note**: when you run python from the terminal, the figures will appear one after the other, that is, the second figure is displayed only after you close the first figure and so on. If you run python from an IDE like [Spyder](https://www.spyder-ide.org/), all the figures are sequentially displayed, just like the jupyter notebook. 

* Change the simulation parameters and visualize the results


#### Terminal Output and Results

The outputed results will be found in ...  There are the following outputs: 

- aaa
- bbb


#### Locating Package Through Command Line

If you need to find the location of the package
- open terminal
- open python and type

```python
import SpringSaLaDpy
print(SpringSaLaDpy.__file__)
```
This will output a path to the package that will look something like this

```python
/usr/local/lib/python3.10/site-packages/SpringSaLaDpy/__init__.py
```



