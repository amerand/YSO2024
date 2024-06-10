# [`PMOIRED`](https://github.com/amerand/PMOIRED) live session for [GRAVITY+ YSO workshop](https://gravity-plus-yso2024.sciencesconf.org/?lang=en) 

Clone this repository (or get the [.zip archive](https://github.com/amerand/YSO2024/archive/refs/heads/main.zip)):
```
git clone https://github.com/amerand/YSO2024
cd YSO2024
```

if you already have `PMOIRED`, you still need the latest version (1.2.4, from June 9th 2024). You should install `PMOIRED` in a python environment, so it will not interfere with your current installation:
```
python3 -m venv ./pmoired
source ./pmoired/bin/activate
pip3 install pmoired==1.2.4 jupyterlab ipympl
jupyter-lab
```
after exiting `jupyter-lab`, you can type `deactivate` in the terminal to go back to your default python3 installation. 

