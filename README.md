# Boussole SES-Maths

Un questionnaire d'orientation post-bac pour un élève de terminale avec les spécialités SES et maths. Il donne un profil, des pistes de formations expliquées (ce qui colle, les points d'attention), des questions à se poser et un catalogue de 47 formations accessibles avec ces spécialités.

Tout tient dans `index.html` : pas de compilation, pas de serveur, rien à installer.

## Mettre en ligne avec GitHub Pages

1. Publier ce dossier dans un dépôt **public**. Avec GitHub Desktop : *File → Add local repository*, choisir ce dossier, *create a repository*, puis *Publish repository* en décochant *Keep this code private*.
2. Sur github.com, dans le dépôt : *Settings → Pages*. Sous *Build and deployment*, choisir *Deploy from a branch*, la branche `main` et le dossier `/ (root)`, puis *Save*.
3. Au bout d'une minute environ, le site répond à l'adresse `https://kerhogo.github.io/<nom-du-dépôt>/`.

Pour mettre à jour : remplacer `index.html`, committer et pousser. GitHub Pages republie tout seul.

## Ce que la page fait des réponses

- Les réponses restent dans le navigateur de la personne qui remplit (stockage local). Rien n'est envoyé à un serveur.
- **Partager le lien** place les réponses à la fin de l'adresse, après le `#`. Cette partie de l'adresse n'est jamais transmise à GitHub : seule la personne qui reçoit le lien voit les réponses. Le bouton n'apparaît que sur la version en ligne.
- **Télécharger en PDF** charge la bibliothèque [pdfmake](https://pdfmake.github.io/docs/) depuis cdn.jsdelivr.net au moment du clic, puis fabrique le fichier dans le navigateur.
- **Télécharger la page HTML** produit une page autonome avec les pistes et toutes les réponses, lisible hors ligne.

## Contenu

Infos vérifiées début octobre 2026 : calendrier Parcoursup 2027 (vœux du 19 janvier au 12 mars 2027), nouvelle licence Professorat des écoles. Les dates, capacités d'accueil et attendus de chaque formation se confirment sur [parcoursup.gouv.fr](https://www.parcoursup.gouv.fr) et [onisep.fr](https://www.onisep.fr).
