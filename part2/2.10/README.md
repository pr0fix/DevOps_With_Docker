# Exercise 2.10

I already did this part in the last exercise 2.09 by removing port mappings from docker-compose.yml file from both frontend and backend.

## With the service running doing a nmap port scan results to this:
```sh
$ docker run -it --rm --network host networkstatic/nmap localhost
Starting Nmap 7.92 ( https://nmap.org ) at 2024-06-04 15:41 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.0000030s latency).
Other addresses for localhost (not scanned): ::1
Not shown: 998 closed tcp ports (reset)
PORT    STATE    SERVICE
80/tcp  filtered http
111/tcp open     rpcbind

Nmap done: 1 IP address (1 host up) scanned in 1.45 seconds
```
