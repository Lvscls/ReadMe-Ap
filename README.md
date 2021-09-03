# PhpMyAdmin

**Introduction**

PhpmyAdmin est un logiciel gratuit en PHP pour administrer un serveur MySQL ou MariaDB.

**Pré-requis**

Pour utiliser PhpmyAdmin il faut un serveur web comme Apach ou IIS

Il faut également :
- Php 7.1.3
- Mbstring extension
- l'extension zip php
- Une base de donnée MySQL 5.5 ou une version plus récente , MariaDB 5.5 ou une version plus récente.
- Un navigateur web avec cookie et Javascript

**Installation**

Le moyen le plus simple d'obtenir phpMyAdmin sur Windows consiste à utiliser des produits tiers qui incluent phpMyAdmin avec une base de données et un serveur Web tels que [WAMPSERVER](https://www.wampserver.com/)

**Paramètres de connexion au serveur**

Depuis la version 1.4.2, phpMyAdmin prend en charge l'administration de plusieurs serveurs MySQL. Par conséquent, un`$cfg['Servers']-array` a été ajouté qui contient les informations de connexion pour les différents serveurs. La première`$cfg['Servers'][$i]['host']` contient le nom d'hôte du premier serveur, le second `$cfg['Servers'][$i]['host']` le nom d'hôte du deuxième serveur, etc. Dans libraries/config.default.php, il n'y a qu'une seule section pour la définition du serveur, mais vous pouvez en mettre autant que vous le souhaitez dans config.inc.php, copier ce bloc ou les parties nécessaires (vous n'avez pas à définir tous les paramètres, juste ceux il faut changer).


**Auteur**

phpMyAdmin est Open Source, vous êtes donc invité à y contribuer. De nombreuses fonctionnalités intéressantes ont été écrites par d'autres personnes et vous pouvez également contribuer à faire de phpMyAdmin un outil utile.

**Crédit**

- [Tobias Ratschiller](tobias_at_ratschiller.com)
creator of the phpMyAdmin project
maintainer from 1998 to summer 2000
- [Marc Delisle](marc_at_infomarc.info)
multi-language version in December 1998
various fixes and improvements
first version of the SQL analyser (most of it)
maintainer from 2001 to 2015
- [Olivier Müller](om_at_omnis.ch)
started SourceForge phpMyAdmin project in March 2001
sync’ed different existing CVS trees with new features and bugfixes
multi-language improvements, dynamic language selection
many bugfixes and improvements
- [Loïc Chapeaux](lolo_at_phpheaven.net)
rewrote and optimized JavaScript, DHTML and DOM stuff
rewrote the scripts so they fit the PEAR coding standards and generate XHTML1.0 and CSS2 compliant codes
improved the language detection system
many bugfixes and improvements
- [Robin Johnson](robbat2_at_users.sourceforge.net)
database maintenance controls
table type code
Host authentication IP Allow/Deny
DB-based configuration (Not completed)
SQL parser and pretty-printer
SQL validator
many bugfixes and improvements
- [Armel Fauveau](armel.fauveau_at_globalis-ms.com)
bookmarks feature
multiple dump feature
gzip dump feature
zip dump feature
- [Geert Lund](glund_at_silversoft.dk)
various fixes
moderator of the phpMyAdmin former users forum at phpwizard.net

