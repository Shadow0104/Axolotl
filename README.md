# Axolotl
bot discord en v12 

Bonjour , pour que le bot soit fonctionnel sur votre serveur discord il faut faire quelques étapes :

===================== Etape 1 =====================


aller dans le terminal du bot est faites cette liste de commande à écrire :

"npm i discord.js"
"npm i dotenv"
"npm i gif-search"
"npm i id"
"npm i lowdb"
"npm i moment"
"npm i ms"
"npm i simple-youtube-api"
"npm i soundcloud-downloader"
"npm iweather-js"
"npm i ytdl-core"

une fois cette étape faite aller dans "package.json" et a la 4ème ligne se trouve "main: etc" , remplacer le par etc par main.js

===================== Etape 2 =====================


Aller dans "config.js" et à la place de :

exports.TOKEN = "TOKEN"; 
exports.PREFIX = "PREFIX";

mettez votre token (id du bot discord que vous avez créer grace à discord developper) et changer "PREFIX" par autre chose (ex: ! ou ?)


===================== Etape 3 =====================


Regardez toutes les commandes est quand vous voyer un truc comme Cela :

client.channels.cache.get('781253946583941141').send(embed);

remplacer les chiffres par l'id du salon ou vous voulez avoir les logs de ce que font les gens

sauf pour suggest et poll , la il faut choisir un salon comme suggestion pour suggest et sondage pour poll

===================== Etape 4 =====================

Ouvre le terminal est faite "node main.js" , ensuite aller sur le serveur discord et faite "help" avec le prefix que vous avez mit avant la commande
