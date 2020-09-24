## 



### Installation

Followed the installation instructions for developers, in case changes to the code are needed
```
conda activate coffea
pip install flake8 pytest coverage
git clone https://github.com/BParkHNLs/coffea.git
cd coffea
pip install --editable .
```

Working on a stable version, v0.6.44 for now. Later update will have to be pulled in our fork
```
git checkout -b ver0644 b531e529c64b446efd694917b69dd17e8c087fe1
```


### Notebooks
To run a jupyter notebook:
```
jupyter notebook --port 8883 --no-browser
```
To display the notebook on your lapton browser
```
ssh -N -f -L localhost:8883:localhost:8883 t3ui02.psi.ch
http://localhost:8883/tree
```
copy and paste one of the provided links

