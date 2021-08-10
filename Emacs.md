##  EMACS :
### DEPLACEMENTS :
C-v	                ->  ***Pagedown***  
M-v	                ->  ***Pageup***  
C-p                 ->  ***Ligne du dessus (previous line)***  
C-n	                ->  ***Ligne du dessous (next line)***  
C-b	                ->  ***Caractère précédent (back)***  
C-f                 ->  ***Caractère suivant (next)***  
M-b                 ->  ***Mot précédent***  
M-f                 ->  ***Mot suivant***  
C-a                 ->  ***Début de ligne***  
C-e                 ->  ***Fin de ligne***  
M-a                 ->  ***Début de phrase***  
M-e	                ->  ***Fin de phrase***  
M-<                 ->  ***Fin de fichier***  
M->                 ->  ***Début de fichier***  
C-l                 ->  ***Curseur en milieu de page***  
C-u C-v             ->  ***Curseur en haut de page***  

### COMMANDES PRINCIPALES (MENU FICHIER)
C-x C-f             ->  ***Ouvrir fichier (tab de complétion)***  
C-x C-s             ->  ***Sauvegarder fichier***  
C-x C-c             ->  ***Quitter Emacs***  
C-z                 ->  ***Sortie provisoire (récupération possible par fg ou %emacs)***  

### EDITION
C-x u	            ->  ***Annuler***  
C-x z               ->  ***Répéter***  
Suppr               ->  ***Suppression du caractère avant***  
C-d                 ->  ***Suppression du caractère après***  
M-suppr             ->  ***Suppression du mot avant***  
M-d                 ->  ***Suppression du mot après***  
C-k                 ->  ***Couper (kill) jusqu'en fin de ligne***  
M-k                 ->  ***Couper (kill) jusqu'en fin de phrase***  
C-x k	            ->  ***Couper (kill) le buffer***  
C-x C-+             ->  ***to increase***  
C-x C--             ->  ***to decrease.***  
C-espace            ->  ***Marquer (début d'un copier/couper)***  
C-w                 ->  ***Fin d'un couper (kill)***  
M-w                 ->  ***Fin d'un coller***  
M-h                 ->  ***Marque le paragraphe***  
C-x h               ->  ***Marque la totalité du buffer***  
C-x C-espace        ->  ***Coller (pop) global mark***  
C-y                 ->  ***Coller (yank du killed)***  
M-y                 ->  ***Passage entre les différents kills***  
C-s                 ->	***Recherche après (suivi de C-w recherche le mot sous le curseur)***  
C-r                 ->  ***Recherche avant (suivi de C-w recherche le mot sous le curseur)***  
M-x                 ->  ***replace-string Remplacer***  
ESC %               ->	***Remplacer***  
M-%                 ->  ***Remplacer***  
Espace              ->  ***Pour remplacer l'occurence suivante***  
Suppr	            ->  ***Pour passer l'occurence sans la remplacer***  
!                   ->  ***Pour remplacer toutes les occurences***  
M-u                 ->	***Mot en majuscule***  
M-l                 ->	***Mot en minuscule***  

### BUFFERS (fenêtrage)

C-x C-b             ->  ***Liste des buffers (fichiers ouverts)***  
C-x s               ->  ***Sauvegarde les buffers (pose la question)***  
C-x 0               ->  ***Supprime cette fenêtre***  
C-x 1	            ->  ***Supprime les autres fenêtre***  
C-x 2               ->	***Divise la fenêtre en 2 verticalement***  
C-x 3               ->  ***Divise la fenêtre en 2 horizontalement***  
C-x o	            ->  ***Passage d'un écran à l'autre (other)***  
C-x ^               ->	***Aggrandir la fenêtre***  
CV-v	            ->  ***Pagedown dans l'autre fenêtre (ESC C-v en cas de non méta)***  
C-x 4 C-f nameFile  ->  ***Ouverture de nomFichier dans une fenêtre en bas***  
C-x 4 b	            ->  ***Fermeture fenêtre***  

### DIVERS
C-u                 ->  ***chiffre	Itération d'une action (ex : C-u 5 C-n Descend de 5 lignes)***  
C-x                 ->  ***Commande suivi d'un seul caractère***  
M-x                 ->	***Commande à partir d'une commande texte (tab de complétion)***  
C-h ?               ->  ***Aide générale***  
C-h c nomCommande   ->	***Description de la commande***  
C-h k nomCommande   ->  ***Aide sur la commande***  
C-h f nomFonction	->  ***Description d'une fonction***  
C-h a nom	 	    ->  ***(Apropos) : liste les commandes contenant le nom***  
C-h i               ->  ***Lire les infos (Manuels en-ligne)***  
C-x m               ->  ***Composer un mail***  
ESC !               ->  ***Commande shell***  
