# Programme Major de Promo — VERSION TEST

Ceci est une version TEST, séparée de LAST-ONE. Déploie-la sur un nouveau dépôt/lien 
(ou une branche à part) pour ne pas toucher à ton site actuel pendant que tu l'essaies.

## Nouveautés de cette version test

### 1. Blocs de l'emploi du temps interchangeables
Dans "Emploi du temps", bouton "✎ Modifier" en haut à droite : 
- ▲▼ pour réordonner un bloc
- ✎ pour modifier son horaire/titre/détail (l'horaire est un texte libre, pas une horloge — 
  écris-le comme tu veux)
- ✕ pour le supprimer
- "+ Ajouter un bloc" en bas de la liste
- "↺ Réinitialiser ce jour" pour revenir au contenu d'origine si besoin

Le Tracker se raccorde automatiquement : chaque bloc a un identifiant propre, donc déplacer, 
renommer ou réordonner un bloc ne fait pas perdre son historique de cases cochées. Seule la 
SUPPRESSION d'un bloc perd son historique (logique, puisqu'il n'existe plus), et un bloc 
totalement NOUVEAU démarre sans historique (normal aussi).

### 2. Import PDF de l'emploi du temps — expérimental
Bouton "📄 Importer PDF" à côté de "✎ Modifier". Fonctionne en 3 étapes : lecture du PDF (texte 
uniquement, pas les PDF scannés/images), détection automatique des jours et horaires, puis un 
aperçu éditable où tu corriges avant de valider — rien n'est appliqué sans ton accord explicite.

Limite réelle à connaître : ça fonctionne correctement sur un PDF texte listant les jours en 
agenda simple (jour, puis liste horaire/matière). Un emploi du temps en grille/tableau (type 
Hyperplanning, ADE, Wigor...) a de bonnes chances d'être mal interprété, car un PDF ne contient 
pas de vraies "cases" de tableau — juste du texte positionné, que l'outil essaie de reconstituer 
en lignes. Teste avec ton vrai PDF et dis-moi ce qui coince pour que j'ajuste le parsing à ton 
format exact.

### 3. Onglet Stages
Nouveau module séparé du tracker scolaire :
- Établissement, service, dates, horaires
- Objectifs & compétences à travailler
- Journal & observations (dates, avec un type : Journal quotidien / Acte observé / Acte réalisé / 
  Situation clinique / Transmission)
- Questions à rechercher après le stage (liste à cocher)
- Cours/fiches liés (tape le nom d'un cours de ton Suivi pour le relier au stage)
- Bilan de fin de stage

Le statut (à venir / en cours / terminé) se calcule automatiquement à partir des dates.

## Ce qui n'a PAS changé
Dashboard, Suivi Cours, TD, QCM, Planning, Bilan, Méthodes, Conseils, Next Action, Export/Import 
sont identiques à LAST-ONE. Je n'ai pas touché à la méthode de spaced repetition (toujours 
J+0/J+3/J+7/J+30) ni ajouté de système de score de rétention — ces deux points n'étaient pas 
dans ta demande finale, donc je les ai laissés de côté pour rester focalisé sur ce que tu as 
vraiment demandé.
