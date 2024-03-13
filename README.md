# Test technique Vasco

Après avoir cloner le repository, adapter les variables d'environnement pour pointer vers un serveur de base de données actif (de préférence MySql).

# Lancer l'application
```
php bin/console doctrine:database:create
php bin/console doctrine:migration:migrate
symfony server:start
```
