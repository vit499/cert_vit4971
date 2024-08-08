# nginx-cert

> первоисточник: https://github.com/wmnnd/nginx-certbot.git

В init-letsencrypt.sh указать все домены и поддомены, почту, staging=1 для проверки, потом staging=0
В docker-compose нужно для nginx указать ранее созданную network 
Создать для каждого домена файл .conf в папке data/nginx, в этих файлах указать имя домена и имена контейнеров
Запусить  ./init-letsencrypt.sh

