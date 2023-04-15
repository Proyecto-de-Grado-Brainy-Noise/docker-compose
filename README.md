
# Project Docker-compose 🐳
Docker compose file to run the complete project.

## Runnning
Make sure you have already install Docker.
if not install here:  [Docker](https://www.docker.com)

Once you have docker, create a folder with the following structure:

project/  
|  
|__ modelService/ **[Repo](https://github.com/Proyecto-de-Grado-Brainy-Noise/modelService/tree/develop)**  
|   |__ ...  
|   |__ Dockerfile   
|   |__ requirements.txt   
|  
|__ queryResultsService/  **[Repo](https://github.com/Proyecto-de-Grado-Brainy-Noise/queryResultsService/tree/develop)**   
|   |__ ...  
|   |__ Dockerfile   
|   |__ requirements.txt   
|       
|__ README .md   



Once you have check the structure of the folders, make sure you are in the same path of the docker-compose, then, run the following command:

```sh
docker-compose up
```

You can check all running containers with the following command:
```sh
docker ps
```

To shut down all the containers, run the following command:
```sh
docker-compose down
```
If you make changes in the code, run the following command to run the containers with the changes you made:

```sh
docker-compose up --build
```



