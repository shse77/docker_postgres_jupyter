sudo docker run -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca
sudo docker exec -it <my_container> bash
sudo docker cp radme.md <my_container>:/radme.md 

sudo docker exec -it 119c2c151559 bash

sudo docker run -v /home/shs77/docker-jupyter:/home/jovyan/work  -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca

sudo docker build -t my_notebook .
sudo docker run -v /home/shs77/docker-jupyter:/home/jovyan/work  -p 8888:8888 my_notebook

sudo docker  inspect 119c2c151559