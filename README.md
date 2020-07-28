Toy_project = 
===

📖 Introduction
---

This project is a site for Student of Likelion X MJUSEOUL

🏁 Getting started
---

### 1. git clone

First of all, clone this repository

```bash
$ git clone https://github.com/hyunbin1/ToyProject.git
```

### 2. create virtual environment

Second, prepare a virtual environment with the django and several packages.
So you have to deleted my venv file, then make your own venv environment again.
If you didn't do that, you can't use my project.

```[terminal] bash
$ python -m venv venv
```


> The name of virtual environment is defined by "venv"

### 3. activate virtual environment
```bash
$ source venv/scripts/activate # for windows
$ source venv/bin/activate # for mac or linux
```

### 4. install pip packages 
I already add my package in this project. you just type this command.

```bash
$ pip install -r requirements.txt
```
cf] If you want people to recommend the package you have installed, enter the command.
> The required packages are defined in the requirements.txt file.

```bash
$ pip freeze > requirements.txt
```

> If additional packages are installed, the following commands should be executed.

### 5. change git branch

first time, you must change master branch to other branch it's very important thing. 
I recommend you to work in a Branch called Develop.

```bash
$ git checkout <branch_name> # "master" or "develop"
```

> Insert 'master' or 'develop' instead of <branch_name>.

:Common times when you start project : Git command
---

```bash
when you start the project=
$ git pull origin <branch_name>
Plz don't forget to push your work, when the work is done.
$ git add .
$ git commit -m "What did u do"
$ git push origin <branch_name>
```
