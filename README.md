# config-server

> Clone following repository to set config files property 
https://github.com/shaikhhafiz/config-files.git
and replace uri: https://github.com/shaikhhafiz/config-files.git by uri: file://'folder location of your config files' in bootstrap.yml file. file://media/ems/config-files was for mine in linux os

> Or just run this application and hit following curl in command line
curl http://root:12345@localhost:4002/config-cient-one/development/master | json_pp
