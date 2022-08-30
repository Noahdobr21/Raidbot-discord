## Si vous lisez ceci c'est que vous voulez utiliser mon bot anti-raid



## Installation
Installez toutes les dépendances :

pip install -r requirements.txt
Mettez ensuite votre jeton Discord qui se trouve dans le portail des développeurs de Discord à l'intérieur config.example.json(ne changez rien d'autre)
Renommez-le enconfig.json
Ce bot doit utiliser "l'intention des membres du serveur", vous devez donc l'activer dans le portail des développeurs de Discord
Enfin, hébergez le bot et invitez-le sur votre propre serveur.

## Fonctionnalités
Ce bot Discord protège votre serveur Discord avec de nombreuses fonctions.

Pare-feu Captcha
Âge minimum du compte requis
Image anti-nudité
Anti-blasphème
Anti-spam
Journaux
Commandes de modération de base
Prise en charge de plusieurs guildes
Multi langue (EN, FR)
Les restrictions n'affectent pas les membres avec l'autorisation ADMINISTRATEUR 


## Commandes
?setup <on/off> : Set up the captcha protection.
?settings : Display the list of settings.
?giveroleaftercaptcha <role ID/off> : Give a role after that the user passed the captcha.
?minaccountage <number (hours)> : set a minimum age to join the server (24 hours by default).
?antinudity <true/false> : Enable or disable the nudity image protection.
?antiprofanity <true/false> : Enable or disable the profanity protection.
?antispam <true/false> : Enable or disable the spam protection.
?allowspam <#channel> (False) : Enable or disable the spam protection in a specific channel.
?lock | unlock <#channel> : Lock/Unlock a specific channel.

?userinfos <@user/ID> : Get user infomations.

?ban <@user/ID> : Ban the user.
?kick <@user/ID> : Kick the user.

?changeprefix <prefix> : Change the bot's prefix for the guild.
?changelanguage <language> : Change the bot's language for the guild.
?help : display help.
Erreurs potentielles
ImportError : impossible d'importer le nom 'joblib' sous la forme 'sklearn.externals'
Vous devez télécharger la dernière version de profanity_check. Désinstallez votre version actuelle et téléchargez la v1.0.6 avecgit+https://github.com/dimitrismistriotis/profanity-check

