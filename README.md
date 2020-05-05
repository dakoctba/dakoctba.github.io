# dako.me

Esse blog utiliza o tema [minima](https://github.com/jekyll/minima/blob/master/README.md)

## Comandos úteis

    docker exec -it jekyll jekyll build

## Subir sem docker-compose

    docker run -p 4000:4000 --volume="$PWD:/srv/jekyll" -it jekyll/jekyll bash
