# Portfolio académique de Basma Sounni

Ce dossier contient un site statique modifiable et compatible avec GitHub Pages.

## Fichiers

* `index.html` : contenu du portfolio
* `styles.css` : apparence, couleurs et mise en page
* `script.js` : menu mobile et année automatique
* `assets/CV_Basma_Sounni.pdf` : CV téléchargeable

## Modifier le contenu

Ouvrir `index.html` dans Visual Studio Code ou dans l’éditeur de GitHub.  
Les sections sont clairement séparées : Profil, Recherche, Projets, Compétences, Parcours et Contact.

Pour changer les couleurs, modifier les variables situées au début de `styles.css` :

```css
:root {
  --accent: #8f2233;
  --accent-dark: #671724;
}
```

## Mettre le site en ligne gratuitement avec GitHub Pages

1. Créer un compte GitHub, puis un dépôt nommé exactement `basmasounni.github.io`.
2. Ajouter dans ce dépôt `index.html`, `styles.css`, `script.js` et le dossier `assets`.
3. Ouvrir `Settings`, puis `Pages`.
4. Dans `Build and deployment`, choisir `Deploy from a branch`.
5. Sélectionner la branche `main` et le dossier `/root`.
6. Le site sera accessible à l’adresse `https://basmasounni.github.io`.

## Éléments à compléter

* Remplacer le lien GitHub dans la section Contact.
* Mettre à jour le CV lorsque sa version définitive sera prête.
* Ajouter éventuellement de vraies captures de Praat, ELAN ou du dictionnaire dans un futur dossier `assets/images`.
* Vérifier les dates et les formulations avant publication.
