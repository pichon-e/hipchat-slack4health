# Hipchat Slack4Health

## Installation

* npm install
* ngrok http 3000
* modifier tous les champs avec url dans le fichier "atlassian-connect.json" par l'url donnée par la commande ngrok
* AC_LOCAL_BASE_URL=https://"<url ngrok>".ngrok.com node app.js
* Créer un compte HipChat avec une team 
* Créer une room 
* Sélectionner la room 
* Aller dans intégration puis "Install an integration from a descriptor URL"
* Ajouter l'url ngrok
* Install
