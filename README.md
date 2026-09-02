##Version 1.0.1

**ÉVOLUTIONS**

- Création d'une page de maintenance liée aux fiches métadonnées en redirection temporaire 302 avec paramètre d'activation;
- #127 Révision du comportement de fermeture du détail volet de droite;
- Filtrage des taxons en fonction du/des groupes taxonomique sélectionnés;
- Révision général du menu de gauche;
- #116 Révision de la légende et de l'échelle utilisée : l'échelle varie dorénavant en fonction de l'étendu géographique et du nombre max d'observation;
- Révision générale des contenus;
- Révision générale des informations du détail dans le panneau droit (nombre d'observation, affichage du code insee et de la commune, code grille etc..);
- "Recherche par géométrie" (toujours en cours de développement) appliqué sur les couches environnementales;
- Révision de l'emplacement du bouton "Appliquer / Réinitialiser" maintenant positionné en haut du menu de gauche et toujours visible;
- Révision du comportement général des menus, fenêtres modales et toasters de chargements;
    
    
**CORRECTIFS**

- Hotfix : correctif suite régression sur css => le tutoriel ne redonner pas la main;
- #126 Modification de l'url pour les métadonnées afin qu'elles pointent sur le datahub;
- Correctif sur les textbox de recherche de taxon qui supprimait des taxons de la liste de recherche, nécessitant de les saisir une nouvelle fois;
- Réinitialisation du filtre date lors d'une nouvelle recherche ou de la réinitialisation des filtres

## Version 1.0.0 (tests) Release Notes

Cette version est dédiée aux premiers retours utilisateurs, les données utilisées sont issues du dernier import de l'extraction INPN réalisé en 2025. Elle comprend :

- Les premiers filtres généraux sur :
  - Groupes taxonomiques
  - Taxons
  - Limites temporelles
  - Limites géographiques
    - Départements
    - Communes
- Un composant Filtres Avancés que l'on peut utiliser en fenêtre flottante ou dans la barre latérale
- Les couches de restitution suivantes :
  - Commune
  - Grille 5x5 nationale
  - Grille 10x10 nationale
- Quelques exemples de couches thématiques dédiées à l'environnement : cette partie fera l'objet d'une refonte complète via l'intégration d'une fonctionnalité dédiée.
- Quelques couches de limites administratives
- Une fenêtre d'accueil : le contenu final n'étant pas finalisé, les textes sont remplacés temporairement par du lorem ipsum.
- Un tutoriel de première connexion
- Quelques fiches métadonnées intégrées partiellement pour la phase de test (ces fiches sont actuellement incomplètes, les flux permettant leur téléchargement n'étant pas implémentés).

Elle ne comprend pas :

- Le design final de l'application et sa compatibilité avec tablettes et smartphones (responsive design). Quelques adaptations ont toutefois déjà été implémentées
- L'intégralité des données des pôles du SINP Hauts-de-France
- La compatibilité avec la recherche générique de mviewer
- D'options de filtrage avancé
