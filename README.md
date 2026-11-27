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
| `projet-04-cover.png` | Visuel du 4e projet |

## Images des études de cas

Chaque étude de cas prévoit des emplacements facultatifs. Tant que l'image n'existe pas, l'emplacement est masqué sur le site, ainsi que la section si elle est vide ; la numérotation et le sommaire s'ajustent seuls. Pour l'afficher, déposer dans `assets/` un fichier nommé `<id>-<emplacement>.png` :

| Emplacement | Nom du fichier |
| --- | --- |
| Wireframes | `<id>-wireframe-1.png`, `<id>-wireframe-2.png`, `<id>-wireframe-mobile.png` |
| Mockups | `<id>-mockup-desktop.png` (16:10), `<id>-mockup-mobile-1.png` à `-3.png` (9:16) |
| Détails | `<id>-detail-1.png`, `<id>-detail-2.png` |
| Ike Oluwa (UX) uniquement | `acm-ui-cover.png`, `acm-ui-parcours-utilisateur.png`, `acm-ui-interface.png` |

Identifiants : `planpoitrines-maquette`, `gardeco`, `acm-ui`, `kuriosity`, `noor`, `rj10`.

Les projets de développement (Plan Poitrines vitrine, Ike Oluwa back-end, WR506D, WR602D) n'ont pas de page dédiée : ils sont présentés en cartes sur l'accueil.

Certains emplacements utilisent déjà une image existante (par exemple `rj10-wireframe.png` à la place de `rj10-wireframe-1.png`) : seuls les emplacements encore libres suivent la règle ci-dessus.

## Ajouter une étude de cas

1. Dupliquer une page `<div id="page-..." class="page cs-page">` dans `index.html`, changer son `id` et les préfixes des identifiants de sections.
2. Dupliquer un bloc `<article>` de la section Projets UX/UI et pointer `showProject('...')` vers le nouvel identifiant.
