# Boussole SES-Maths

**En ligne : https://kerhogo.github.io/boussole-ses-maths/**

Un questionnaire d'orientation post-bac pensé pour un profil précis : un élève de terminale avec les spécialités SES et maths. Il donne un profil rédigé (avec ce qui tiraille), des pistes de formations expliquées (ce qui colle, les points d'attention), des questions pour aller plus loin et un catalogue de 62 types de formations accessibles avec ces spécialités, dont des voies moins connues : hôtellerie, tourisme, luxe et mode, culture et événementiel, audiovisuel, management du sport.

Tout tient dans `index.html` : pas de compilation, pas de serveur, rien à installer.

## Mettre à jour

Remplacer `index.html`, committer et pousser sur `main`. GitHub Pages republie le site tout seul, en une minute environ.

## Ce que la page fait des réponses

- Les réponses restent dans le navigateur de la personne qui remplit (stockage local). Rien n'est envoyé à un serveur.
- **Télécharger en PDF** charge la bibliothèque [pdfmake](https://pdfmake.github.io/docs/) depuis cdn.jsdelivr.net au moment du clic, puis fabrique le fichier dans le navigateur. La première page résume tout ; le détail suit.
- **Télécharger la page HTML** produit une page autonome avec les pistes et toutes les réponses, lisible hors ligne.
- **Partager mon lien** place les réponses à la fin de l'adresse, après le `#`. Le lien sert à retrouver ses réponses sur un autre appareil, ou à les montrer à qui on veut. Cette partie de l'adresse n'est jamais transmise à GitHub. Les liens créés avec la première version restent lisibles.

## Comment les pistes sont choisies

- Chaque formation a des poids sur 8 axes (chiffres, économie, société, droit, humain, communication, numérique, international), des centres d'intérêt liés et une façon d'étudier (encadrement, concret, durée, coût, alternance…).
- Le top 5 ne contient pas plus de deux pistes du même type de formation. Si le budget n'est pas tranché, pas plus de trois écoles payantes dans les 12 premières pistes.
- « À côté de ce que tu imagines » propose jusqu'à trois voies moins connues, bien classées, qui ne sont pas déjà dans la liste.

## Contenu

Infos vérifiées début octobre 2026 : calendrier Parcoursup 2027 (vœux du 19 janvier au 12 mars 2027), fin de PASS et LAS à la rentrée 2027, admissions 2027 à Sciences Po et dans les IEP, licence Professorat des écoles, frais d'inscription 2026-2027. Chaque fiche renvoie vers une page officielle, le plus souvent Onisep. Les dates, capacités d'accueil et attendus de chaque formation se confirment sur [parcoursup.gouv.fr](https://www.parcoursup.gouv.fr) et [onisep.fr](https://www.onisep.fr).

## Versions

- **5 octobre 2026** : catalogue vérifié et élargi de 50 à 62 formations (hôtellerie, tourisme, luxe, culture et événementiel, communication, audiovisuel, sport, science politique, histoire, philosophie, BUT GACO). Portrait rédigé et tensions dans le profil, rubrique « À côté de ce que tu imagines », liens vers les fiches officielles, question sur la spécialité arrêtée en première, trois nouveaux centres d'intérêt.
- **4 octobre 2026** : première version en ligne.
