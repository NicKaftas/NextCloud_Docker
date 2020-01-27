# NextCloud_Docker

This is a Docker application where you can create a Cloud storage app and can storage save/edit any file you desire.

To create the Docker container we nned to execute the follow steps:

1) Create directory where the docker-compose file of our container will be located "sudo mkdir /root/myprojects/Dockerized-Nextcloud".
2) Go to the directory that yu just created "cd /root/myprojects/Dockerized-Nextcloud"
3) Create a file, from where the docker composer will "see" to create the container "sudo touch docker-compose.yml"
4) Copy/paste the docker-compose file from my repository to your coresponding file in your host machine.
5) Save & Exit the docker-compose.yml file.
6) Run the command "docker-compose up -d" in order to start the docker container.
7) Open a broswer and search for the IP of your host machine with the corresponding port (in this case port:8080).

In my case it's: IP:83.212.75.213:8080

User: #######
Password: ###########
