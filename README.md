# Page de Vérification - Générateur de Code de Vérification

Ce projet est une simple page web permettant de générer un code de vérification aléatoire et de le comparer avec l'entrée utilisateur. Le code de vérification est composé de caractères alphanumériques (0-9 et a-f) et permet à l'utilisateur de valider un formulaire avec le bon code.


## Capture d'écran principale

![Capture principale](./images%20de%20la%20fin/principal.png)

## Exemple de code incorrect

![Code incorrect](./images%20de%20la%20fin/incorrect.png)

## Exemple de succès

![Succès](./images%20de%20la%20fin/succes.png)



## Fonctionnalités

- Génération de codes de vérification aléatoires (6 caractères).
- Possibilité de générer un nouveau code si celui affiché est illisible.
- Validation de l'entrée utilisateur contre le code généré.
- Affichage d'un message d'alerte si le code est incorrect.

## Technologies Utilisées

- **HTML5** : Structure de la page.
- **CSS3** : Stylisation de la page.
- **JavaScript** : Logique de génération et de validation des codes.

## Installation et Utilisation

1. **Cloner le dépôt** :
    ```bash
    git clone https://github.com/votre-utilisateur/nom-du-projet.git
    ```

2. **Accéder au dossier du projet** :
    ```bash
    cd nom-du-projet
    ```

3. **Ouvrir le fichier `index.html`** dans un navigateur pour tester l'application localement.

## Fonctionnement

- Au chargement de la page, un code de vérification aléatoire est généré et affiché.
- L'utilisateur peut entrer ce code dans le champ prévu à cet effet.
- En cliquant sur le bouton **"Valider"**, le code saisi est comparé au code affiché. Si les deux correspondent, un message de confirmation s'affiche. Sinon, un message d'erreur apparaît et le champ d'entrée est réinitialisé.
- Si le code est difficile à lire, l'utilisateur peut cliquer sur **"Changer si illisible"** pour générer un nouveau code.

## Structure du Projet

```bash
nom-du-projet/
│
├── index.html         # Fichier HTML principal
└── README.md          # Ce fichier de documentation

