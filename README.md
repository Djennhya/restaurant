# Application de gestion de restaurants

**Description :**  
Cette application est un outil complet de gestion de restaurants, conçu pour aider les propriétaires et gestionnaires à superviser plusieurs établissements et leurs livraisons de manière centralisée. Développée avec le framework **Laravel** et utilisant **MySQL** comme base de données, elle offre une solution robuste et extensible pour répondre aux besoins variés des restaurateurs.

---

## Fonctionnalités principales :

1. **Gestion des restaurants :**
   - Créez, modifiez et supprimez des restaurants.
   - Suivi des informations spécifiques à chaque restaurant (nom, localisation, horaires, etc.).

2. **Gestion des menus :**
   - Ajoutez et gérez les plats proposés par chaque restaurant.
   - Catégorisez les plats (entrées, plats principaux, desserts, etc.).
   - Fixez les prix et gérez les disponibilités.

3. **Suivi des commandes et livraisons :**
   - Gestion des commandes des clients.
   - Suivi en temps réel des livraisons.
   - Attribution des livreurs aux commandes.

4. **Gestion des utilisateurs :**
   - Gestion des rôles et permissions (propriétaires, gestionnaires, livreurs, clients).
   - Authentification sécurisée pour chaque utilisateur.

5. **Rapports et statistiques :**
   - Génération de rapports sur les ventes, les livraisons et la performance des restaurants.
   - Visualisation des statistiques pour une prise de décision éclairée.

---

## Prérequis :
Avant de démarrer le projet, assurez-vous que les éléments suivants sont installés sur votre machine :
1. **PHP** (version recommandée : ≥ 8.x)
2. **Composer** (Gestionnaire de dépendances PHP)
3. **MySQL** (Pour la base de données)
4. **Node.js et npm** (Pour gérer les dépendances front-end)
5. **Laravel** (framework utilisé pour le développement)

---

## Étapes pour démarrer le projet :

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/Djennhya/restaurant.git
   cd restaurant
   ```

2. **Installer les dépendances PHP :**
   ```bash
   composer install
   ```

3. **Installer les dépendances front-end :**
   ```bash
   npm install
   npm run dev
   ```

4. **Configurer le fichier `.env` :**
   - Dupliquer le fichier `.env.example` et renommez-le en `.env`.
   - Configurez les informations de connexion à la base de données :
     ```env
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=online_rest
     DB_USERNAME=localhost
     DB_PASSWORD=
     ```

5. **Générer la clé de l'application :**
   ```bash
   php artisan key:generate
   ```

6. **Migrer la base de données :**
   ```bash
   php artisan migrate
   ```

7. **Lancer le serveur local :**
   ```bash
   php artisan serve
   ```

   L'application sera accessible à l'adresse suivante : [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Technologies utilisées :

- **Framework Backend :** Laravel (PHP)
- **Base de données :** MySQL
- **Frontend :** Blade Templates, JavaScript
- **Gestion des dépendances :** Composer et npm

---

## Auteur :
Développé par [Djennhya](https://github.com/Djennhya).  
