# Site Team Opossum

Site vitrine de l'équipe de robotique Opossum. Site statique (HTML/CSS/JS), sans
aucune construction : GitHub Pages sert les fichiers directement.

## Structure

```
index.html            → tout le site (une seule page qui défile)
assets/img/           → photos (banner.jpg, robots, bilans...)
assets/img/sponsors/  → logos des partenaires
.nojekyll             → indispensable : empêche GitHub de traiter le site avec Jekyll
```

## Mettre en ligne

Repo → Settings → Pages → Source : **Deploy from a branch** → branche `main`,
dossier `/ (root)`. Le site est publié à l'adresse indiquée par GitHub.

## Modifier le contenu

Tout se fait dans `index.html`, qui est commenté en français :

- **Photos du carrousel / bilans** : ajoute tes images dans `assets/img/` puis change
  les `src`.
- **Vidéos** : remplace `dQw4w9WgXcQ` par l'identifiant de tes vidéos YouTube.
- **Sponsors** : mets les logos dans `assets/img/sponsors/` et adapte les liens.
- **Réseaux / e-mail** : liens GitHub, Instagram et adresse e-mail dans le fichier.
- **Couleurs** : bloc `:root` en haut du `<style>`.
