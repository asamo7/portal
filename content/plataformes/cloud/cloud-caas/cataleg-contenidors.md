+++
date        = "2023-07-17"
title       = "Elements del catàleg de contenidors"
description = "Descripció de les imatges docker base proporcionades pel CTTI."
sections    = "Cloud"
weight      = 1
toc = true
categories  = ["cloud","docker","container", "kubernetes","openshift","swarm", "swamme", "ibm", "caas"]
+++

En aquesta secció es descriuen les diferents imatges docker homologades pel CTTI i utilitzables a les diferents plataformes de contenidors.

## **Imatges de contenidors base**

Per facilitar la tasca de desenvolupament i creació d'aplicacions basades en contenidors, CTTI ofereix un conjunt d'imatges certificades i alineades amb les versions del software del [Full de Ruta de Programari](https://qualitat.solucions.gencat.cat/estandards/estandard-full-ruta-programari/).

Podeu trobar aquestes imatges certificades al [registre privat](https://registreimatges.sic.intranet.gencat.cat). Si necessiteu més informació d'aquest registre privat, podeu consultar [Registre d'imatges](http://canigo.ctti.gencat.cat/sic30-serveis/registre-imatges/).

**Element**  | **Versió**   | **Imatge Docker**   | **Codi font**
------------ | ------------ |-------------------- |-----------
Apache 		 | 2.4    | registreimatges.sic.intranet.gencat.cat/gencatcloud/httpd:2.4   | [httpd](https://git.intranet.gencat.cat/3048-intern/imatges-docker/httpd/tree/2.4)
Apache GICAR Shibboleth| 1.0.3    |registreimatges.sic.intranet.gencat.cat/gencatcloud/gicar-shibboleth:1.0.3   | [gicar-shibboleth](https://git.intranet.gencat.cat/3048-intern/imatges-docker/gicar-shibboleth/tree/1.0.3)
Apache GICAR Shibboleth Kubernetes/Openshift| 1.0.3    |registreimatges.sic.intranet.gencat.cat/gencatcloud/gicar-shibboleth-openshift:1.0.3   | [gicar-shibboleth-openshift](https://git.intranet.gencat.cat/3048-intern/imatges-docker/gicar-shibboleth-openshift/tree/1.0.3)
Apache Proxy ElasticSearch  	 | 2.4-1.0   |registreimatges.sic.intranet.gencat.cat/gencatcloud/httpd-proxy-es:2.4-1.0   | [httpd-proxy-es](https://git.intranet.gencat.cat/3048-intern/imatges-docker/httpd-proxy-es/tree/2.4-1.0)
Nginx  	 | 1.20   |registreimatges.sic.intranet.gencat.cat/gencatcloud/nginx:1.20   | [nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/nginx/tree/1.20)
GICAR Nginx 	 | 1.0.0  |registreimatges.sic.intranet.gencat.cat/gencatcloud/gicar-nginx:1.0.0   | [gicar-nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/gicar-nginx/tree/1.0.0)
GICAR Nginx Kubernetes/Openshift	 | 1.0.0  |registreimatges.sic.intranet.gencat.cat/gencatcloud/gicar-nginx-openshift:1.0.0   | [gicar-nginx-openshift](https://git.intranet.gencat.cat/3048-intern/imatges-docker/gicar-nginx-openshift/tree/1.0.0)
Java		 | 8  | registreimatges.sic.intranet.gencat.cat/gencatcloud/java:8   | [java](https://git.intranet.gencat.cat/3048-intern/imatges-docker/java/tree/8)
Java		 | 11-openjdk  | registreimatges.sic.intranet.gencat.cat/gencatcloud/java:11-openjdk   | [java](https://git.intranet.gencat.cat/3048-intern/imatges-docker/java/tree/11)
.Net Core    | 3.1   | registreimatges.sic.intranet.gencat.cat/gencatcloud/dotnet:1.0-3.1   | [dotnet](https://git.intranet.gencat.cat/3048-intern/imatges-docker/dotnet/tree/3.1)
.Net Core    | 6.0.19   | registreimatges.sic.intranet.gencat.cat/gencatcloud/dotnet:1.0-6.0.19   | [dotnet](https://git.intranet.gencat.cat/3048-intern/imatges-docker/dotnet/tree/1.0-6.0.19)
NodeJS 		 | 14   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:14   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/14)
NodeJS 		 | 16   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:16   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/16)
NodeJS 		 | 18   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:18   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/18)
PHP 		 | 8.0   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:8.0   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/8.0)
PHP 		 | 8.1   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:8.1   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/8.1)
Tomcat  	 | 9.0-java8   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:9.0-java8   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/9.0-java8)
Tomcat  	 | 9.0-java11   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:9.0-java11   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/9.0-java11)
Tomcat amb suport de Sessions distribuïdes | 9.0-java8   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:9.0-java8   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/9.0-java8)
Tomcat amb suport de Sessions distribuïdes  | 9.0-java11   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:9.0-java11   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/9.0-java11)

<br>
**IMPORTANT**: De cara a minimitzar les vulnerabilitats de les aplicacions, es recomana que periòdicament els proveïdors d'aplicacions les reconstrueixin utilitzant aquestes imatges Docker certificades més actualitzades. Per realitzar aquestes tasques de construcció i desplegament s'ha de fer ús de les corresponents pipelines al Jenkins del SIC.
<br>

La llista anterior no exclou que no es puguin lliurar contenidors que corrin altres productes i personalitzacions. En qualsevol cas, les imatges construïdes passaran per un servei d'avaluació de vulnerabilitats per a garantir en una primera instància la qualitat d'aquestes.

Per construir contenidors personalitzats, cal tenir present els [Criteris creació contenidors docker](https://canigo.ctti.gencat.cat/cloud-caas/dockerImages/).

Més informació sobre Docker: https://www.docker.com/

### Bases de dades a contenidors

Les bases de dades a contenidors no disposen de cap servei com backups o gestió d'usuaris. El proveïdor d'aplicacions haurà de fer-se càrrec d'aquests serveis.

Tampoc ofereix un entorn en alta disponibilitat. És una modalitat no recomanada per entorns productius.

## **Imatges de contenidors obsoletes**

**Aquestes imatges són obsoletes/no suportades i no tenen manteniment. Poden contenir vulnerabilitats i no està recomanat el seu ús.**

**En cas d'utilitzar aquestes imatges es recomana l'actualització a les imatges suportades.**

**Element**  | **Versió**   | **Imatge Docker**   | **Codi font**
------------ | ------------ |-------------------- |-----------
Apache GICAR Openshift| 1.0   | registreimatges.sic.intranet.gencat.cat/gencatcloud/gicar-openshift:1.0   | No disponible
Nginx  	 | 1.12   |registreimatges.sic.intranet.gencat.cat/gencatcloud/nginx:1.12   | [nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/nginx/tree/1.12)
Nginx  	 | 1.14   |registreimatges.sic.intranet.gencat.cat/gencatcloud/nginx:1.14   | [nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/nginx/tree/1.14)
Nginx  	 | 1.16   |registreimatges.sic.intranet.gencat.cat/gencatcloud/nginx:1.16   | [nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/nginx/tree/1.16)
Nginx  	 | 1.18   |registreimatges.sic.intranet.gencat.cat/gencatcloud/nginx:1.18   | [nginx](https://git.intranet.gencat.cat/3048-intern/imatges-docker/nginx/tree/1.18)
NodeJS 		 | 4  | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:4   | [node ](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/4)
NodeJS 		 | 6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:6   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/6)
NodeJS 		 | 8   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:8   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/8)
NodeJS 		 | 10   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:10   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/10)
NodeJS 		 | 12   | registreimatges.sic.intranet.gencat.cat/gencatcloud/node:12   | [node](https://git.intranet.gencat.cat/3048-intern/imatges-docker/node/tree/12)
PHP 		 | 5.6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:5.6   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/5.6)
PHP 		 | 7.1   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:7.1   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/7.1)
PHP 		 | 7.2   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:7.2   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/7.2)
PHP 		 | 7.3   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:7.3   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/7.3)
PHP 		 | 7.4   | registreimatges.sic.intranet.gencat.cat/gencatcloud/apache-php:7.4   | [apache-php](https://git.intranet.gencat.cat/3048-intern/imatges-docker/apache-php/tree/7.4)
Java		 | 6  | registreimatges.sic.intranet.gencat.cat/gencatcloud/java:6   | [java](https://git.intranet.gencat.cat/3048-intern/imatges-docker/java/tree/6)
Java		 | 7  | registreimatges.sic.intranet.gencat.cat/gencatcloud/java:7   | [java](https://git.intranet.gencat.cat/3048-intern/imatges-docker/java/tree/7)
Tomcat  	 | 6-java6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:6-java6    | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/6-java6 )
Tomcat  	 | 6-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:6-java7    | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/6-java7 )
Tomcat  	 | 7-java6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:7-java6   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/7-java6)
Tomcat  	 | 7-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:7-java7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/7-java7)
Tomcat  	 | 7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/7)
Tomcat  	 | 8.0-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:8.0-java7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/8.0-java7)
Tomcat  	 | 8.0   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:8.0   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/8.0)
Tomcat  	 | 8.5   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat:8.5   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat/tree/8.5)
Tomcat amb suport de Sessions distribuïdes | 6-java6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:6-java6    | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/6-java6 )
Tomcat amb suport de Sessions distribuïdes | 6-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:6-java7    | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/6-java7 )
Tomcat amb suport de Sessions distribuïdes | 7-java6   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:7-java6   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/7-java6)
Tomcat amb suport de Sessions distribuïdes | 7-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:7-java7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/7-java7)
Tomcat amb suport de Sessions distribuïdes | 7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/7)
Tomcat amb suport de Sessions distribuïdes | 8.0-java7   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:8.0-java7   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/8.0-java7)
Tomcat amb suport de Sessions distribuïdes | 8.0   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:8.0   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/8.0)
Tomcat amb suport de Sessions distribuïdes | 8.5   | registreimatges.sic.intranet.gencat.cat/gencatcloud/tomcat-hc:8.5   | [tomcat](https://git.intranet.gencat.cat/3048-intern/imatges-docker/tomcat-hc/tree/8.5)
Postgres	 | 9.3    | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:9.3   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/9.3)
Postgres	 | 9.4    | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:9.4   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/9.4)
Postgres	 | 9.5    | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:9.5   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/9.5)
Postgres	 | 9.6    | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:9.6   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/9.6)
Postgres	 | 10   | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:10   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/10)
Postgres	 | 11   | registreimatges.sic.intranet.gencat.cat/gencatcloud/postgres:11   | [postgres](https://git.intranet.gencat.cat/3048-intern/imatges-docker/postgres/tree/11)
MongoDB 	 | 3.2   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mongodb:3.2   | [mongodb](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mongodb/tree/3.2)
MongoDB 	 | 3.4   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mongodb:3.4   | [mongodb](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mongodb/tree/3.4)
MongoDB 	 | 3.6   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mongodb:3.6   | [mongodb](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mongodb/tree/3.6)
MongoDB 	 | 4.0   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mongodb:4.0   | [mongodb](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mongodb/tree/4.0)
MongoDB 	 | 4.2   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mongodb:4.2   | [mongodb](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mongodb/tree/4.2)
MySql 		 | 5.7   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mysql:5.7   | [mysql](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mysql/tree/5.7)
MySql 		 | 8.0   |registreimatges.sic.intranet.gencat.cat/gencatcloud/mysql:8.0   | [mysql](https://git.intranet.gencat.cat/3048-intern/imatges-docker/mysql/tree/8.0)
