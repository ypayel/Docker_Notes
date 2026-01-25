# tworzymy nowy etap na podstawie obrazu bazowego
FROM httpd:2.4.66-alpine 


LABEL maintener="Zrob wlasny obraz"

# dodajemy plik lokalnie, dodajemy w tym przypadku tylko index.html
# ADD /usr/local/apache2/htdocs - w taki sposob dodaje sie caly DockerFile
ADD . /usr/local/apache2/htdocs

# EXPOSE nie nadaje portu, a tylko zwraca informacje ze powinien byc na porcie 80 w naszym przypadku
EXPOSE 80