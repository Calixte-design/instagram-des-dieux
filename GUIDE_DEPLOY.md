GUIDE — Déployer sur GitHub Pages (simple pour débutants)
========================================================

1) Crée un compte sur https://github.com si tu n'en as pas.
2) Crée un nouveau dépôt (repository). Nomme-le, par exemple, `instagram-des-dieux`.
3) Sur ta machine:
   - Dézippe le fichier fourni.
   - Ouvre Git Bash (ou terminal).
   - Navigue vers le dossier du projet.
   - Initialiser le repo local:
       git init
       git add .
       git commit -m "Initial commit - Instagram des Dieux"
       git branch -M main
       git remote add origin https://github.com/TON_PSEUDO/instagram-des-dieux.git
       git push -u origin main
   (Si tu préfères, tu peux uploader les fichiers via l'interface web GitHub en cliquant sur 'Add file' > 'Upload files'.)

4) Activer GitHub Pages:
   - Va dans l'onglet Settings du repo.
   - Clique sur 'Pages' dans le menu à gauche.
   - Sous 'Build and deployment', choisis 'Deploy from a branch'.
   - Sélectionne la branche 'main' et le dossier '/'.
   - Clique 'Save'. GitHub déploiera ton site en quelques minutes.
   - L'URL sera: https://TON_PSEUDO.github.io/instagram-des-dieux

Astuce: si tu veux modifier le contenu en ligne, fais des commits locaux puis pousse sur GitHub — le site se mettra à jour automatiquement.
