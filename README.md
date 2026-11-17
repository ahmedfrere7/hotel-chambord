# Hôtel Chambord — projet pédagogique BTS SIO

Projet frontend issu du dossier fourni, complété avec des pages Bootstrap et des formulaires.

## Utilisation
Ouvrir `index.html` dans un navigateur, ou lancer `python3 -m http.server 8000` dans ce dossier puis visiter http://localhost:8000.

## Pages ajoutées
`pages/connexion.html`, `pages/reservation.html`, `pages/recrutement.html`, `pages/activites.html`, `pages/hotel.html` et pages juridiques provisoires.

## Important
Les formulaires ne transmettent aucune donnée. Ils utilisent une validation HTML5/JavaScript et sont **à connecter à un backend**. La connexion n'est pas sécurisée/fonctionnelle sans backend. Les textes juridiques sont des placeholders.

## GitHub Pages
Créer un dépôt public, importer le contenu de ce dossier à sa racine, puis Settings > Pages > Deploy from a branch > main / root. GitHub Pages ne prend pas en charge PHP/MySQL.

## Linux Apache (Ubuntu/Debian)
Sur une machine autorisée, installer Apache/PHP/MariaDB si nécessaire puis copier le dossier dans `/var/www/html/hotel-chambord`. Vérifier les permissions, Apache et l'adresse locale. Ne jamais publier les identifiants ou secrets.

## Contrôles manuels
Tester navigation, images, responsive, formulaires, menu mobile, console navigateur, compatibilité et accessibilité.
