#db

#C'est une base de données PostgreSQL.

#La base de donnée doit être initialisée avec le schéma (création de la base et des tables) et les données (utilisées par l'application).

#Le fichier words.sql contient les commandes SQL nécessaires.

FROM postgres

COPY words.sql /docker-entrypoint-initdb.d
