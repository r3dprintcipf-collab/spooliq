# SpoolIQ — Filament Intelligence

Application web autonome de gestion de filament 3D, en français.

## Fonctionnalités
- Tableau de bord stock, alertes, activité, valeur estimée
- Inventaire individuel de bobines avec poids initial/restant, tare et pesée brute, coût d'achat, fournisseur, lot, date et emplacement
- Catalogue de références de filament avec marque, matière, couleur/HEX, diamètre, densité et températures
- Recettes produit multi-couleurs et déduction atomique de la consommation à la déclaration d'une production
- Journal des entrées, sorties et corrections
- Analyses de consommation, coûts de matière estimés et top couleurs
- Gestion fournisseurs
- Recherche, filtres, export CSV, sauvegarde/restauration JSON
- Interface responsive, sans dépendances externes

## Déploiement GitHub Pages
1. Crée un nouveau dépôt GitHub nommé `spooliq`.
2. Ajoute `index.html` à la racine.
3. Ouvre Settings → Pages.
4. Dans Build and deployment, choisis Deploy from a branch, branche `main`, dossier `/(root)`, puis Save.

## Limites de cette édition autonome
Les données sont conservées dans le stockage local du navigateur. Elles ne se synchronisent pas entre ordinateurs ou navigateurs. Le logiciel ne récupère pas automatiquement les données du slicer ou de l'imprimante. Pour le multi-appareil, les comptes, l'accès multi-utilisateur, la télémétrie imprimante, l'API ou le scan NFC, ajouter un backend et les intégrations appropriées.
