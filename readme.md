#   :green_apple: Eat healthy, be wealthy :green_apple:
Parce que c'est cooooool

## Avant de commencer

***Crée une base de donnée en local en tant que root***

`CREATE DATABASE database_name;`

***Donne tous les privilèges à l'user que tu veux***

`GRANT ALL PRIVILEGES ON database_name.* TO 'username'@'localhost';`

***Puis crée un fichier config.py avec le nom de ton user, le mot de passe et le nom de ta base de donnée (voir config.py.template)***
```
HOST = 'localhost'
USER = 'user_name'
PASSWORD = 'password'
DATABASE = 'database_name'
```

***Enfin, installe tous les packages nécessaires***

`pip install -r requirements.txt`

## Lance le programme
***Pour synchroniser les données et initialiser la base de donnée***

`python main.py --init --sync`

`Les options doivent être utilisées seulement la premiere fois lors du lancement du programme.`

## Ok mais pour quoi faire?

- Tu peux rechercher des aliments dans la base de donnee et voir leur description.

- Tu peux chercher un substitut pour l'aliment que t'aimerais remplacer.

- Tu peux sauvegarder tes aliments favoris pour les retrouver plus tard.

Et voilà! :ok_hand:
