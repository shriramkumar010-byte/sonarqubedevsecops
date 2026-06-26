### follow following commands for docker based sonarqube 
```
docker pull sonarqube:lts
```
can use following tags as well :-
sonarqube:community

sonarqube:developer

sonarqube:enterprise

sonarqube:lts

```
docker run -d --name sonarqube \
  -p 9000:9000 \
  -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true \
  sonarqube:lts
```
