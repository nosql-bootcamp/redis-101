# Redis 101

**Redis 101** est un workshop permettant de découvrir la base de données NoSQL Redis et son écosystème, étape par étape.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">redis-101</span> par <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/nosql-bootcamp/redis-101" property="cc:attributionName" rel="cc:attributionURL">Chris WOODROW et Sébastien PRUNIER</a> est distribué sous les termes de la licence <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons - Attribution - NonCommercial - ShareAlike</a>.

## Introduction

[Redis](https://redis.io/) (REmote DIctionary Server) est une base de données NoSQL faisant partie de la famille des bases « clé-valeur ». C'est un modèle de stockage de données très simple.

C'est la base clé-valeur la plus populaire selon [db-engines.com](http://db-engines.com/en/ranking).

Redis peut gérer des valeurs autres que des chaînes de caractères dont notamment des listes, des ensembles, des ensembles triés, des hashes. Vous pouvez lire l'introduction aux différents types de données gérés par Redis : https://redis.io/topics/data-types-intro.

Redis conserve l'intégralité de ses données en mémoire (RAM) afin de garantir d'excellentes performances. Un mécanisme de « snapshotting » permet la persistance des données sur disque de manière asynchrone, rendant ainsi possible la restauration des données en cas d'incident. La persistance sur disque a lieu toutes les 2 secondes par défaut, ce qui limite (mais n'exclut pas) la perte de données.

La scalabilté est assurée par un mécanisme de réplication master/slave permettant la répartition de la charge en lecture et offrant une meilleure résistance aux pannes.

## Use Cases

Voici quelques cas d'utilisation des bases de données clé-valeur :

* Cache
* Stockage de données simples (compteurs par exemple)
* Broker simple

## Étapes du workshop

* Étape 0 : [Try Redis !](https://redis.io/)
* Étape 1 : [Installation](https://redis.io/download#installation)

## Liens utiles

* Site officiel : https://redis.io/
* « Try Redis » : https://try.redis.io/
* Interface d'administration (SaaS) : https://www.redsmin.com/
