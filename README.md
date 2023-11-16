# devopslive2.1
ASsignment 2 Part 1

```
root@dice-devops:/home/Repos/devopslive2.1# docker compose up -d
[+] Running 1/1
 ⠿ Container nginx_container  Started                                                                                                                                                                                                                    0.6s
root@dice-devops:/home/Repos/devopslive2.1# docker network ls
NETWORK ID     NAME         DRIVER    SCOPE
67d53fdcca74   bridge       bridge    local
7336833188a0   host         host      local
fa82bac86cea   my_network   bridge    local
4043b45d65ff   none         null      local
root@dice-devops:/home/Repos/devopslive2.1# docker compose ps
NAME                COMMAND                  SERVICE             STATUS              PORTS
nginx_container     "/docker-entrypoint.…"   web                 running             0.0.0.0:8080->80/tcp, :::8080->80/tcp
root@dice-devops:/home/Repos/devopslive2.1#

```


![image](https://github.com/sydali/devopslive2.1/assets/449393/895cdfd9-d009-4fae-add3-0a098cea0100)
