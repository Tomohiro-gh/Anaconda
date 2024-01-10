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


-----------------
## scVeloのための環境構築
```
conda create -n scVelo python=3.8.16 scvelo notebook
```
