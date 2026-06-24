# LaManiguette — site vitrine

Site vitrine pour **LaManiguette**, restaurant bistronomique spécialisé dans la viande (Lyon, Croix-Rousse).
Fichier unique, autonome : HTML, CSS et JavaScript inlinés. Aucune dépendance à installer.

## Aperçu

- Hero avec photo plein cadre + « échelle de cuisson » (signature visuelle)
- Carte chiffrée, formules, avis, FAQ accessible
- Module de réservation (mardi → samedi, déjeuner / dîner, créneaux, couverts)
- Responsive mobile-first, contraste WCAG AA, navigation clavier, `prefers-reduced-motion`

Les photos proviennent d'Unsplash (chargées par URL) avec repli CSS. Remplacez-les
par vos propres clichés dans le bloc `imgs` du `<script>` (en bas de `index.html`).

## Lancer en local

Ouvrez simplement `index.html` dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Mettre en ligne (GitHub Pages)

Une fois le dépôt poussé sur GitHub, activez Pages :
**Settings → Pages → Source : Deploy from a branch → Branch : `main` / `/root` → Save.**
Le site sera disponible à `https://<votre-pseudo>.github.io/test-website-restaurant-viande/`.

## Structure

```
.
├── index.html      # le site complet (autonome)
└── README.md
```
