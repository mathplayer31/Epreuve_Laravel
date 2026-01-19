Liste des commandes à effectuer pour installer et lancer le site :
# 1. Installer composer
composer install

# 2. Install Node
npm install

# 3. Copier le fichier env
cp .env.example .env

# 4. Generer la clé d'application
php artisan key:generate

# 5. Configurer manuellement le .env pour la database
Set DB_DATABASE, DB_USERNAME, DB_PASSWORD

# 6. Lancer la migration
php artisan migrate

# 7. Build les assets
npm run build

# 8. Lancer le serveur
php artisan serve