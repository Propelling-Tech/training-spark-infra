# Spark Infra Playground
 
## Docker Overview
![docker](img/docker-overview.png)
 
## Architecture
![architecture](img/infra.png)
 
## Run Infra
 
### Requirements
- [ ] Docker installed
- [ ] Git Installed
 
1. Open the folder with **Visual Studio Code**
2. (if windows) Open the file **build.sh** and in the botton right, change **CRLF** by **LF**, then with `git bash` run shell script.
4. Open a terminal (if windows use Gitbash instead)
    ```shell
    sh build.sh
    ```
5. Run `docker-compose up`
6. Go to local [Jupyerlab](http://localhost:8890/lab)
7. Open the terminal inside the jupyter editor
8. Clone the repository `https://github.com/Propelling-Tech/training-spark-notebooks