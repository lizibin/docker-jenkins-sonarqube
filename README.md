# docker-jenkins-sonarqube

## 1. Docker
To use this program, you must have `docker` and `docker-compose` installed on your computer. The installation process can be found on the [official Docker website](https://www.docker.com/)
## 2. Start the program
First of all, you have to clone this project in your directory with the following command:
```Bash
git clone https://github.com/lizibin/docker-jenkins-sonarqube.git
```
```Bash
docker login repo.1000m.xin
```
the username is github ,pwd LIZIBINlizibin520
```Bash
docker-compose -f autoDeployment-compose.yml up -d
```


## 3. Jenkins and SonarQube

Jenkins and SonarQube are available on the following ports:

- Jenkins: 8080
- SonarQube: 9000

## If you have questions, please go to my blog to discuss.
[我的博客](http://www.zyizou.com) 

## License
This repository is under the MIT license. You can find it [here](https://github.com/lizibin/docker-jenkins-sonarqube/blob/master/LICENSE).


