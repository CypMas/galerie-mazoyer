# Mazoyer Gallerie

Site vitrine d’une galerie de tableaux, construit en HTML/CSS/JavaScript.
Le projet met en avant trois pages principales :
- une page d’accueil immersive,
- une galerie d’images avec visualisation plein écran,
- une page de contact avec validation côté client.

---
## Visualier le site en ligne
https://raw.githack.com/Suprem69/site-futuram/main/index.html


---
## Aperçu rapide

Le site est pensé pour une navigation simple :
1. **Accueil** (`index.html`) : présentation + sélection de tableaux populaires.
2. **Galerie** (`gallery.html`) : collection complète avec Lightbox.
3. **Contact** (`contact.html`) : formulaire avec contrôle des champs en JavaScript.

L’ambiance visuelle repose sur des images grand format, une navigation sobre et un style orienté galerie d’art.

---

## Stack utilisée

- **HTML5**
- **CSS3**
- **JavaScript (vanilla)**
- **Bootstrap 3** (mise en page / composants)
- **jQuery**
- **Lightbox2** (affichage des images en plein écran)
- **Google Fonts** (`Lobster`, `Righteous`)


---

## Arborescence utile

```text
gallerie art/
├─ index.html
├─ gallery.html
├─ contact.html
├─ contact.js
├─ style.css
├─ background-image.jpg
├─ lightbox/
│  ├─ css/lightbox.css
│  └─ js/lightbox.js
└─ tableaux/
```

---

## Personnalisation

### Ajouter / remplacer des tableaux

- Déposer les nouvelles images dans `tableaux/`.
- Ajouter les balises `<a>` + `<img>` correspondantes dans `gallery.html`.
- Renseigner `data-title` pour le titre affiché dans la Lightbox.

### Modifier les images mises en avant

- Mettre à jour les trois vignettes « Tableaux populaires » dans `index.html`.

### Adapter le formulaire de contact

- Le contrôle des champs est géré dans `contact.js` (`validateForm()`).
- L’attribut `action` du formulaire pointe actuellement vers `/file.php` : à adapter selon le backend choisi.

---

## Notes

- Le projet est volontairement simple et lisible, pour faciliter les retouches visuelles.
- Les dossiers `tableaux - Copie` et `tableaux - Copie2` peuvent servir d’archives de travail si besoin.
- Un `.gitignore` est présent pour éviter de versionner les fichiers locaux d’IDE/système.

---

## Auteur

Projet réalisé pour la **Mazoyer Gallerie**.
