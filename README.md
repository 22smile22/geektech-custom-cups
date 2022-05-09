# geektech-custom-cups
Geektech 14Py group - Final project

--git

echo "# geektech-custom-cups" >> README.md

git config --global user.name "your nickname"
git config --global user.email "your email"

git init
git add README.md
git commit -m "first commit"
git branch -M "your personal branch"
git remote add origin https://github.com/22smile22/geektech-custom-cups.git
git push -u origin "your personal branch"

…or push an existing repository from the command line

git remote add origin https://github.com/22smile22/geektech-custom-cups.git
git branch -M "your personal branch"
git push -u origin "your personal branch"

--postgre

postgres=# psql
postgres=#
postgres=# \l
postgres=# 
postgres=# CREATE DATABASE 'your database name';
CREATE DATABASE
postgres=#
postgres=#
postgres=# CREATE USER 'your username to db' WITH PASSWORD 'your password to db';
CREATE ROLE
postgres=#
postgres=#
postgres=# GRANT ALL PRIVILEGES ON DATABASE 'your database name' TO 'your username to db';
GRANT
postgres=#

--docker

docker build .  or docker build -t 'your docker name'
docker image
docker compose up
docker compose down
