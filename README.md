# Assignment1
first home test assignment

to start you will need to download and install Docker.
you can use this link here: https://docs.docker.com/engine/install/
then install the docker compose from this link: https://docs.docker.com/compose/install/
or use this comman: docker compose version
when you have those installed you can use this command to install Jankins from docker hub: docker run -it -p 8080:8080 jenkins/jenkins:lts
Now create a diractory named jenkins_compose on your desktop.
download the file docker-compose.yaml to that diractory.
open a terminal and run this command: docker-compose up -d
it will run acontainer for jenkins.
now open a browser and go to "local host:8080", it will ask password to log in.
go back to the terminal and run this command: docker logs jenkins
it will give you tha password between 3 lines of asterisks.
when you copy your password to the web page select "Install Suggested Plugins"
when it's over enter a user name and password and click Save and Continue.
next keep it the same and continue untill you see "start using jenkins".
