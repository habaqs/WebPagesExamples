# ESGI
L'**E**cole **S**upérieur de **G**énie **I**nformatique est l'école d'ingénieur dans la quel j'éffectue mon Master en [Systèmes, Réseaux et Cloud Computing](https://www.esgi.fr/programmes/systeme-reseau-cloud-computing.html).

Pour la réalisation de différents projets, nous devons présenter un serveur web fonctionnel. J'ai donc réalisé cette page web qui peut être importée rapidement sur un serveur. La page peut être modifiée afin d'y ajouter des informations supplémentaires (hostname, adresse IP...).

## Télécharger le fichier
1. Placez-vous dans le dossier de destination de la page d'exemple
```bash
cd /var/www/html
```
2. Téléchargez le fichier avec une des commandes suivantes \
⚠️ La commande écrase le fichier index.html à présent dans l'emplacement
```bash
# CURL
curl -o index.html https://github.com/habaqs/WebPagesExamples/raw/main/ESGI/esgi.html

# WGET
wget -O index.html https://github.com/habaqs/WebPagesExamples/raw/main/ESGI/esgi.html

```
> Vous pouvez aussi télécharger la page directement depuis git hub.