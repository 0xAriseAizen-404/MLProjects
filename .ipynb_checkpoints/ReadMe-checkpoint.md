# Creating Virtual Environment

### Using Python PIP

```python
cd ~/Documents/Code/ProjectName
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windowsz
```

```python
pip install flask
pip list
pip freeze > requirements.txt
pip install -r requirements.txt
```

```python
deactivate
```

### Using Conda

```python
cd ~/Documents/Code/ProjectName
conda create --prefix ./env python=3.10 # local
conda activate ./env -> activate

conda create -n env python=3.10 # global -> /home/mrx/miniconda3/envs
```

```python
conda deactivate
```

```python
conda config --set env_prompt '({name})' # if prefix is long then use this
```

```python
pip install flask # Use This ONE

conda install flask # install packages not recommeneded as it install those Lib Packages -> use PIP
conda list
```

```python
conda env export > environment.yml # export all types of packages like Lib, Conda, Pip

conda env export --from-history > environment.yml # only export installed packages through conda
```

```python
conda env create --prefix ./env -f environment.yml # Local -> similar like pip install -r requirements.txt - do inside activated env

conda env create -f environment.yml # Global

conda env update -f environment.yml --prune
```
