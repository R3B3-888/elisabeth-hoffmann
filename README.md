# elisabeth-hoffmann

## Mise en ligne d'un produit

Mettre la photo dans le dossier `images/paintings/` en format .jpg et si possible rester autour des 400 en largeur et 400 en longueur par soucis de fluidité de chargement des photos par les navigateurs des différentes personnes.

### 4 cote à cote

Dans le fichier `_.html`, on ajoute un bloc div avec en class col-4, une borne imbriqué img avec le chemin en src, le titre et les dimensions en h4, et le prix en p

```html
<div class="col-4">
  <img src="images/paintings/nom-du-jpg" />
  <h4>Nom de l'oeuvre</h4>
  <p>Prix</p>
</div>
```

### 3 cote à cote

Comme pour le col-4 mais on met un col-3 et les images sont fixes et sans prix.
