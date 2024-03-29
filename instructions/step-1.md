# Installation

### Utilisation d'une version cloud
Plutôt que d'installer Redis localement, vous pouvez profiter de l'essai gratuit (15 jours) de la version cloud qui est accessible sur [https://redis.com/redis-enterprise-cloud/overview/](https://redis.com/redis-enterprise-cloud/overview/) (bouton bleu `Try for free` en bas à gauche).

Vous pouvez trouver les instructions complètes à suivre ici pour vous connecter à votre instance [ici](https://docs.redis.com/latest/rc/rc-quickstart/).


### Installation en local

## Linux et Mac OS

La procédure à suivre est la suivante : https://redis.io/download#installation

## Windows

**Redis n'est pas supporté officiellement sous windows.**

A une époque, Microsoft Open Tech maintenait un portage de Redis sous Windows : https://github.com/MSOpenTech/redis

Cela ne semble plus être le cas malheureusement :-(

Il y a plusieurs alternatives possibles si vous travaillez sous windows : 
* [Image Docker pour Redis](https://hub.docker.com/_/redis/)
* [Redis Cloud](https://redislabs.com/redis-cloud) en tant que serveur Redis et [Redsmin](https://www.redsmin.com/) en tant que client et outil d'administration
* [Memurai](https://www.memurai.com/), "Redis-compatible cache and datastore for Windows"
