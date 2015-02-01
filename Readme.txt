Pour faire "runner" les jeux:

- Télécharger un fichier de jeu incluant un Chrome HTML Document et un .unity3d
- Exécuter le fichier HTML, avec le .unity3d dans le même dossier
- Activer les plug-ins si nécessaire

Notes:

Move-a-ball:

- Des formes ont été ajoutés pour créer des obstacles
- Un nouveau GameObject avec un tag différent et un matérial différent a été ajouté
pour se familiariser avec les tags et textures
- Un GUIText a été ajouté pour expliquer les différentes missions

Space Shooter:

- Un GUIText a été ajouté pour expliquer les contrôles du jeu
- Une augmentation du nombre d'astéroides par vagues a été implémentée
- Un GUIText a été ajouté par indiquer au joueur à quelle vague il est.
- Une implémentation a permise d'indiquer le nombre d'astéroides restants
à la vague pour se familiariser avec l'ensemble du code.
- Un GUIText a été ajouté pour expliquer à l'utilisateur qu'il doit attendre
que la vague finisse pour pouvoir commencer une nouvelle partie.
- Un GUIText pour indiquer à quel vague l'utilisateur a perdu et quel est
son score final

Survival shooter:

- Aucune implémentation supplémentaire 
- Cependant, problème avec l'exportation du jeu:
	- Les icônes de coeur et la slider bar s'affichent incorrectement
	- Le score de s'affiche pas dans toutes les scènes
	- Le UI Text Game Over ne s'affiche pas lors de l'écran bleu
- Note: Toutes ces implémentations marchent sur Unity3D sur mon ordinateur.