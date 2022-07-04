## Start Machine Learning Project

### Software and account Requirements.


1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
OR 
```
conda activate venv

For windows: conda activate E:\Complete_python\Krishna\Fullstack\Class_execution\fscicdpipline\machine_learning_project\venv
```

```

pip install -r requirements.txt
```
To add files in system on git

```
git add .
```
OR

```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```
To check remote url 
```
git remote -v
```
To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```
To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = yogeshkkolte@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-regression-app