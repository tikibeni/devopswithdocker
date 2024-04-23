```console
~/koulu/docker$ docker run -it --name deps ubuntu sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
~/koulu/docker$ docker exec -it deps bash
root@e84b84071e1b:/# apt update
root@e84b84071e1b:/# apt install curl
```