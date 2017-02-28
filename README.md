# epsi-test


Auteurs:

* SY Birane 
* OUARET sALIM






Les différentes commandes utilisées: 



db_nmap -v sV  "adresse IP"

services 

search "EXPLOIT"

use expoit/linux/etc/etc

show options 

set RHOSTS "adresse IP"

run



Les failles trouvées :

1- Le "vsftpd"

Ce module exploite une backdoor qui a été ajouté a l'archive de téléchargement vsftpd

Solution:

Mettre a jour le module vsftpd (la derniere version).

2-Le "ftp/anonyme" 

Scanner une plage d'adresses IP à la recherche des serveurs FTP qui permettent un accès anonyme.


3-Le "ftp_version" 

Le module scanne simplement une plage d'adresses IP et détermine la version de tous les serveurs FTP qui sont en cours d' exécution



