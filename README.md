# Recettes

Une application web simple pour consulter et filtrer des recettes de cuisine.

## Fonctionnalités

- **Recherche par titre** : filtrer les recettes par mot-clé
- **Filtrer par ingrédients** : sélectionner un ou plusieurs ingrédients (ET logique)
- **Filtrer par saison** : afficher les recettes selon la saison (Hiver, Printemps, Été, Automne)

## Utilisation en local

Ouvrez simplement le fichier `index.html` dans un navigateur web :

```bash
# Avec Python
python -m http.server 8000

# Avec PHP
php -S localhost:8000
```

Puis accédez à `http://localhost:8000` dans votre navigateur.

Les recettes sont stockées dans `recettes.csv` au format CSV.
