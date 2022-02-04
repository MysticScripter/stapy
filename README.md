# stapy

stapy is a python package that calculates probability distributions based on the Gaussian model 

# installation

To have stapy installed in your machine, adhere to the following:
```
git clone https://github.com/MysticScripter/stapy.git
```
Move into the stapy directory and install the package
```
cd stapy

pip install
```

# usage

If everything is set correctly `pip` installs the stapy package.
start the python interpreter
```
python
```
sample code
```
from stapy import Gaussian

gaussian_one = Gaussian(25, 2)

gaussian_one.mean

gaussian_one + gaussian_one
```
