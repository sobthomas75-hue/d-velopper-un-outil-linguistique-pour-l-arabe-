# LughaLearn — Apprendre l'arabe, une leçon à la fois

**LughaLearn** est une application web éducative, gratuite et open source, destinée aux débutants francophones qui veulent découvrir l'alphabet arabe et des mots courants.

## Fonctionnalités (MVP v0.1)
- 28 lettres arabes interactives avec transcription et indications phonétiques ;
- prononciation synthétique via l'API Web Speech (selon les voix installées) ;
- huit cartes de vocabulaire arabe–français ;
- quiz de cinq questions aléatoires avec retour immédiat ;
- suivi local des lettres, mots explorés et du meilleur score ;
- interface responsive et navigation accessible au clavier.

## Démarrage

Ouvrez `index.html` dans un navigateur récent. Aucun serveur, compte, téléchargement de dépendances ni clé API ne sont nécessaires.

## Publication gratuite avec GitHub Pages

Dans le dépôt GitHub : **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**. Attendez que GitHub affiche l'URL du site publié.

## Structure
- `index.html` : structure accessible de l'interface.
- `styles.css` : mise en page responsive.
- `app.js` : données pédagogiques, quiz, synthèse vocale et stockage local.

## Limites connues
- Le contenu représente une **introduction** et non un cours d'arabe complet.
- La synthèse vocale dépend de l'appareil et ne remplace pas des enregistrements validés par des locuteurs.
- Les formes contextuelles des lettres, les voyelles brèves et la grammaire ne sont pas encore enseignées.
- La progression reste sur le navigateur via `localStorage` ; elle ne se synchronise pas entre appareils.

## Feuille de route
1. Faire relire les données linguistiques par des enseignants d'arabe.
2. Introduire les formes initiale, médiane et finale des lettres.
3. Ajouter des enregistrements audio et exercices d'écoute.
4. Ajouter une banque de leçons sous licence ouverte, testée et versionnée.
5. Envisager les interfaces et contenus pour d'autres langues.

## Contribuer
Consultez [CONTRIBUTING.md](CONTRIBUTING.md). Toute contribution linguistique doit être sourcée ou validée.

## Licence
MIT — voir [LICENSE](LICENSE).
