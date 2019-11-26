Steps for the exam:

START VM IN VBOX
Centos (ip=192.168.56.101)

#this is on my computer:
START JENKINS
./start_jenkins.sh

GO TO
localhost:8080

BUILD NOW
CI pipeline
CD pipeline

FINAL STEPS
#check in browser after CI and CD pipelines ran with SUCCESS in jenkins: 
http://192.168.56.101:8081/
http://192.168.56.101:5001/
http://192.168.56.101:5002/
http://192.168.56.101:5003/
#can also check that containers are up and running on VM (but it is obvious)
docker ps in GUI or via ssh root@192.168.56.101
 
