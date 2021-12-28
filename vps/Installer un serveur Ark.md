# Instaler les depandences 

```sudo dpkg --add-architecture i386```  
```sudo apt-get update```  
```sudo apt-get install mailutils postfix curl wget file gzip bzip2 bsdmainutils python util-linux tmux lib32gcc1 libstdc++6 libstdc++6:i386```  

### Creer un utilisateur

```adduser arkserver```

Ecriver votre mot de pass 

```su - arkserver```

### Telechargez le script du serveur

```wget https://gameservermanagers.com/dl/arkserver```

### Executer le script

```chmod +x arkserver```

### Lancez l'installation 

```./arkserver install```

### Lancer le serveur

```./arkserver start```

## Tips

Obtenir la liste de commandes: `./arkserver`

Stopper le serveur: `./arkserver stop`

Redémarrer le serveur: `./arkserver restart`

Mettre à jour du serveur: `./arkserver update`

