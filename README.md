# recipe-app-api
Recipe API project

sudo docker-compose run --rm app sh -c "python manage.py test && flake8"


docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

//la liste des dockers
docker ps

//Liste des volumes de notre système
docker volume ls

//supprimer un volume
docker volume rm NomVolume

//Démarrer un nouveau serveur
docker compose up

