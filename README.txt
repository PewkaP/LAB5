Komendy do uruchomienia

build:
docker build --build-arg VERSION=9.9.9.9 -f Dockerfile_zad1i2 -t lab5zad1i2:v1 .

run:
docker run -d -p 8083:80 --name lab5zad1i2 lab5zad1i2:v1   

w przeglądarce:
http://localhost:8083