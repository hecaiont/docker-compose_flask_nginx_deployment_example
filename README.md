# docker-compose_flask_nginx_deployment_example


├── docker-compose.yml
├── flask
│   ├── Dockerfile
│   ├── src
│   │   ├── run.py
│   │   └── webapp
│   │       ├── __init__.py
│   │       └── main.py
│   └── uwsgi.ini
├── nginx
│   ├── Dockerfile
│   └── default.conf


cd to flask > docker build -t flask:test .

cd to nginx > docker build -t nginx:test .

cd to / docker-compose up or docker-compose up -d




ref to https://basketdeveloper.tistory.com/66
