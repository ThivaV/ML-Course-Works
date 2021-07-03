# Anaconda Environment Configuration

---

**List all the available environment**

```python
conda env list
```

**Activate an environment**

```python
conda activate <ENV_NAME>
```

<!-- Blockquote -->

**Create conda environment with python 3.8**

> Eventhough a specific version of python installed in your machine, We can create a python environment with other versions

```python
conda create -n <env_name> python=3.8
```

<!-- Blockquote -->

**Show available conda environments**

```python
conda env list
```

<!-- Blockquote -->

**Activate the created environment**

```python
conda activate <env_name>
```

<!-- Blockquote -->

**Install packages to that environment**

<!-- Code Block -->

```python
pip install matplotlib
pip install pandas
pip install numpy
pip install tensorflow
pip install scikit-learn
pip install keras
pip install seaborn
pip install plotly
pip install scipy
pip install xgboost
pip install statsmodels
pip install opencv-python
pip install torch
pip install jupyterthemes
```

> We using the python environment py38TF24.yml for this project