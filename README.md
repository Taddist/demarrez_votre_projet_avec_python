# Démarrer avec Python

## Installation 

Installation des dépendances :
    pip install -r requirements.txt

## Parser

Lancer le scraper :

- Commencer par supprimer l'ancien fichier :
    rm -rf characters.json

- Puis lancer le scraper :
    scrapy runspider characters_scraper.py -o characters.json

