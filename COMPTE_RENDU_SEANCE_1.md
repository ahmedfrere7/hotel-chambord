# AP3 — Hôtel Chambord — Séance 1

**Objectif :** préparer l'équipe, les outils, Bootstrap, GitHub Pages et la procédure LAMP.

## Outils
- **Trello** : tâches, responsables, suivi.
- **GitHub** : versionner et publier les pages statiques.
- **HTML/CSS/JavaScript** : structure, style et interactions.
- **Bootstrap** : mise en page responsive et composants de formulaire.
- **LAMP** : Linux, Apache, MariaDB/MySQL, PHP.

## Équipe (à compléter)
- Chef de projet : ______
- Référent SLAM : ______
- Référent SISR : ______

## Trello
Créer « Hôtel Chambord — AP3 », avec les listes À faire, En cours, À vérifier, Terminé. Importer ou recopier les tâches du fichier `TRELLO_TACHES.csv`.

## Bootstrap
Un formulaire utilise `form-label`, `form-control`, `form-select`, `btn` et les espacements `mb-3`. Les colonnes adaptatives utilisent `container`, `row`, `col-*`. Les formulaires ajoutés valident les champs sans transmettre les données.

## GitHub Pages
1. Créer un dépôt public `hotel-chambord`.
2. Y ajouter les fichiers du dossier à la racine.
3. Settings > Pages > Deploy from a branch > main / (root).
4. Attendre le déploiement puis vérifier toutes les pages et images.
5. Copier l'URL réelle dans le compte rendu : ______

## Tutoriel LAMP (Ubuntu)
Le serveur du client est annoncé comme déjà installé. Ces commandes servent à comprendre la procédure sur une machine d'essai autorisée :
```bash
sudo apt update
sudo apt install apache2 mariadb-server php libapache2-mod-php php-mysql
sudo systemctl status apache2
sudo systemctl status mariadb
```
Déposer les fichiers du site dans `/var/www/html/hotel-chambord`, puis vérifier `http://localhost/hotel-chambord/`. Les pages PHP nécessiteraient un backend supplémentaire. Référence : https://ubuntu.com/server/docs

## Bilan
Les ressources initiales ont été conservées et des pages/formulaires frontend ont été préparés. Il reste à affecter les rôles, créer le Trello réel, publier sur le compte GitHub et tester sur le poste Linux.
