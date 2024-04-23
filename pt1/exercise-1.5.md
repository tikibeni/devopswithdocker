```console
~/koulu/docker$ docker images
REPOSITORY                          TAG              IMAGE ID       CREATED         SIZE
devopsdockeruh/simple-web-service   ubuntu           4e3362e907d5   3 years ago     83MB
devopsdockeruh/simple-web-service   alpine           fd312adc88e0   3 years ago     15.7MB
~/koulu/docker$ docker run devopsdockeruh/simple-web-service:alpine
Starting log output
Wrote text to /usr/src/app/text.log
~/koulu/docker$ docker exec -it zen_swirles sh
/usr/src/app # tail -f ./text.log 
2024-04-23 19:34:07 +0000 UTC
2024-04-23 19:34:09 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```