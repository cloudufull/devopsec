# as you know
https://www.sonarqube.org/
# examples
* in jenkins : https://github.com/4admin2root/devopssec/blob/master/CI/jenkins/sonarqube_maven.Jenkinsfile (with sonarqube server configure named '89')  
* for maven: https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Maven  
# docker run
docker run -d -p 9000:9000 --name sonarqube 4admin2root/sonarqube:5.6.6  
browse http://localhost:9000/  
username:admin
password:admin