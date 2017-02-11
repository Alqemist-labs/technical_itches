# technical_itches

Préparation et suivi des workshops weekly d'Alqemist.

## TLDR;
Alqemist organise **chaque Vendredi à 10h** des workshops internes, dans le but de :
- Se former à de nouvelles technos, de nouveaux concepts
- D'essayer de résoudre ensemble des problématiques récurrentes
- De se montrer des projets et des recherches perso

Ce Repo (et sa [board](#boards)) a pour objectif d'organiser ces sessions workshop.
La sélection des workshop à venir se fait par vote.
Les workshops sont enregistrés, pour que les absents puissent les revoir :)

## Ca se passe où ?
Sur appear.in: [https://appear.in/u/workshop-alqemist](https://appear.in/u/workshop-alqemist)

## Prérequis
Installer l'extension nav [ZenHub](https://www.zenhub.com/) pour avoir accès à la [board](#boards)

## Fonctionnement de la board

#### Colonne "Proposals":
Liste les propositions de workshop.
Ces propositions ne sont pas encore prêtes, c'est à dire qu'elles ne peuvent pas être programmées pour l'instant.

#### Colonne "Ready": 
Les Workshop prêts, qui potentiellement peuvent être programmés dans les semaines à venir.

#### Colonne "Week + 2":
Le Workshop programmé pour la session N+2

#### Colonne "Week + 1":
Le Workshop programmé pour la session N+1

## Le système de vote
Le choix des prochains workshop se fait via un système de vote, par les reactions Github sur les issues :
![Vote](/images/voting.png)

Vote = :+1:

## Je veux proposer un Workshop !
Il est possible de proposer un Workshop dont on veut être le presenter, où que l'on aimerait voir être présenté par quelqu'un d'autre.
Il suffit de créer une issue, avec quelques lignes de description, et de le mettre dans la colonne Proposals ou Ready.

**L'issue devra porter les labels :**
- BackOffice ou FrontOffice
- Un label de duration
- Un label de Type

## Enregistrer une session
C'est le presenter du workshop qui doit être en charge de l'enregistrement.

#### MacOSX
Sous MacOS, le plus simple est de passer par Quicktime.
Via `Fichier -> Nouvel enregistrement de l'écran` il est possible d'enregistrer l'écran du presenter et son microphone.
![Recording via Quicktime](/images/recording-osx-01.png)

**Il est également possible d'enregistrer les voix des autres participants en enregistrant le son du système:**
- [Télécharger le .dmg de Soundflower](https://github.com/mattingalls/Soundflower/releases) (version modifiée pour Yosemite/Mavericks/El Capitan/Sierra)
- Redémarrer
- Ouvrir la configuration audio et MIDI du système (`/Applications/Utilities/Audio MIDI Setup.app`)
- Créer un "Périphérique agrégé", et cocher votre input audio et Soundflower (2ch)
![Aggregate Device](/images/recording-osx-02.png)
- Créer un "Périphérique à sortie multiple", et cocher votre output audio et Soundflower (2ch)
![Multi-Output Device](/images/recording-osx-03.png)
- Dans les préférences de son du système, régler la Sortie à "Périphérique à sortie multiple"
- Enregistrer avec Quicktime comme d'habitude, en choisissant "Périphérique aggrégé" comme microphone

**NOTE:** cette manip n'impacte pas l'utilisation normale de votre input / output audio 

## Outils
vidéo + partage d'écran : https://appear.in/ à tester

capture vidéo : https://obsproject.com/ à tester
