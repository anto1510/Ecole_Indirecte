<p align="center">
  <img src="./Logo_indirecte.png" alt="logo" width="100%">
</p>



<table align="center">
  <tr>
    <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/PHP">
        <img src="https://www.svgrepo.com/show/349474/php.svg" alt="PHP" width="65" height="65" />
      </a>
      <br>PHP
    </td>
        <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/Python_(langage)">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="Python" width="65" height="65" />
      </a>
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/C_Sharp">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="C shrap" width="65" height="65" />
      </a>
      <br>HTML 
    </td>
    <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/C_Sharp">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="C shrap" width="65" height="65" />
      </a>
      <br>CSS
  <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/TypeScript">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mariadb/mariadb-original.svg" alt="TypeScript" width="65" height="65" />
      </a>
      <br>MariaDB 
    </td>
    <td align="center" width="96">
      <a href="https://fr.wikipedia.org/wiki/Structured_Query_Language">
        <img src="https://www.svgrepo.com/show/331760/sql-database-generic.svg" width="65" height="65" alt="Structured Query Language" />
      </a>
      <br>SQL
    </td>
    
  </tr>
</table>

# Ecole Indirecte :

**Ecole Indirecte** est une application mobile destinée aux étudiants. Elle permet de moduler l'interface à la convenance de l'utilisateur et de discuter en direct avec d'autres étudiants !

Ce projet est réalisé dans le cadre de notre formation en **BTS SIO option SLAM** (Solutions Logicielles et Applications Métiers), lors de notre seconde année.

---

## Client Lourd (Application Mobile) :

### Par qui ce logiciel sera-t-il utilisé ?

Dans cette partie du projet, nous avons un type d'utilisateur: 

* **Les Étudiants**

### Pourquoi ce projet ?

Ce projet a été pensé pour accompagner au mieux les étudiants dans leur vie au lycée. L'objectif est de leur permettre de s'organiser efficacement entre leurs études et leur vie personnelle, notamment grâce à la modification personnalisée de l'emploi du temps.

De plus, la possibilité de personnaliser l'interface de l'application permet un accès plus rapide aux informations essentielles. Par exemple, un élève qui consulte systématiquement son emploi du temps en ouvrant l'application pourra choisir de l'afficher directement sur sa page d'accueil.




---

## Client Léger (Application Web) :

### Par qui ce logiciel sera-t-il utilisé ?

* **Les Administrateurs**
* **Étudiant** 

### Pourquoi ce projet ?

Cette interface va être utilisée par les administrateurs.

Dans le cadre de notre projet de BTS SIO, nous devons obligatoirement concevoir deux types d’applications : un client lourd et un client léger. Nous avons fait le choix de développer un client lourd les étudiants, car ces utilisateurs consulteront l'outil principalement sur smartphone. Par conséquent, une application légère, accessible directement depuis un navigateur web, nous a semblé beaucoup plus adaptée aux besoins de gestion des administrateurs. Par contre les Etudiant auront beaucoup plus de fonctionnalité sur l'application web.  





---

## Contraintes et Solutions Techniques :

### Contraintes :

Ce projet a une contrainte technique majeure l'utilisation de l'API : Au début du projet, nous avions pour but de récupérer les informations d'École Directe via une API, malheuresement **l'API d'Ecole Directe n'est pas publique** et il est donc impossible pour nous de l'utiliser. **Il existe bien des API créées par la communautée disponible en Open Source, mais elles ne sont malheureusement pas suffisamment fonctionnelles ou stables** pour notre projet.

### Solution :

Pour pallier à ce problème, nous avons choisi de créer nous-mêmes nos jeux de données. Nous avons donc **intégré dans notre propre base de données** toutes les informations nécessaires à la simulation, telles que les emplois du temps, les notes, le cahier de textes et toutes les autres informations nécéssaires pour la bonne réalisation de notre projet.

---

## Fonctionnalités proposées :

Voici les fonctionnalités prévues pour chaque type d'utilisateur, certaines fonctionnalitées sont marquées en optionnel car elle ne sont pas prioritaires dans notre projet initial :


**L'étudiant aura accès aux fonctionnalités suivantes (Client Lourd) :**
* Accès simplifié à l'emploi du temps.
* Interface modulable (ex: possibilité de mettre l'emploi du temps en page d'accueil).
* Ajout d'heures personnelles dans l'emploi du temps.
* Notifications en cas de changement d'emploi du temps, nouvelle note, information. 
* Chat de discussion privé entre classes.



**L'administrateur aura accès aux fonctionnalités suivantes (Client Léger) :**
* Gestion du support de l'application (accès, lecture et réponse aux tickets étudiants).
* Accès à certaines données confidentielles (sous réserve des droits et rôles accordés).
* Gestion des utilisateur.
* Gestion des rôles et permissions.
* consultations des logs.
* Envoie messages générales.
* Envoyer des messages privés.
* Gestion des emplois du temps.

---

## Technologies utilisées :

### Version Légère (Client Web) :

* **MariaDB (Base de données SQL) :**  Pour la gestion et le stockage des données de l'application nous décidons de tout héberger sur les serveurs PhpMyAdmin qui sont installés sur nos VM distantes au lycée.
* **PHP :**  Pour développer le côté serveur (backend) et la logique métier, nous allons utiliser le language Php grâce aux cours que nous avons eux l'année dernière.
* **JavaScript :**  Pour rendre l'interface web dynamique et interactive côté utilisateur, c'est le language JavaScript qui sera utilisé dans notre projet.
* **HTML et CSS :**  Pour la structure et l'habillage graphique de notre site web.

### Version Lourde (Client Mobile) :

* **Flutter :**  Ce framework polyvalent permet de développer et de compiler l'application pour plusieurs systèmes d'exploitation (comme iOS et Android) à partir d'une seule et même base de code.
* **Dart :** En nous basant sur le framework Flutter, pour programmer une grande partie de notre application.
* **PHP :**  Pour développer le côté serveur (backend) et la logique métier, nous allons utiliser le language Php grâce aux cours que nous avons eux l'année dernière.



## Base de données

**Utilisateur**: il seras définit par son **Id**, **son rôle (administrateur, Étudiant)**, **nom**, **prénom**, **nom d'utilisateur**, **mot de passe**, **ID Formation**, **Id emplois du temps**,**id classe** 

**Formation**: Une formation seras définit par un **id de formation**, un **id de classe**, et **l'année Scolaire**. 

**Classe**: La classe seras définit par un **id classe** (qui permet de définir une classe comme il existe plusieur classe différente), et le **nom de la classe** avec l'option.


**Emplois du temps**: **id Emploi du temps**,**Matière**, **Durée (heure)**, **Le jour**,**ID Classe (clé étrangère)**









---

## Comment faire évoluer le projet ? 

### Rajout acteur

* Professeur 
* BDE (envoyer d'information consernée le BDE)
* Support technique

### Ajout de fonctionnalité

* Accès au planing cantine 
* Mot de passe oublié 
* Possibilité d'envoyer des tickets pour les étudiants: 
  * Un ticket est créer avec les informations d'un **titre** de l'incident, **la date** de l'incident, la **description** de l'incident, **Thème** de l'incident (le thème vaut l'importance de l'incident)



