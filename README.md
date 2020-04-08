# recipe-app-api
Recipe app api source code



## Criando a imagem docker com o Dockerfile: 
- docker build .

## Criando a imagem docker com o docker-compose:
- docker-compose build

## Criando o projeto dentro do docker (com copia local):
Notar que o comando poderia ser apenas -- docker-compose run app "django-admin.py startproject app ." --
Porem usando o "sh -c" indica que será executado no shell do docker
- docker-compose run app sh -c "django-admin.py startproject app ."