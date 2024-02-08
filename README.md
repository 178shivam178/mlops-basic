create env

```bash
conda create -n mlops-main python=3.8 -y
```
activate env

```bash
conda activate mlops-main
```
created a req file
install the req

```bash
pip install -r requirements.txt
```
download the data from

https://drive.google.com/drive/u/0/folders/1hZImF3u05t4dgEjDg8edhcFrdSpBf9vl

```bash
git init
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add . && git commit -m "update Readme.md"
```

```bash
git remote add origin https://github.com/178shivam178/mlops-basic.git
git branch -M main
git push origin main
```