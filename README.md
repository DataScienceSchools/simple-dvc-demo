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

create a github repositry and do following

push an existing repository from the command line
git remote add origin https://github.com/DataScienceSchools/simple-dvc-demo.git
git branch -M main
git push -u origin main

write content of params.yaml 
git add . && git commit -m "yaml file"

touch src/get_data.py

write content get_data.py

python src/get_data.py