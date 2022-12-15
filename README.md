# Nginx for html

### Preparing

```git clone https://github.com/codesshaman/docker_clear_nginx.git```

``cd docker_clear_nginx``

Remove file ``html/index.html`` and put your code with index.html to ``html`` folder.

If necessary, change port and container name in docker-compose file.

### Building

``docker-compose up -d --build``

or

``make build``

in unix with make.