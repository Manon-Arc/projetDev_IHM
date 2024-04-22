# Projet de Contrôle d'Objet 3D avec Interface Qt C++ et Unity

### Repository

- repo server / gestion Unity : https://github.com/Manon-Arc/IHM_Unity.git <br>
- repo client IHM : https://github.com/Manon-Arc/IHM_Unity-Qt.git

## Présentation
Ce projet démontre l'intégration d'une interface utilisateur développée en Qt C++ pour contrôler un objet 3D visualisé dans Unity. L'interface utilisateur Qt permet à l'utilisateur de manipuler les propriétés de l'objet 3D, telles que sa position, sa rotation, et instantier des GameObject, tandis que Unity est utilisé pour visualiser l'objet 3D et appliquer les modifications en temps réel.

## Fonctionnalités

- Interface utilisateur Qt C++ pour contrôler un objet 3D dans Unity.
- Système de connexion (base de donnée)
- Contrôle de la position, de la rotation et de l'échelle de l'objet 3D.
- Visualisation en temps réel des modifications apportées à l'objet 3D dans Unity.

## Configuration Requise

- [Qt](https://www.qt.io/download) : Qt Creator est utilisé pour développer l'interface utilisateur en C++.
- [Unity](https://unity.com/) : Unity est utilisé pour visualiser l'objet 3D et recevoir les commandes de contrôle.

## Installation


**Note pour les utilisateurs :**

Ce projet présente une configuration spécifique en termes de compatibilité entre le serveur et le client.

- Le **serveur Unity** inclus dans ce projet est spécifiquement conçu pour fonctionner sur **Windows** en raison de la compatibilité de Unity avec cette plateforme.

- Le **client Qt C++**, quant à lui, a été développé et testé sur **Linux**. Cependant, il peut être possible de le faire fonctionner sur d'autres plateformes, mais cela n'a pas été testé.

**Instructions pour les utilisateurs Windows :**

- Pour exécuter le serveur Unity sur Windows, aucune étape supplémentaire n'est nécessaire, car Unity est nativement compatible avec cette plateforme.

**Instructions pour les utilisateurs Linux :**

- Pour utiliser le client Qt C++ sur Linux, veuillez suivre ces étapes :
  1. Assurez-vous d'avoir les dépendances nécessaires installées sur votre système (Qt, CMake, etc.).
  2. Clonez ce dépôt sur votre machine locale.
  3. Compilez et exécutez le client Qt C++ en suivant les instructions fournies dans la documentation du projet.

**Instructions pour les utilisateurs Windows souhaitant utiliser le client :**

- Comme le client Qt C++ a été testé sur Linux et peut ne pas être entièrement compatible avec Windows, vous devrez installer gRPC manuellement sur votre système. Voici le lien vers la documentation pour vous guider dans le processus d'installation : [Installation de gRPC sur Windows](https://github.com/grpc/grpc/blob/master/BUILDING.md).

Veuillez noter que la compatibilité du client avec Windows dépendra également des dépendances et des configurations spécifiques de votre système.
