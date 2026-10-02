<p align="center">
  <img src="./Logo_indirecte.png" alt="logo" width="100%">
</p>

# Ecole Indirecte

**Ecole Indirecte** est une application mobile destinée aux étudiants. Elle permet de moduler l'interface à la convenance de l'utilisateur et de discuter en direct avec d'autres étudiants !

Ce projet est réalisé dans le cadre de notre formation en **BTS SIO option SLAM** (Solutions Logicielles et Applications Métiers), lors de notre seconde année.

---
## Pourquoi ce projet ? 

Ce projet a été pensé pour accompagner au mieux les étudiants dans leur vie au lycée. L'objectif est de leur permettre de s'organiser efficacement entre leurs études et leur vie personnelle, notamment grâce à la modification personnalisée de l'emploi du temps. 

De plus, la possibilité de personnaliser l'interface de l'application permet un accès plus rapide aux informations essentielles. Par exemple, un élève qui consulte systématiquement son emploi du temps en ouvrant l'application pourra choisir de l'afficher directement sur sa page d'accueil.

---

## Par qui ce logiciel sera-t-il utilisé ? 

Dans ce projet, nous distinguons plusieurs types d'utilisateurs : 

* **Étudiant**
* **Administrateur**
* **Professeur**

---
## Contraite et Solution Technique 

### Contrainte 

Ce projet à une contrainte technique, nous voulons récupérez les informations d'École Directe via une API, aujourd'hui cette API n'existe pas.Il existe des API créer par des utilisateur mais qui sont malheureusement pas très fonctionel.

### Solution 

Pour régler ce problème, nous avons choisi de créer nous-mêmes nos jeux de données. Nous avons donc intégré dans notre base de données toutes les informations nécessaires, telles que les emplois du temps, les notes et le cahier de textes.

---

## Fonctionnalités proposées

Voici les fonctionnalités pour chaque type d'utilisateur : 

**L'étudiant aura accès aux fonctionnalités suivantes :**
* Accès simplifié à l'emploi du temps.
* Interface modulable (ex: possibilité de mettre l'emploi du temps en page d'accueil).
* Notifications en cas de changement d'emploi du temps.
* Chat de discussion privé entre classes.
* Système de tickets (Support) en cas de problème avec le logiciel.
* Consultation du menu du jour au self.

**L'administrateur aura accès aux fonctionnalités suivantes :**
* Gestion du Support du logiciel (accès, lecture et réponse aux tickets).
* Accès à certaines données confidentielles (sous réserve d'autorisation/rôles).

**Les professeurs auront accès aux fonctionnalités suivantes :**
* Accès aux discussions de groupe si un groupe incluant des élèves a été créé.

---



## Technologies

### Version Légère (Client Web)



* **MariaDB (Base de données SQL)** : Pour la gestion et le stockage des données de l'application.
* **PHP** : Pour développer le côté serveur (backend) et les fonctionnalités dont nous avons besoin. 
* **JavaScript** : Pour rendre le site dynamique et interactif côté utilisateur.
* **HTML et CSS** : Ces langages constituent tout simplement la base pour structurer et habiller notre site web. 

### Version Lourde (Client Mobile)

* **Flutter** : Ce framework polyvalent permet de développer et de compiler l'application pour plusieurs systèmes d'exploitation, comme iOS et Android, à partir d'une seule et même base de code.





