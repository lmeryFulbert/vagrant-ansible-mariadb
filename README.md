#Configuration automatique d'une VM avec mariadb

##lyc�e Fulbert - lmery

###To Do

En cas de probl�me avec les vbguest-tools

Bien v�rifier que le plugin vagrant vbguest est bien install�. Voir doc [ici](https://github.com/dotless-de/vagrant-vbguest)

se connecter en ssh � la VM via

`vagrant ssh

```\
sudo apt update
sudo apt-get upgrade
sudo apt-get dist-upgrade
```

quitter la session ssh puis faire un

`vagrant reload

Tant que les guest tools ne sont pas correctement install� le provisionnement ne fonctionnera pas car il faut monter le volume dans la VM.

Pour provisionner:
`vagrant provision




