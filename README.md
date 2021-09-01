# Simple Machine Learning Exercises

# How to Run

1. Run a virtual environment with its requirements:
```
$ sudo apt install python3-pip
$ pip3 install virtualenv
$ sudo apt install python3-virtualenv
$ virtualenv myenv
$ source myenv/bin/activate
$ pip3 install -r requirements.txt
```

2. With the virtual environment running, set the a new kernel for Jupyter:
```    
$ python3 -m pip install ipykernel
$ ipython kernel install --user --name=myenv
$ jupyter-notebook
```
