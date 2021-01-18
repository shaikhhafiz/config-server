# config-server

> Clone following repository to set config files property 
https://github.com/shaikhhafiz/erp-config-files.git
and replace uri: https://github.com/shaikhhafiz/erp-config-files.git by uri: file://'folder location of your config files' in bootstrap.yml file. file://media/github/erp/erp-config-files was for mine in linux os

> Or just run this application and hit following curl in command line
curl http://root:12345@localhost:4002/config-client-one/development/master | json_pp

### Docker
> Create docker image using following command docker build -t config-server .

> Run container using following command docker run -dp 4002:4002 -v /media/github/erp/erp-config-files:/media/github/erp/erp-config-files config-server 