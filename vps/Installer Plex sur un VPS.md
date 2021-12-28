# Plex c'est quoi
 
# Installer Plex Media Serveur
 
```
sudo apt-get install curl
echo "deb http://shell.ninthgate.se/packages/debian squeeze main" | sudo tee -a /etc/apt/sources.list.d/plexmediaserver.list
sudo curl http://shell.ninthgate.se/packages/shell-ninthgate-se-keyring.key | sudo apt-key add -
sudo apt-get update
sudo apt-get install plexmediaserver
```
Accéder à Plex avec l'url "http://votreip:32400/web"
 
![image](https://user-images.githubusercontent.com/60802587/147521414-1ba5f098-da19-4aec-9302-4d66c5aa90ab.png)
 
### Liez votre serveur a Plex.tv
 
```ssh -L 32400:127.0.0.1:32400 root@IPSERVEUR```
 
Vous y accéder maintenant avec l'url "https://localhost:32400/web"
 
Suite à cela connectez vous à votre compte plex (dans la partie reglages)
 
![image](https://user-images.githubusercontent.com/60802587/147521434-213135f8-ef19-4bbd-9036-f58de8ca778c.png)
 
# Ajoutez des bibliothèques
 
 Appuyez sur l'icône "+" à gauche, spécifiez le type de contenu, la langue, la descriptions et le dossier
 
 ![image](https://user-images.githubusercontent.com/60802587/147521587-0b1bb6cc-e9d1-4bdd-a131-f09a2ee9ccf6.png)
 
# Lancer votre serveur
 
Pour lancer votre serveur entrez la commande: `service plexmediaserver start`
 
Pour arrêter votre serveur entrez la commande: `service plexmediaserver stop`
 
Pour redémarrer votre serveur entrez la commande: `service plexmediaserver restart`
 
 

