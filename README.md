# TP 2 - NEXUS League

## Mission

Vous intégrez le site multipage d'une ligue e-sport fictive à partir des maquettes fournies. Les trois pages partagent la même identité graphique et la même feuille CSS.

## Durée

4 h 30.

## Pages attendues

| Fichier | Rôle |
|---|---|
| `index.html` | Accueil, chiffres clés, jeux mis en avant et manifeste |
| `tournois.html` | Présentation détaillée des quatre compétitions |
| `inscription.html` | Formulaire d'inscription d'une équipe |

## Compétences travaillées

Structure sémantique, navigation multipage, chemins relatifs, mutualisation du CSS, Flexbox, Grid, superposition contrôlée, formulaires HTML, responsive et accessibilité.

## Contraintes

1. Les trois pages utilisent une seule feuille `assets/style.css`.
2. L'en-tête et le pied de page conservent exactement la même structure.
3. Le lien correspondant à la page courante porte `aria-current="page"`.
4. Les titres suivent une hiérarchie cohérente et chaque page ne contient qu'un seul `h1`.
5. Utiliser `figure`, `article`, `time`, `dl`, `fieldset` et `legend` lorsque leur sémantique est pertinente.
6. Tous les champs possèdent un `label` explicitement associé.
7. Les champs obligatoires sont validés nativement par HTML, sans JavaScript.
8. Le contenu est utilisable au clavier et le focus reste visible.
9. La grille de cartes change réellement de composition sur tablette et mobile.
10. Aucun défilement horizontal ne doit apparaître à 390 px.
11. Les images ne doivent pas être déformées.
12. Aucun framework, style en ligne ou JavaScript n'est autorisé.

## Informations du formulaire

Le formulaire demande le tournoi, le nom de l'équipe, le nombre de joueurs, le niveau, le nom et l'adresse e-mail du capitaine, une courte présentation et l'acceptation du règlement.

## Vérifications

- test des trois pages à 1440 px, 850 px, 640 px et 390 px ;
- navigation entre toutes les pages sans lien cassé ;
- validation HTML W3C de chaque page ;
- test du formulaire avec des champs vides et une adresse e-mail incorrecte ;
- désactivation du CSS pour contrôler l'ordre du contenu.

Une modification fonctionnelle ou graphique courte sera communiquée en fin de TP.
