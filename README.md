Pokretanje ovog apija koristi se XAMP
u vhosts.conf file koji se nalazi u insalacionom folderu Xampa dodaje se:

<VirtualHost *:80>
    DocumentRoot "C:\xampp\htdocs\api"
    ServerName api.loc
    ServerAlias *.api.loc
</VirtualHost>

takodje dodaje se u C:\Windows\System32\drivers\etc\hosts 

127.0.0.1 www.api.loc

To nam omogucuje pokretanje apija u lokalu
potopm sa githuba skinuti projekat, napraviti folder i dodati ga u :

C:\xampp\htdocs

Nakon toga pokrenutu Xamp i doati preko phpmyadmina sql koji se nalazi u foderu projekta.
Nakon ucitavanje baze podataka ici u browser i uneti u url tab api.loc kretanjem kroz foldere uci u read da se vide podatci
Koristeci program Postman moze se kompletno koristiti api za opcije Create, Read, Update i Delete
