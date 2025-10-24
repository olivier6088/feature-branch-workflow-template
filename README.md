# 🧪 TP Git : Workflow de branche de fonctionnalité

Bienvenue dans ce dépôt de TP Git ! Ce projet est conçu pour pratiquer le **workflow de branche de fonctionnalité** en équipe.

## 🎯 Objectifs

- Créer une branche pour chaque fonctionnalité.
- Travailler en parallèle sans impacter `main`.
- Utiliser les pull requests pour collaborer et fusionner proprement.

## 🚀 Instructions

1. Clone ce dépôt :
   ```bash
   git clone https://github.com/<ton-org>/feature-branch-workflow-template.git
   cd feature-branch-workflow-template
   ```

2. Crée une branche avec ton prénom et ta tâche :
   ```bash
   git checkout -b sebastien-add-footer
   ```

3. Modifie le fichier `main.py` ou ajoute un fichier dans `utils/`.

4. Commit et push ta branche :
   ```bash
   git add .
   git commit -m "Ajout du footer par Sébastien"
   git push -u origin sebastien-add-footer
   ```

5. Ouvre une pull request vers `main`.

6. Relis la PR d’un camarade et laisse un commentaire.

7. Fusionne la PR une fois validée.

## 📂 Dossiers utiles

- `main.py` : point d’entrée du projet.
- `utils/` : fonctions utilitaires à enrichir.
- `docs/` : instructions et documentation.
- `.github/workflows/ci.yml` : exemple de pipeline CI (optionnel).

## 👥 Exemples de branches

- `fidel-login-form`
- `gael-navbar-update`
- `olivier-api-refactor`
- `dorian-fix-bug-42`
- `anna-add-tests`

---

Bon TP ! 💻

