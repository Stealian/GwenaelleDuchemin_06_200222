## Installation 

Here are the dependancies you need to install:
- NodeJS 12.14 or 14.0.
- Angular CLI 7.0.2.
- node-sass : make sure to use the corresponding version to NodeJS. For Noe 14.0 for instance, you need node-sass in version 4.14+.

On Windows, these installations require to use PowerShell in administrator mode.

Then, clone this repo, run `npm install`, and run `npm install --save-dev run-script-os`.


## Usage 

Run `npm start`. This should both run the local server and launch your browser.

If your browser fails to launch, or shows a 404 error, navigate your browser to http://localhost:8080.

The app should reload automatically when you make a change to a file.

Use `Ctrl+C` in the terminal to stop the local server.

# GwenaelleDuchemin_06_200222

## Scénario
Vous avez passé la dernière année en tant que développeur back-end indépendant et vous avez travaillé sur plusieurs projets de tailles et de difficultés variées.

La semaine dernière, vous avez reçu un message sur votre plateforme de freelance vous demandant de l'aide pour un nouveau projet. Les sauces piquantes sont de plus en plus populaires, en grande partie grâce à la série YouTube « Hot Ones » . C’est pourquoi ce nouveau client, la marque de condiments à base de piment Piiquante, veut développer une application web de critique des sauces piquantes appelée « Hot Takes » .

![Desktop - 2](https://user.oc-static.com/upload/2021/07/29/16275605596354_PiiquanteLogo.png)

Piiquante : Marque de sauces piquantes

Si la responsable produit de Piiquante souhaite à terme transformer l'application d'évaluation en une boutique en ligne, elle souhaite que la première version soit une « galerie de sauces » permettant aux utilisateurs de télécharger leurs sauces piquantes préférées et de liker ou disliker les sauces que d'autres partagent. Le front-end de l'application a été développé à l'aide d'Angular et a été précompilé après des tests internes, mais Piiquante a besoin d'un développeur back-end pour construire l'API.

Le délai est raisonnable, vous décidez donc d'accepter le projet. Après avoir rencontré Paula, la cheffe de produit de Piiquante, elle vous envoie l’email suivant :

 
***
De : Paula Z
À : Me
Sujet : Besoins pour l'API

Bonjour,

Nous sommes ravis que vous contribuiez à cette nouvelle application web ! Nous sommes une petite marque, donc ce projet aura un impact important sur notre croissance.

Vous trouverez ci-joint les spécifications pour l'API. Vous pouvez également trouver un lien vers le repo du projet ici où vous aurez accès à l'interface.

Merci de faire particulièrement attention aux exigences en matière de sécurité. Nous avons récemment été victimes d'attaques sur notre site web et nous voulons être sûrs que l'API de cette application est construite selon des pratiques de code sécurisées. Tous les mots de passe des utilisateurs recueillis par l'application doivent être protégés !

Cordialement,

Paula Z
Cheffe de produit
Piiquante


Pièce jointe : 

Requirements :https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DWJ_FR_P6/Requirements_DW_P6.pdf
***

Vous êtes prêt à vous lancer dans l'API ! C’est parti !

## Livrables

Pour faciliter votre passage au jury, mettez le livrable sur la plateforme dans un dossier nommé « P6_prenom_nom » .

Un fichier zip contenant le code de l'API, nommé « P6_prenom_nom_code.zip » (en remplaçant « prenom » et « nom » par votre prénom et nom).

##Soutenance
Pendant la présentation orale, votre évaluateur jouera le rôle de Paula, la cheffe de produit de Piiquante. L'évaluateur challengera vos décisions, préparez-vous donc à défendre votre travail.

Lorsque votre évaluateur aura téléchargé votre code, il exécutera “npm install” à partir de la racine du projet. Il doit ensuite être en mesure d'exécuter le serveur node (ou le serveur nodemon) pour faire tourner votre API.

La présentation sera structurée comme suit :

- Présentation du livrable (15 minutes)
	- Expliquez le fonctionnement de votre code, en particulier les éléments qui ne peuvent pas être vérifiés à l'aide de l'application front-end, comme votre middleware d'authentification. Vous devrez partager votre écran pour faire votre démonstration.
	- Expliquez la structure de votre code (contrôleurs, routeurs, etc.) et les raisons pour lesquelles vous avez choisi cette structure spécifique.
	- Expliquez vos méthodes pour sécuriser la base de données selon le RGPD et l’OWASP.
- Discussion (10 minutes)
	-Jouant le rôle du cheffe de produit, l'évaluateur vous posera des questions sur votre méthodologie et votre livrable. Par exemple, il peut vous challenger sur :
	- Votre choix de versions de logiciels, de plugins et de services.
	- Votre approche pour protéger les données des utilisateurs et sécuriser l'API. 
- Débriefing (5 minutes)
	- À la fin de la session, l'évaluateur cessera de jouer le rôle du cheffe de produit afin que vous puissiez débriefer ensemble.
Votre présentation devrait durer 15 minutes (+/- 5 minutes).  Puisque le respect des durées des présentations est important en milieu professionnel, les présentations en dessous de 10 minutes ou au-dessus de 20 minutes peuvent être refusées. 

## Compétences évaluées
- Implémenter un modèle logique de données conformément à la réglementation
- Stocker des données de manière sécurisée
- Mettre en œuvre des opérations CRUD de manière sécurisée
