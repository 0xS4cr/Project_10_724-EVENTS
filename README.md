# 724 EVENTS

## Mission de Développement Front-End

Je suis développeur front-end freelance, et l’agence évènementielle 724events me contacte pour une mission.

L’agence souhaite publier la nouvelle version de son site vitrine. Il s’agit d’un site one-page.

Le design a été validé, et un premier développeur freelance a commencé l’intégration il y a quelques semaines. Malheureusement, ce freelance a dû abandonner le projet pour raisons personnelles. Le site est fonctionnel, mais quelques bugs entravent le bon usage par les visiteurs. 724events fait donc appel à mes services pour finaliser le travail.

Je rencontre Jean-Baptiste, le directeur Marketing de l’agence, en visioconférence pour qu’il me présente plus précisément le projet.

---

### Tâches à Réaliser

#### 1) Fork du projet

- Fork du projet : [lien vers le projet](https://github.com/OpenClassrooms-Student-Center/Debuggez-une-application-React.JS)

#### 2) VSCode cloner le dépot git créé suite au fork + installation de Yarn

- Cloner le dépôt depuis VSCode.
- Installer Yarn :
    - Vérifier si Node et NPM sont installés (sinon les installer) :
        - Commande : `node -v`
        - Commande : `npm -v`
    - Installer le package Yarn :
        - Commande : `npm install --global yarn`
        - Vérifier si bien installé :
            - Commande : `yarn -v`
        - Installer Yarn dans le projet :
            - Commande : `yarn install`
        - Démarrer le serveur de développement :
            - Commande : `yarn start` (équivalent à `npm start` sous npm ou `npm run dev` sous ViteJS) **ATTENTION : serveur en mode Développement**

#### 3) Installation et Configuration de React Dev Tools

- Installer l'extension React Dev Tools compatible avec votre navigateur (extension de navigateur classique).
- Sur VS Code :
    - Commande : `yarn start`
- Sur le navigateur dans lequel l'installation React Dev Tools est installée, faire :
    - Clic droit -> Inspecter -> Dans les onglets à droite : "Components"

#### 4) Effectuer les Tests pour Voir les Problèmes

- Lancer les tests :
    - Commande : `yarn test --watch`
- Lister les tests échoués.

#### 5) Correction des Erreurs Lors des Tests

- Correction des bugs signalés dans le fichier Issues.

#### 6) Ajout de Tests à la Section Home/index.test.js

**ATTENTION : le fichier JSON comporte des erreurs au niveau des dates.**

---

