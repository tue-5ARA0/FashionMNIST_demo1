# Fashion-MNIST-part1

# PART1

### Objectives
* Create GitHub project
* Create issues via Kanban Board
* PyCharm settings and requirements.txt
* Create Jupyter notebook
* Initialize and use DVC
* Create folder structure for the ML project

### Prerequisite
* PyCharm Professional
* Python **3.8** (64 bit)
* Git, DVC, and GitHub account

### GitHub Setup
1. Create GitHub repository 
2. Adjust project settings for automated kanban
3. Create issues with your team-mates

### Python Project Setup
1. Configure Python 3.8 and create virtual environment
2. Create requirement file "requirements.txt" and include necessary packages
3. Add directories: data, logs, models, notebooks.
4. Add ".idea/" to the end of .gitignore file to exclude PyCharm projects
5. Create the python package with the name of "src"
   1. Add __main__, config, train python files. 
   2. You can also have a look directory templates for ML project via [Data Science Cookiecutter][1] and [ML_Template][2]

### Fashion MNIST Jupyter Notebook
1. Check the [Fashion MNIST dataset][3]
2. Add [Fashion MNIST Jupyter notebook][4] to notebooks directory of the project. 
3. Go through the notebook and understand the implementation. 

### DVC Initilization
Here we will create local serve to keep our data, model, weights by using the [DVC][5]
1. Download Fashion MNIST dataset through the "Get the Data" section of [Zalando GitHub page][3]
2. Initiliaze DVC and commit necessary files to GitHub
3. Add "/data" to the end of ".gitignore" file to exclude DVC directory
4. You can check [DVC Data and Model versioning][6] for creating the local storage
5. Check the directory created for DVC in your local to observe the data
   1. As an experiment, delete data directory and type "dvc pull" in console to see data has ben loaded automatically.   
6. You can additionally check [DVC Google Drive Example][7] to use Google Drive instead of your local  

[1]: https://drivendata.github.io/cookiecutter-data-science/
[2]: https://github.com/eddiepease/ml-template
[3]: https://github.com/zalandoresearch/fashion-mnist
[4]: https://github.com/tensorflow/docs/blob/master/site/en/tutorials/keras/classification.ipynb
[5]: https://dvc.org/doc/start
[6]: https://dvc.org/doc/start/data-and-model-versioning
[7]: https://www.youtube.com/watch?v=kLKBcPonMYw&t=2s&ab_channel=DVCorg

