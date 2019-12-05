# Docker Install 

### Informations :
| |  |
| ------ | ------ |
| HTTP| Apache |
| PHP| 7.3.12 |
| MYSQL| MariaDB |

## Préparation :


> /docker-compose.yml.dist
- renommer en docker-compose.yml
- remplacer `{{name_project}}` par le nom du projet


> docker/config/project.conf.dist
- renommer en `{{nameproject}}.conf`
- remplacer l.2 `{{name_project}}`

> Configuration du fichier host
- rajouter `127.0.0.1 fr.{{name_project}}.test` dans le fichier host

> Installation Symfony
- `www/`

> Lancement docker
- docker-compose up

## Conteneur Informations :

> Host 
- url : fr.{{name_project}}.test

> Mysql 
- host : localhost
- port : 3306
- login : root
- password : root

