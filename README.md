# Profiles REST API #

REST API providing basic functionality for managing user profiles.

1. Build:
sudo docker-compose build

2. Run migrations:
sudo docker-compose run api python src/profiles_project/manage.py migrate

3. How to up the server (build if is the first time)
sudo docker-compose up 

If you want to run in background, use -d flag

4. Now acess the browser api at
localhost:8000/api or localhost:8000/admin

5. Close the container
Ctrl + C




