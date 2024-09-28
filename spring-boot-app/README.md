# Spring Boot Based Java Web Application

This is a simple Spring Boot-based Java application that can be built using Maven. Spring Boot dependencies are handled using the `pom.xml` at the root directory of the repository.

This is an MVC architecture-based application where the controller returns a page with title and message attributes to the view.

## Execute the Application Locally and Access It Using Your Browser

1. **Clone the Repository and Navigate to the Directory**:
   ```bash
   git clone https://github.com/iam-priya
   nshu/java-maven-sonar-argocd-helm-k8s/sprint-boot-app
   cd java-maven-sonar-argocd-helm-k8s/sprint-boot-app
mvn clean package

java -jar target/spring-boot-web.jar

docker build -t ultimate-cicd-pipeline:v1 .

docker run -d -p 8010:8080 -t ultimate-cicd-pipeline:v1

apt install unzip
adduser sonarqube

wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.4.0.54424.zip
unzip *
chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424
chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424

cd sonarqube-9.4.0.54424/bin/linux-x86-64/
./sonar.sh start


This will render correctly on your GitHub README with proper headings, code blocks, and instructions.
