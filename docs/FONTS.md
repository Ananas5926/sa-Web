# Utilisation des polices (Trajan Pro 3)

Ce projet inclut la police **Trajan Pro 3** dans le dossier `fonts/`.

## 1. Importer la feuille de style

Pour utiliser la police, vous devez lier le fichier `stylesheet.css` situé dans le dossier `fonts` dans la section `<head>` de vos fichiers HTML.

### Si vous êtes à la racine (ex: index.html) :
```html
<link rel="stylesheet" href="fonts/stylesheet.css">
```

### Si vous êtes dans un sous-dossier (ex: subpages/aide.html) :
```html
<link rel="stylesheet" href="../fonts/stylesheet.css">
```

## 2. Appliquer la police en CSS

Vous pouvez ensuite utiliser la famille de police `'Trajan Pro 3'` dans vos fichiers CSS.

Exemple pour l'appliquer à tout le corps de page :

```css
body {
    font-family: 'Trajan Pro 3', serif;
}
```

Ou pour des titres spécifiques :

```css
h1, h2 {
    font-family: 'Trajan Pro 3', serif;
    font-weight: bold;
}
```

## 3. Poids disponibles

La police est disponible en plusieurs graisses (weights). Vous pouvez les sélectionner via la propriété `font-weight` en CSS :

*   **Extra Light** : `font-weight: 200;`
*   **Light** : `font-weight: 300;`
*   **Regular** (Normal) : `font-weight: normal;` (ou 400)
*   **SemiBold** : `font-weight: 600;`
*   **Bold** : `font-weight: bold;` (ou 700)
*   **Black** : `font-weight: 900;`
