# Portfolio UX/UI — Nimotalah Alli

Portfolio statique (HTML, Tailwind CSS via CDN), publié avec GitHub Pages.

## Ajouter des images

Les emplacements d'images s'affichent en pointillés tant que le fichier correspondant n'existe pas dans `assets/`. Il suffit de déposer le fichier avec le nom attendu :

| Fichier | Emplacement |
| --- | --- |
| `photo-profil.jpg` | Photo du hero (4:5) |
| `photo-about.jpg` | Photo de la section À propos (4:5) |
| `cv-nimotalah-alli.pdf` | CV téléchargeable |
| `logo-acm.png`, `logo-rj10.png`, `logo-planpoitrines.png`, `logo-parfumerie.png` | Logos de la section Expérience |
| `acm-ui-*.png` | Étude de cas Ike Oluwa (couverture, wireframes, écrans, design system, parcours) |
| `projet-04-cover.png` | Visuel du 4e projet |

## Ajouter une étude de cas

1. Dupliquer le bloc `page-acm-ui` dans `index.html` et changer son `id`.
2. Dupliquer un bloc `<article>` de la section Projets UX/UI et pointer `showProject('...')` vers le nouvel identifiant.
