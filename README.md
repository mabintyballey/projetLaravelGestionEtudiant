# projetLaravelGestionEtudiant
"Application de gestion Etudiant en Laravel"
Ce projet est une application Laravel permettant de gérer les users(Professeurs, Personnels, Etudiants), les departement, classes, matiere et les notes.
1. **Cloner le projet** :
   ```bash
   git clone https://github.com/mabintyballey/projetLaravelGestionEtudiant.git
   cd projetLaravelGestionEtudiant
2. **Installer les dépendances** 
     composer install
3. **Créer et configurer l'environnement**
   cp .env.example .env
   php artisan key:generate
4. **Configurer la base de données dans .env**   
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=nom_de_la_base
   DB_USERNAME=root
   DB_PASSWORD=
5. **Exécuter les migrations et les seeders**
       php artisan migrate --seed
7. **Lancer le serveur**
        php artisan serve
8.  **Équipe L4 UBO**
  Admin : @Mabintyballey
Développeur (Professeur, Personnel) : @booba
Développeur (Etudiant) : @Saran
Développeur (Roles) : @Alpha
Développeur (Departement) : @Rougui
Développeur (Classe) : @Ibrahima
Développeur (Matiere) : @Balley
Développeur (Notes) : @Mahawa  
