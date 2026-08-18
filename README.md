# 🔍 Analyseur de Numéro de Sécurité Sociale (NIR)

Un outil simple, rapide et visuel pour décoder et analyser un numéro de sécurité sociale français (NIR) à 15 chiffres.

## 🧠 Comment est créé un numéro de Sécurité Sociale ?

Le NIR (Numéro d'Inscription au Répertoire) n'est pas un numéro aléatoire. Il est composé de **15 chiffres** qui permettent d'identifier précisément l'état civil d'une personne. Voici sa structure détaillée :

![Schéma explicatif du NIR](https://github.com/Hackerd-825/Analyseur-de-Numero-de-Secu/blob/main/image/code_secu.webp?raw=true)

1. **Sexe (1 chiffre)** : `1` pour un homme, `2` pour une femme.
2. **Année (2 chiffres)** : Les deux derniers chiffres de l'année de naissance.
3. **Mois (2 chiffres)** : Le mois de naissance (01 à 12).
4. **Département (2 chiffres)** : Code du département de naissance (ex: 69 pour le Rhône, 2A/2B pour la Corse).
5. **Commune (3 chiffres)** : Code INSEE de la commune de naissance.
6. **Numéro d'ordre (3 chiffres)** : Numéro permettant de différencier les personnes nées au même endroit, au même moment.
7. **Clé de contrôle (2 chiffres)** : Résultat d'un calcul mathématique (Modulo 97) qui permet de vérifier si le numéro saisi est valide.

---

## 🚀 À propos du projet

Cet analyseur vous permet de décomposer n'importe quel numéro de sécurité sociale instantanément. Il est conçu pour fonctionner **entièrement en local** dans votre navigateur : aucune donnée n'est envoyée vers un serveur, garantissant une confidentialité totale.

### Fonctionnalités :
- **Analyse instantanée** : Découpage immédiat des blocs.
- **Interprétation** : Traduction des codes en informations lisibles (mois, sexe, localisation).
- **Visualisation** : Un graphique dynamique généré par *Chart.js* pour voir la répartition des données.
- **Responsive** : Design moderne avec *Tailwind CSS*, utilisable sur mobile et ordinateur.

---

## 💻 Comment l'utiliser sans Internet

Puisque cet outil est composé de fichiers HTML/JS, vous n'avez pas besoin d'une connexion internet pour le faire fonctionner une fois les fichiers téléchargés.

1. **Téléchargez le projet** : Cliquez sur le bouton "Code" > "Download ZIP" sur cette page GitHub ou clonez le dépôt.
2. **Ouvrez le fichier** : Localisez le fichier `index.html` sur votre ordinateur.
3. **Lancez l'outil** : Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur préféré (Chrome, Firefox, Edge).
4. **Utilisez** : Entrez un numéro de sécurité sociale dans la zone de saisie et cliquez sur "Analyser".

---

## 🛠️ Technologies

- **HTML5 & CSS3**
- **JavaScript (ES6+)**
- **Tailwind CSS** (pour l'interface utilisateur)
- **Chart.js** (pour la visualisation graphique)

---

## 📜 Licence
Projet libre et ouvert. N'hésitez pas à proposer des améliorations via des *Pull Requests* !
