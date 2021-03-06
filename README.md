
# <img src="assets/logo.png" alt="class logo" class="logo"/> Introduction aux IHM en Java

* **Cours:** [M2105](http://cache.media.enseignementsup-recherche.gouv.fr/file/25/09/7/PPN_INFORMATIQUE_256097.pdf)
* **Responsable intérimaire:** [Cyril Pain-Barre](mailto:cyril.pain-barre@univ-amu.fr)
* **Responsable habituel:** [Sébastien NEDJAR](mailto:sebastien.nedjar@univ-amu.fr)
* **Enseignants actuels:** [Sophie Nabitz](mailto:sophie.nabitz@univ-avignon.fr), [Cyril Pain-Barre](mailto:cyril.pain-barre@univ-amu.fr)
* **Besoin d'aide ?**
    * La page [Piazza de ce cours](https://piazza.com/univ-amu.fr/spring2018/m2105/home).
    * Consulter et/ou créér des [issues](https://github.com/IUTInfoAix-M2105/Syllabus/issues).
    * [Email](mailto:sebastien.nedjar@univ-amu.fr) pour une question d'ordre privée, ou pour convenir d'un rendez-vous physique.

## Intentions pédagogiques
- Apporter les notions de base de la conception d'IHM pour sensibiliser les étudiants à l'ergonomie et aux principes sous-jacents.
- Spécifier, concevoir et développer les interfaces/interactions avec l’utilisateur 
- Faire découvrir aux étudiants un nouveau langage de programmation orienté objet pour consolider leurs connaissances acquises en C++.
- Permettre aux étudiants de s'autoévaluer à travers la mise en place d'un suivi automatisé s'appuyant sur une suite de test et de l'intégration continue.

## Pré-requis
 - M1103 - Structure de données et algorithmes fondamentaux 
 - M2103 - Bases de la programmation orientée objet
 - M2104 - Bases de la conception orientée objet 
 
## Objectifs du parcours
Ce cours vise à apprendre à développer un logiciel doté d'une interface graphique avec le langage Java. Après une rapide introduction à ce langage, les étudiants découvrirons entre autre:  la programmation evénementielle; la spécifications d’interfaces utilisateur, le maquettage; l'ergonomie des interfaces utilisateur; la programmation d’interfaces à travers l'utilisation de composants graphiques.

Les réalisations de ce cours utiliseront la bibliothèque [Java FX](http://docs.oracle.com/javase/8/javase-clienttechnologies.htm). Nous ne couvrirons pas l'intégralité des possibilités offertent par l'API de Java FX mais uniquement les parties liées directement à la réalisation d'une IHM classiques.

En plus de ces objectifs principaux, cet enseignement sera l'occasion de découvrir plusieurs outils et méthodes venant en support au développement logiciel. Sans entrer dans le détail de la configuration et de la mise en place, les étudiants découvriront Git, les tests unitaires et l'intégration continu.

## Contenu et structuration du parcours
- Programmation événementielle
- Spécifications d’interfaces utilisateur, maquettage
- Notions d’ergonomie des interfaces utilisateur
- Programmation d’interfaces, utilisation de composants graphiques 

### CM (10h)
- Java et les objets
- JavaFx
- JavaFx
- Java et l'héritage

### TD/TP (28h)
#### TP 1 : Pour débuter (8h)
- Mise en place de l'environnement:
  * Découverte du workflow
  * Import du projet dans l'IDE
- Découverte Java :
  * Helloword
  * Tableau
  * Ligne de commande
  * Tests avec JUnit 5

#### TP 2 Premier contact avec JavaFx (Stage, scène, événements... )(6h):
- Première application : les classes Application et Stage
- Cycle de vie d'une application
- Premières applications graphiques : composants et événements
  * Hello word graphique
  * Personnalisation de la scène
  * Composants graphiques simples et placement
  * Personnalisation du style d'un composant
  * Événements
- Sujets complémentaires : Animations, gestionnaires de positionnement et dessin
  * Interaction entre composants
  * Composition de composant et panneau de base
  * Animation
  
#### TP 3 Propriétés et Bindings (6h)
#### TP 4 FXML (8h)


## Méthodologie
Formation-action participative et interactive : ces formations s'appuient sur les connaissances, les expériences des participants, leur implication les rendant acteurs de leur formation.
Alternance d'apports théoriques, réflexions collectives et individuelles, mises en situation par des exercices et des réalisations pratiques.

## Supports pédagogiques
Les supports pédagogiques seront mis à disposition des étudiants directement sur [l'organisation Github de cet enseignement](https://github.com/IUTInfoAix-M2105). 

## Ressources humaines et techniques
Les membres de l’équipe conçoivent et animent les formations. Les équipements et matériels disponibles au département informatique de l'IUT d'Aix-Marseille seront utilisés pour illustrer les apports et pour concrétiser certaines réalisations.

Pour travailler sur d'autres machines que celle du département, il faudra installer les outils suivants : 
- [Java SE Development Kit 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven](https://maven.apache.org/)
- [Git](https://git-scm.com/)
- [Bash](https://www.gnu.org/software/bash/) et/ou [Zsh](http://ohmyz.sh/)
- Un IDE Java ([Eclipse](http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/keplersr1), [Netbeans](https://netbeans.org/downloads/) ou [IntelliJ](https://www.jetbrains.com/idea/))

L'installation de ces outils peut se faire manuellement sous windows, avec [homebrew](https://brew.sh/index_fr.html) sous MacOS ou avec le gestionnaire de paquet de votre distribution Linux.

## Modalités d'évaluation
 - Examen final de 2h. Voir examens des années précédentes: [2019](https://github.com/IUTInfoAix-M2105/TestIHM2019/), [2018](https://github.com/IUTInfoAix-M2105/TestIHM2018/), [2017](https://github.com/IUTInfoAix-M2105/TestIHM2017/), [2016](https://github.com/IUTInfoAix-M2105/TestIHM2016/blob/master/Sujet.md), [2015](https://github.com/IUTInfoAix-M2105/TestIHM2015/blob/master/sujet.md), [2014](https://github.com/IUTInfoAix-M2105/TestIHM2014/blob/master/Sujet.md) **(min 90% de la note du module M2105)**
 - Controle continu du travail fait en tp et mis en ligne sur Github **(max 10% de la note du module M2105)**.
 - Réalisation des maquettes fonctionnelles pour les projets tutorés **(approximativement 17% de la note du module M2107)**.
