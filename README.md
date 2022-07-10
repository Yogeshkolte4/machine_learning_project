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
To Discard the changes in working directory
```
git restore

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
To know the branch of git
```
git branch
```
To check remote url 
```
git remote -v
```
Connect Github to Heroku to strat deployment
To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = yogeshkkolte@gmail.com
2. HEROKU_API_KEY = 371fd6b0-d1f1-4d84-bb39-3e8fcea76551 # Find API_KEY in account setting
3. HEROKU_APP_NAME = ml-regression-cicd

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be in lowercase


TO list the docker images
```
docker images
```
Run dicker image
```
docker run -p 5000:5000 -e PORT=5000 <IMAGE ID>
```
To check running container in docker
```
docker ps
```
To stop runnning docker container
```
docker stop <CONTAINER ID>
```