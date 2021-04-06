conda create -n wineq python=3.7 -y

conda activate wineq

touch requirements.txt

pip install -r requirements.txt

touch README.md

touch template.py

python template.py

mkdir data_given

git init

dvc init

dvc add data_given/winequality.csv 

git add .

git commit -m "fist commit"