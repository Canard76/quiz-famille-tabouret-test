
# Quiz soirée – Parents & Ados

Ce paquet contient un quiz en JSON et une page HTML pour jouer en famille (parents & adolescents), avec timer de 30 secondes et alerte rouge les 10 dernières secondes.

## Fichiers
- `index.html` — l'application web qui charge `quiz.json`
- `quiz.json` — les 40 questions QCM + configuration de timer

## Publier sur GitHub Pages
1. Créez un nouveau dépôt GitHub **public** (ex. `quiz-soiree-famille`).
2. Ajoutez ces fichiers à la racine du dépôt (`index.html`, `quiz.json`, `README.md`).
3. Validez et poussez :
   ```bash
   git add .
   git commit -m "Quiz parents-ados + timer"
   git push
   ```
4. Activez **GitHub Pages** : Settings → Pages → *Deploy from a branch* ; branche `main` ; répertoire `/root`.
5. Ouvrez l'URL GitHub Pages : la page `index.html` chargera automatiquement `quiz.json`.

Bon jeu !
