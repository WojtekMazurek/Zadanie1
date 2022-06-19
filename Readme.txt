1. Pobieramy pliki
2. Przechodzimy do folderu z plikiem Dockerfile
3. Następnie "budujemy" za pomoca komendy docker build .
4. docker images pozwoli nam sprawdzi id obrazu
5. Uruchamiamy: docker run -d -h localhost -p 80:80 [IMAGE ID]
6. Wchodzimy w przegladarke i wpisuje localhost/index.php

___________________________________________________________

Sprawdzanie logow:

1.docker ps
2.docker exec -it [container id] bin/sh
3.cat MYLOG.log

___________________________________________________________

1. docker history - sprawdzanie ilosci warstw
