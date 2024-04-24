Changes made to the .yml file:

Removed the port definitions from backend, frontend and db.

```console
~/koulu/docker/pt2/exercise-2.10$ docker run -it --rm --network host networkstatic/nmap localhost
Starting Nmap 7.92 ( https://nmap.org ) at 2024-04-24 17:18 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000011s latency).
Not shown: 998 closed tcp ports (reset)
PORT    STATE SERVICE
80/tcp  open  http
631/tcp open  ipp

Nmap done: 1 IP address (1 host up) scanned in 0.19 seconds
```