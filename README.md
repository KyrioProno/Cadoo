# 🎄 Cadoo

**Cadoo** est une application mobile d’idées de cadeaux de Noël, entièrement autonome dans un seul fichier `index.html` (aucune dépendance externe, aucun appel réseau).

## Fonctionnalités

- **Accueil festif** : neige qui tombe, compte à rebours avant Noël, ton léger et drôle.
- **Calendrier de l’avent des idées** : 25 cases avec porte qui s’ouvre en animation 3D. Seules les cases jusqu’à la date du jour (1er → 25 décembre) sont ouvrables, les autres sont verrouillées 🔒. Bouton **Mode test** pour tout débloquer.
- **Un cadeau pour quelqu’un** : questionnaire en 5 questions à gros boutons tactiles (pour qui, âge, budget, centres d’intérêt en multi-sélection, style), puis 3 idées personnalisées grâce à un algorithme de matching sur **162 idées intégrées** (taguées par destinataire, âge, budget, intérêts et style). Boutons « Autre idée » et « Garder en favori ».
- **Mes idées** : favoris persistés (localStorage protégé par try/catch), regroupés par personne, avec **copie de la liste en texte** pour la partager.
- **Bonus** : bouton « Surprends-moi » (idée au hasard), petits sons de grelots (WebAudio) et vibrations optionnels via le bouton 🔔, design mobile-first utilisable d’une main avec navigation en bas d’écran.

## Utilisation

Ouvrez simplement `index.html` dans un navigateur (ou servez le dossier avec n’importe quel serveur statique). Aucune installation, aucune inscription : on ouvre, on trouve, on offre. 🎁
