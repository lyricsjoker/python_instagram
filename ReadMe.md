
## Introduction
 This project is create to learn python. 
 
Origin from 
[Increase your Instagram followers with a simple Python bot](https://towardsdatascience.com/increase-your-instagram-followers-with-a-simple-python-bot-fde048dce20d)

## Evironment

- Python 3.7
- Selenium
- Chrome
- Instagram account
- chromedriver


## Commands
Operate System: MacOS

### 1.Install python and  related tools.

Download and install newest python from [Python](Python.org).

After install success, run
```
which python3
```
should get the the path of python3.


2. Set up virtual environment

```shell
pip install virtualenv
```

go to project and activ

 ```shell
 cd  ${my_project} 
 virtualenv ${env_name}
```

A folder called ${env_name} created, all future python modules should be install inside this folder. In  ${env_name}/lib/python3.7/site-packages

Activate virtual environment
```shell
source my_project_env/bin/activate
```

Install project modules
```shell
pip install pandas
pip install selenium
```

Start run 

```shell
python3 fans.py
```

## Result
1. All added instagram user will be added to .csv file, you next these user will not be targeted
2. You can see 5 person follow me in half hour. Screenshot is added in /result folder.

