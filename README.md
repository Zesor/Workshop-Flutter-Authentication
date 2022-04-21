# Workshop-Flutter-Authentication
Le workshop potera sur l'authentification avec Flutter et Firebase.

# Workshop 1 - Introduction au développement mobile avec Flutter !

# Step 0 : Setup ❗

Toutes les infos relatives à la préparation du workshop sont disponibles dans le SETUP.md

Veillez à avoir terminé ses étapes avant de passer à la suite.

Un lien vers la documentation Flutter est également disponible : https://docs.flutter.dev/

## Step 01 : Premiers pas et explication de la synthax flutter et dart. 🖥️

Dart est un langage de programmation polyvalent open source. Il est à l’origine développé par Google.
Dart est un langage orienté objet avec une syntaxe de style C. Il prend en charge les concepts de programmation tels que les interfaces,
les classes, contrairement aux autres langages de programmation Dart ne prend pas en charge les tableaux. Les collections de fléchettes
peuvent être utilisées pour répliquer des structures de données telles que des tableaux, des génériques et une saisie facultative.

Le framework Flutter offre les fonctionnalités suivantes aux développeurs -

Cadre moderne et réactif.
Utilise le langage de programmation Dart et il est très facile à apprendre.
Développement rapide.
De belles interfaces utilisateur fluides.
Grand catalogue de widgets.
Exécute la même interface utilisateur pour plusieurs plates-formes.
Application haute performance.

## Step02 : Créer un formulaire de connexion ⛷️

Sur Flutter, il existe un widget qui permet de créer de facilement créer un widget de connexion.
  • Créer une page 'Login' qui permettra aux utilisateurs déja existant de se connectés,
      dans cette page, vous devez créer un champ pour l'addresse mail et un champ pour le mot de passe,
      un bouton pour accepter la connexion et un bouton pour rediriger l'utilisateur sur une page de création de compte
      s'il n'est pas register.
  • Créer une page 'SignUp' qui permettra aux utilisateurs de créer leurs comptes,
      dans cette page, vous devez créer un champ pour l'addresse mail et un champ pour le mot de passe,
      un champ pour confirmer le mot de passe, un champ pour le nom, un pour le prénom,
      un bouton pour accepter la connexion et un bouton pour rediriger l'utilisateur sur une page de création de compte
      s'il n'est pas register.
      
La suite est évidente :) il faut créer une classe qui va gérer vos utilisateurs.

## Step03: Créer un nouveau projet sur Firebase.

Ok c'est good on a notre UI, maintenant faut faire la partie back-end.
Pour cela on va utiliser Firebase: https://firebase.google.com/
Connecter vous avec un compte google (votre adresse mail perso fera l'affaire)
Créer un nouveau projet pour android ou IOS, et suivez les étapes.
Allez dans authentication et activer l'authentification avec email/password.
Ensuite retournez dans votre code et implémenter les fonctions d'authentification.

## Contributors: Illyas Chihi, Valentin Fouillet
