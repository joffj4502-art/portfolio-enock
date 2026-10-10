# Portfolio d'Enock — HTML & CSS

Un portfolio personnel responsive réalisé uniquement en HTML et CSS (aucun JavaScript, aucun framework).

## Fichiers

- `index.html` : contenu et structure du site.
- `style.css` : mise en page, couleurs et adaptation aux téléphones/tablettes.

## Tester sur l'ordinateur

1. Télécharge et décompresse le dossier.
2. Ouvre `index.html` dans ton navigateur.
3. Garde `index.html` et `style.css` dans le même dossier.

## Personnaliser avant publication

Dans `index.html`, remplace :

- `tonadresse@example.com` par ton adresse e-mail publique (ou modifie le bouton de contact).
- `https://github.com/ton-pseudo` par l'adresse de ton profil GitHub.
- Le nom, la description, les compétences et les projets selon tes besoins.

Le site n'a besoin d'aucune police ou bibliothèque externe : les polices système sont utilisées pour qu'il reste lisible même hors ligne. Tout le style se trouve dans `style.css`.

## Publier avec GitHub Pages

1. Connecte-toi à GitHub et crée un dépôt public nommé `portfolio-enock`.
2. Dans le dépôt, choisis **Add file → Upload files**.
3. Envoie `index.html`, `style.css` et `README.md` (les fichiers, pas seulement le dossier ZIP).
4. Clique sur **Commit changes**.
5. Ouvre **Settings → Pages**.
6. Dans **Build and deployment**, choisis **Deploy from a branch**.
7. Choisis la branche `main` et le dossier `/(root)`, puis clique sur **Save**.
8. Après quelques minutes, GitHub Pages affichera l'adresse publique du site dans la page **Settings → Pages**.

Le site est statique : le formulaire/contact n'envoie pas de message en arrière-plan ; le bouton e-mail ouvre l'application de messagerie du visiteur. Aucun mot de passe ou compte utilisateur n'est demandé.
