# my-pipeline

docker run -u root -d --name jenkins -p 8080:8080 -p 50000:50000 -v /var/run/docker.sock:/var/run/docker.sock -v /var/run/docker-cli.sock:/var/run/docker-cli.sock -v $(which docker)
:/usr/bin/docker -v $(which com.docker.cli):/usr/bin/com.docker.cli -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
