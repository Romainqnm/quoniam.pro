# QUONIAM Hub

Hub visuel immersif pour les produits QUONIAM, développé avec Astro.

Le site présente 4 dimensions produit avec des animations CSS pures, une identité visuelle bleu/violet premium et des transitions de navigation fluides.

## Aperçu

- Home hub: portail principal avec cartes interactives animées
- Quoniam Audio: univers orchestral génératif
- Quoniam Vision: univers synthwave et tunnels de fréquences
- Quoniam Prisma: univers prismes/lumière
- Quoniam Nexus: univers data/matrice

## Stack

- Astro
- HTML/CSS (animations CSS natives, sans librairie d’animation JS)
- View Transitions (`astro:transitions`)

## Routes

- `/`
- `/quoniam-audio`
- `/quoniam-vision`
- `/quoniam-prisma`
- `/quoniam-nexus`

## Lancer le projet

Depuis la racine:

```bash
npm install
npm run dev
```

Build production:

```bash
npm run build
npm run preview
```

## Structure utile

```text
src/
	assets/
		logo.png
		icone_audio.png
	pages/
		index.astro
		quoniam-audio.astro
		quoniam-vision.astro
		quoniam-prisma.astro
		quoniam-nexus.astro
```

## Notes

- Le design est volontairement immersif et orienté “portal UX”.
- Les effets visuels sont principalement gérés en CSS (gradients, masques, keyframes).
- Le projet est actuellement en première version fonctionnelle (v1 initiale).
