# Boussole SES-Maths

**En ligne : https://kerhogo.github.io/boussole-ses-maths/**

Un questionnaire d'orientation post-bac pensé pour un profil précis : un élève de terminale avec les spécialités SES et maths. Il donne un profil, des pistes de formations expliquées (ce qui colle, les points d'attention), des questions à se poser et un catalogue de 50 formations accessibles avec ces spécialités.

Tout tient dans `index.html` : pas de compilation, pas de serveur, rien à installer.

## Mettre à jour

Remplacer `index.html`, committer et pousser sur `main`. GitHub Pages republie le site tout seul, en une minute environ.

## Ce que la page fait des réponses

- Les réponses restent dans le navigateur de la personne qui remplit (stockage local). Rien n'est envoyé à un serveur.
- **Télécharger en PDF** charge la bibliothèque [pdfmake](https://pdfmake.github.io/docs/) depuis cdn.jsdelivr.net au moment du clic, puis fabrique le fichier dans le navigateur.
- **Télécharger la page HTML** produit une page autonome avec les pistes et toutes les réponses, lisible hors ligne.
- **Partager mon lien** place les réponses à la fin de l'adresse, après le `#`. Le lien sert à retrouver ses réponses sur un autre appareil, ou à les montrer à qui on veut. Cette partie de l'adresse n'est jamais transmise à GitHub.

## Contenu

Infos vérifiées début octobre 2026 : calendrier Parcoursup 2027 (vœux du 19 janvier au 12 mars 2027), nouvelle licence Professorat des écoles. Les dates, capacités d'accueil et attendus de chaque formation se confirment sur [parcoursup.gouv.fr](https://www.parcoursup.gouv.fr) et [onisep.fr](https://www.onisep.fr).
