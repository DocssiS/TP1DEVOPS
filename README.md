TPDevOPS
Rendu TP DevOps

Alexis Applincourt

les 3 scripts s'éxécute dans le répertoire dans lequel vous voulais créer les répertoires et les fichiers (dans mon cas, le repertoire /home/username/)

script 1 bis : s'éxécute seulement apres avoir deja éxécuter script1.sh (besoin d'avoir créer les repertoires), doit etre éxécuter en root !

script 2 : sert a installer cron et permet d'ajouter au crontab l'éxécution de script1.sh toutes les 5 minutes.