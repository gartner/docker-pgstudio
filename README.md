# docker-pgsql-studio [![](https://badge.imagelayers.io/gartneriet/pgsql-studio:latest.svg)](https://imagelayers.io/?images=gartneriet/pgsql-studio:latest 'Get your own badge on imagelayers.io')

PostgreSQL Studio wrapped in a neat little Docker container.
The image is available on [Docker Hub](https://registry.hub.docker.com/u/gartneriet/pgsql-studio/).

Run the image

```
ocker run -d --name pgsql-studio --restart always -it -p 8088:80 -t gartneriet/pgsql-studio
```

Connect to your database via `http://localhost:8080` and enter
your database credentials.

![PostgreSQL Studio Screenshot](screenshot.png)
