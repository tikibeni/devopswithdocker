Frontend terminal:
```console
~/koulu/docker/pt1/exercise-1.14/frontend$ docker build . -t front && docker run -p 5000:5000 front
```

Backend terminal:
```console
~/koulu/docker/pt1/exercise-1.14/backend$ docker build . -t back && docker run -p 8080:8080 back
```