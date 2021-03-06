[![Build Status](https://travis-ci.org/ebranlard/welib.svg?branch=master)](https://travis-ci.org/ebranlard/welib)
<a href="https://www.buymeacoffee.com/hTpOQGl" rel="nofollow"><img alt="Donate just a small amount, buy me a coffee!" src="https://warehouse-camo.cmh1.psfhosted.org/1c939ba1227996b87bb03cf029c14821eab9ad91/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4275792532306d6525323061253230636f666665652d79656c6c6f77677265656e2e737667"></a>

# welib

Wind energy library, suite of matlab and python tools.


See also:

- [weio](http://github.com/ebranlard/weio/) library to read and write files used in wind energy

- [pyDatView](http://github.com/ebranlard/pyDatView/): GUI to visualize files (supported by weio) and perform analyses on the data



# Installation and testing
```bash
git clone --recurse-submodules http://github.com/ebranlard/welib
cd welib
python -m pip install -r requirements.txt
python -m pip install -e .
pytest
```


# Examples
Check out the examples folder for examples. Some are listed below:

- Manipulation of airfoil curves (see `welib\airfoils\examples\`)
- Dynamic stall model by Oye and Morten Hansen (see `welib\airfoils\examples\`)


# Libraries

- Airfoils: polar manipulations, dynamic stall models
- BEM: steady and unsteady bem code



# Contributing
Any contributions to this project are welcome! If you find this project useful, you can also buy me a coffee (donate a small amount) with the link below:


<a href="https://www.buymeacoffee.com/hTpOQGl" rel="nofollow"><img alt="Donate just a small amount, buy me a coffee!" src="https://warehouse-camo.cmh1.psfhosted.org/1c939ba1227996b87bb03cf029c14821eab9ad91/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4275792532306d6525323061253230636f666665652d79656c6c6f77677265656e2e737667"></a>
