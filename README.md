# Mission Lexo

Application web d'entraînement au français pour Octave : un monde de blocs en pixels (univers original), 49 missions du CE1 au CE2, un hibou compagnon (Plume), des astuces progressives et des coffres de récompenses réelles.

- Un seul fichier : `index.html` (aucune dépendance, polices incluses).
- Compte de sauvegarde : adresse e-mail et mot de passe (Supabase). La progression se retrouve sur tous les appareils connectés au compte.
- Accessibilité : clavier, lecteur d'écran, trois thèmes dont un contraste fort, texte jusqu'à 140 %, animations réduites, police lisible (Andika).

## Publication

Chaque modification poussée sur la branche `main` est en ligne en une à deux minutes (GitHub Pages, dossier racine).

Fichiers : `index.html`, `.nojekyll`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`.

## Base de données

Table `public.lexo_progress` (`user_id`, `data`, `ts`, `updated_at`) avec sécurité par ligne : chaque utilisateur ne lit et n'écrit que sa propre ligne.

## Note

Univers graphique original, inspiré des jeux de construction en blocs. Aucun logo, personnage ou élément d'une marque existante n'est utilisé.
