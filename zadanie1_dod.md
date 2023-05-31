Jako, że po drodze napotkałem problem w postaci błędu [ERROR: multiple platforms feature is currently not supported for docker driver. Please switch to a different driver (eg. "docker buildx create --use")], udało mi się zbudować kontener dla pojedynczej architektury (analogicznie by to wyglądało dla innych).

Polecenie: docker build --platform linux/amd64 -t zad1_dod-docker .

Po uruchomieniu poleceniem "docker run -p 3000:3000 zad1dod-docker" otrzymujemy informacje:

![informacje na ekranie docker dodatkowe](img/informacje_na_ekranie_docker_dodatkowe.png)

![informacje w logach docker dodatkowe](img/informacje_w_logach_docker_dodatkowe.png)
