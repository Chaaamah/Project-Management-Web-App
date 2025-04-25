
# 🚀 ProjectManagement

**ProjectManagement** est une application web moderne de gestion de projets développée avec **Laravel** (backend), **ReactJS** (frontend) et **InertiaJS** pour une navigation fluide en Single Page Application (SPA).  
Le projet utilise **Vite** pour la compilation rapide des assets.

---

## 🛠️ Technologies utilisées

- [Laravel](https://laravel.com/) – Backend PHP Framework
- [ReactJS](https://react.dev/) – Frontend JavaScript Library
- [InertiaJS](https://inertiajs.com/) – Adaptateur SPA sans API complexe
- [Vite](https://vitejs.dev/) – Build tool ultra-rapide pour le frontend
- [MySQL](https://www.mysql.com/) – Base de données

---

## 📦 Installation

1. **Cloner le projet**

```bash
git clone https://github.com/ton-repo/projectmanagement.git
cd projectmanagement
```

2. **Installer les dépendances PHP et Node.js**

```bash
composer install
npm install
```

3. **Configurer l’environnement**

- Copier le fichier `.env.example` vers `.env`

```bash
cp .env.example .env
```

- Configurer la base de données et les autres variables dans `.env`.

4. **Générer la clé d’application**

```bash
php artisan key:generate
```

5. **Exécuter les migrations (et seeders si besoin)**

```bash
php artisan migrate --seed
```

6. **Lancer le serveur de développement**

```bash
php artisan serve
npm run dev
```

---

## 🖥️ Lancer le projet

- Backend : [http://localhost:8000](http://localhost:8000)
- Frontend via Inertia + React intégré directement.

---

## 📂 Structure principale du projet

- `app/` – Contrôleurs, modèles Laravel
- `resources/js/` – Composants React
- `routes/web.php` – Routes principales
- `database/` – Migrations et seeders
- `public/` – Assets publics

---

## ✅ Fonctionnalités principales

- Gestion des projets (Créer, Modifier, Supprimer)
- Assignation des membres aux projets
- Système d’authentification
- Interface dynamique en React avec navigation sans rechargement grâce à Inertia
- Performances optimisées avec Vite

---

## 🚀 Scripts utiles

| Commande | Action |
|:---|:---|
| `npm run dev` | Lancer le serveur Vite pour développement |
| `npm run build` | Compiler les assets pour production |
| `php artisan migrate` | Lancer les migrations |
| `php artisan db:seed` | Lancer les seeders |

---

## 📜 Licence

Ce projet est sous licence [MIT](https://opensource.org/licenses/MIT).
