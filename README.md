# Graphique Conso Electrique Téléinfo EDF avec Highcharts

[![Licence](https://img.shields.io/github/license/BmdOnline/Teleinfo.svg)](LICENSE.md)
[![Release](https://img.shields.io/github/release/BmdOnline/Teleinfo.svg)](https://github.com/BmdOnline/Teleinfo/archive/master.zip)

![Animation](../screenshots/teleinfo/animation_small.gif)

# Présentation
Ceci est une application WEB permettant de visualiser sous forme de graphique les relevés EDF fournis par l'interface téléinfo.

La présentation s'adapte automatiquement aux smartphones & tablettes.

Il faut, au préalable, disposer d'une base de donnée MySQL contenant les relevés Téléinfo.

Vous trouverez toute la documentation nécessaire à la collecte téléinfo à l'aide de votre moteur de recherche favori.
Cet aspect technique ne sera pas évoqué et aucun support ne sera fourni ici.

# Pré-requis
## Matériel
* Un compteur EDF avec l'option téléinfo et les relevés correspondants.

## Logiciel
| | Pré-requis | Versions testées |
| ----------- | ------- | ------- |
| Serveur Web| ![Apache](https://img.shields.io/badge/apache-%3E%3D%202.2-green.svg) | 2.2, 2.4.23 |
| | ![Nginx](https://img.shields.io/badge/nginx-unknown-lightgrey.svg) | serveurs type Nginx… non testés |
| PHP | [![PHP](https://img.shields.io/badge/php-%3E%3D%205.4-green.svg)](https://php.net/) | 5.4, 5.5, 5.6, 7.0.4 |
| Base de donnée | ![MySQL](https://img.shields.io/badge/mysql-%3E%3D%205.0-green.svg) | 5.0, 5.5, 5.7.1 |
| | ![MariaDB](https://img.shields.io/badge/mariadb-%3E%3D%205.5-green.svg) | 5.5, 10.1.16 |

# Sommaire
* [Installation](INSTALL.md) : Installation, configuration et paramétrage du programme.
* [Personnalisation](THEMES.md) : Personnalisation de l'interface via l'utilisation de templates et thèmes.
* [Copies d'écran](../screenshots/README.md) : Quelques copies d'écran illustrant les fonctions et différents thèmes du programme.
* [Ressources](https://github.com/BmdOnline/Teleinfo/tree/ressources) : Ressources diverses (tarifs EDF, collecteur Téléinfo).
* [Changements] (CHANGELOG.md) : Historique des versions.
* [Licence] (LICENSE.md) : Ce programme est placé sous licence GPL v3.
* Librairies PHP
    * [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) : Licence MIT.
    * [RainTPL](https://github.com/feulf/raintpl3) : Licence LGPL v3.
* Librairies JavaScript
    * [JQuery](https://jquery.org/license) : Licence MIT.
    ```
    jQuery Foundation projects are released under the terms of the license specified in the project's repository or if not specified, under the MIT license.
    The MIT License is simple and easy to understand and it places almost no restrictions on what you can do with a jQuery Foundation project.
    You are free to use any jQuery Foundation project in any other project (even commercial projects) as long as the copyright header is left intact.
    ````
    * [Chart.js] (http://www.chartjs.org) : Licence MIT.
    ```
    Chart.js is open source and available under the MIT license.
    ```
    * [Highcharts] (https://shop.highsoft.com/faq#Non-Commercial) : Licence CC by-nc 3.0.
    ```
    You can use our software for free under the non-commercial license if you are:
    - A student;
    - Working on a project for a university or a public school;
    - A non-profit organization, or;
    - for testing and demonstration purposes.
    ```
    * [JQPlot] (http://www.jqplot.com) : Licence MIT & GPL v2.
    ```
    jqPlot is an open source project dual licensed under the MIT and GPL version 2 licenses.
    You are free to choose the license that best suits your project.
    ```
    * [Flot] (http://www.flotcharts.org) : Licence MIT.
    ```
    Copyright (c) 2007-2014 IOLA and Ole Laursen
    It was started by Ole Laursen, sponsored by IOLA, an agile little Danish web-development house with a keen eye for Python/Django and jQuery.
    It is currently being maintained by David Schnur.
    ```