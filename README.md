# docker-psql
Docker image with alpine linux and postgres (9.6) installed (used only for psql really). 

## Information
The command that runs is ```tail -f /dev/null``` therefore it is designed to be started detached and then connected / disconnected from as needed. 

I would usually use it like this:

```docker run -d benwest/psql```
```docker ps``` To get the container id just started
```docker exec -it [container ID] psql [psql options]```
