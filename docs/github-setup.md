# Publier sur GitHub (VS Code)

1. Ouvrir le dossier `ArchViz-Prompt-Library` dans VS Code.
2. Vérifier que les fichiers à publier ne contiennent aucun rendu confidentiel ni secret.
3. Se connecter à GitHub dans VS Code si nécessaire.
4. Ouvrir **Contrôle de code source**, puis cliquer sur **Initialiser le dépôt**.
5. Ajouter les changements et créer un commit, par exemple `Initial public prompt library`.
6. Choisir **Publier sur GitHub** puis **Dépôt public**.
7. Vérifier sur GitHub que `README.md`, `LICENSE.md` et `CONTRIBUTING.md` sont visibles.

Alternative en terminal (Git installé et dépôt distant déjà créé) :

```bash
git init
git add .
git commit -m "Initial public prompt library"
git branch -M main
git remote add origin https://github.com/USERNAME/ArchViz-Prompt-Library.git
git push -u origin main
```

Remplacer `USERNAME` par le compte GitHub. Les appels aux modèles d'IA peuvent être payants même si les prompts sont gratuits.
