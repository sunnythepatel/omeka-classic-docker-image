Omeka-Classic in docker

[![Open Source Helpers](https://www.codetriage.com/sunnythepatel/omeka-classic-docker-imange/badges/users.svg)](https://www.codetriage.com/sunnythepatel/omeka-classic-docker-imange)

There is also example of docker-compose.yml file which can be used for development.
It creates 3 containers:

- mysql db
- phpmyadmin
- omeka-classic behind apache (modules or themes can be inserted via docker volumes

`docker-compose up`

Commands to create docker image

sudo docker build -t sunny3p/omeka-classic .
sudo docker push sunny3p/omeka-classic 

Resources and Reference
1. Docker documentation: https://docs.docker.com/engine/reference/builder/ 
2. Docker Cheat Sheet: https://github.com/wsargent/docker-cheat-sheet 
3. Docker Tutorial: https://www.flux7.com/tutorial/docker-tutorial-series-part-1-an-introduction-docker-components/
4. Omeka-Classic Previous Old Docker Image: https://github.com/klokantech/omeka-docker  

