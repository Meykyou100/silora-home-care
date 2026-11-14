# Silora Home Care

Site statique (HTML, CSS, JavaScript) prêt pour Vercel. Aucune étape de build.

## Mise en ligne sur GitHub

    git init
    git add .
    git commit -m "Site Silora Home Care"
    git branch -M main
    git remote add origin https://github.com/VOTRE-COMPTE/silora-home-care.git
    git push -u origin main

## Déploiement sur Vercel

1. Sur vercel.com, cliquez sur « Add New » puis « Project ».
2. Importez le dépôt GitHub silora-home-care.
3. Framework Preset : « Other ». Laissez les commandes de build vides.
4. Cliquez sur « Deploy ».

## Modifier le numéro WhatsApp

Dans index.html, cherchez la ligne `const WA = "212657436309";` et remplacez le numéro (format international, sans +).

## Avant la mise en ligne

- Remplacez `VOTRE-DOMAINE.vercel.app` par votre vraie adresse dans `index.html`, `robots.txt`, `sitemap.xml` et les pages légales (recherche-remplacement dans l'éditeur).
- Complétez tous les passages en surbrillance jaune « [À compléter : ...] » dans les pages légales et la FAQ : raison sociale, RC/ICE, délais, retours, paiement, TVA.
- Les pages légales doivent être validées par votre conseiller juridique avant publication.
