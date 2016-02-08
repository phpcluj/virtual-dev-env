# virtual-dev-env
Learn about creating a virtual development environment and provisioning it


DOCKER - image

to pull the image :
 
     sudo docker pull ralucaonaca/first-site:latest

to run the image :

     sudo docker run -d -p 127.0.0.1:8080:80 --name web -v /var/www/site:/var/www/site ralucaonaca/first-site 

to build the image:

   1. Trebuie sa faci un git pull la acest repository sa faci checkout pe branch-ul de docker-image

   2. cd where is the Dockerfile
 
   3.  sudo docker build -t ralucaonaca/first-site:first .  # first - tag-ul first . - directorul unde se afla Dockerfile

   4.  si se ruleaza commanda de run de mai sus
 
   5. daca esti curios de a accesa containerul : sudo docker exec -it web /bin/bash

# Any questions ping me on whatever social media you want :)

