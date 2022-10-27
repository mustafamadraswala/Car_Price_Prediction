# Car_Price_Prediction
Implementation of End To End Machine Learning Project With Deployment via Heroku and Docker


VS CODE Steps - 

>> Create a local Folder
>> Create a Repo on github --> Add Readme.md - Select Python - Add a License
>> Open Cmd --> cd into local folder --> git clone github repo
>> Go to repo folder on local machine --> Right click - Git bash Here - code .
>> Vscode will open with the folder as working directory
>> Ctrl+Shift+P --> Select base pythn=3.8.8 interpreter --> Open Terminal
>> Select cmd or Git ( or powershell)  accoridng to the project
```
conda create -n <my_env_name> python=3.8.8 -y
```
``
conda info --envs
```
```
conda activate <my_env_name>
```

Anaconda Steps - 

1. Open anaconda prompt
2. Base environment - 
>> conda create -n <my_env_name> python=3.8.8 -y
>> activate <my_env_name>
3. Create a local Folder
4. Copy the path --> cd in anaconda prompt to the path (D:\)
>> jupyter notebook

===========================================================================================

### Create and Install requirements.txt
```
pip install -r requirements.txt
```

### Setup your Github account
```
git config --global user.name "mustafamadraswala"
```
```
git config --global user.email "museychamp@gmail.com"
```

### Push all the changes and code to Github -
Add all the files to github - 
```
git add .
```

Check status of your files
```
git status
```

Commit all the files to github by pushing the fies from local to  thestaging environment -
```
git commit -m "This is my first commit includes requirement.txt and readme.md file"
```
or 
```
git add . && git commit -m "This is my first commit"
```

Push this to github -
```
git push origin main
```

### Execute the Car-price-prediction.ipynb file to get the pickle model file
### Create a folder templates and an HTML file - index.html
### Create a python file for your flask application
```
touch app.py
````
### Execute the app.py file in vscode
```
python app.py
```
### Deploy to Heroku
1. Go to Heroku - Create an app Car-price-prediction-mm
2. Connect the app with github repo
3. Push final commit to gitub
4. Deploy branch on heroku