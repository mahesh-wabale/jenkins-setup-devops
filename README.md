# jenkins-setup-devops

setup : 
using native installation : 
https://www.cherryservers.com/blog/how-to-install-jenkins-on-ubuntu-22-04

using docker : 
https://medium.com/@eloufirhatim/install-jenkins-using-docker-e76f41f79682

step 1: 
docker pull jenkins/jenkins


step 2: 
docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins

step 3 : 
docker ps 

steps 4 : 
open browser 

http://localhost:8080

steps 5 : 
do exec into docker 

and check for file 

/var/jenkins_home/secrets/initialAdminPassword

copy key 
