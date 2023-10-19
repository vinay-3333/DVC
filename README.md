```
##DVC 
DATA version control
```




```
conda create -y venv python 3.8 -y
source activate ./venv
```

```
git init
```

```
touch .gitignore
touch README.md
touch requirement.txt
```

```
mkdir dvc
cd dvc 
code .
```


```
pip install -r requirement.txt
```

```
dvc init
dvc add 
dvc repro 
dvc dag
```


```
dvc.yaml :-
file have a config which file depend on each other 
dvc repro(command)->dvc.yaml->dvc.lock(output)

dvc.lock file contain all the meta data inside lock file have some hash value those we can track each file 
```