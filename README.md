# Anaconda
condaに関する備忘録


#### 仮想環境一覧
```
conda info --envs
```
#### 仮想環境の作成
```
conda create -n env_name libraries
```
#### 仮想環境の削除
```
conda remove -n myenv --all
```

#### プロキシ設定の確認
```
conda config --show
```

#### conda のアップデート
```
conda update -n base -c defaults conda
```

#### 最初の設定
```
conda init bash
```

-----------------
## scVeloのための環境構築
```
conda create -n scVelo python=3.8.16 scvelo notebook
conda activate scVelo

pip install pybind11 hnswlib
pip install python-igraph louvain
conda install -c anaconda openpyxl
```

-----------------
## velocytoのための環境構築 （遺伝研スパコン 24/1/10）
velocyto installation guide ->   http://velocyto.org/velocyto.py/install/index.html
```
conda create -n velocyto python=3.9.16
conda activate Velocyto

conda install numpy scipy cython numba matplotlib scikit-learn h5py click
pip install velocyto
```
