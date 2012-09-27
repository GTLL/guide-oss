Big Data et NoSQL
=================

Depuis 2009, une nouvelle mouvance – le NoSQL – est apparue. Elle propose une alternative au SQL et au modèle relationnel afin de permettre un haut niveau de scalabilité (extensibilité).


MongoDB
-------

:Version: 2.2.0
:Site: http://www.mongodb.org
:Porteur: 10gen Inc
:Licence: Affero GPL

MongoDB est une base de données "orientée documents" de la mouvance NoSQL permettant le stockage de documents au format BSON (une forme binaire de JSON).

Elle dispose de capacité à évoluer en environnement distribué via des mécanismes de réplication et de sharding. Son intégration particulièrement réussie avec la plupart des langages de programmation ainsi que sa documentation de qualité lui confèrent une popularité importante. MongoDB profite du fort regain d'intérêts pour les bases documentaires qui permettent de mieux coller aux environnements modernes qui se doivent de manipuler des données fortement hétérogènes et pour lesquels les SGBD relationnels ne sont pas nécessairement les plus adaptés.

La base de données est par ailleurs supportée par une entité commerciale, la société 10gen Inc.

MongoDB est écrit en C++.

NEO
---

:Version: 1.0
:Site: http://www.neoppod.org/
:Porteur: un éditeur (Nexedi)
:Licence: GPL-2.0

NEO est une base de données NoSQL de type objet qui est la fois transactionnelle, répartie et redondante. NEO a fait l'objet dans le cadre de Systematic  d'un projet de recherche conjoint de Nexedi, Pilot Systems, l'Université de Paris 13 et l'Université de Paris 6. La cohérence transactionnelle de NEO sur un cluster de stockage réparti a ainsi pu être démontrée ce qui ouvre la voie à une application des technologes NoSQL aux systèmes de paiements et aux systèmes bancaires.

NEO est écrit en python et en C.


Redis
-----

:Version: 2.2.13
:Site: http://redis.io
:Porteur: un éditeur (VMware)
:Licence: BSD

Redis est un dépot de données clé/valeur issue de la mouvance NoSQL. Le projet est sponsorisé par VMware. La première version a été publiée en 2009 par Salvatore Sanfilippo et Pieter Noordhuis.

Comme la plupart des datastore key / value, Redis propose une interface HTTP REST. Son originalité par rapport aux autres solutions disponibles réside dans le fait que Redis dispose d'un ensemble de fonctions de manipulation de données principalement axées sur la manipulation des chaines de caractères qui sont stockées, conférant à Redis la capacité de construire des requêtes légèrement plus complexes que ses concurrents traditionnellement limités aux opérations CRUD (Create Reade Update Delete). Les bonnes performances de Redis, que ce soit en lecture ou en écriture, le positionnent comme un excellent choix pour l'implémentation de backend de cache ou de gestionnaire de session.

Redis est écrit en C.


Apache Cassandra
----------------

:Version: 1.1.5
:Site: http://cassandra.apache.org
:Porteur: une fondation (Apache)
:Licence: Apache

Cassandra est une autre base de données de la mouvance NoSQL. Initialement développée par Facebook en 2008, elle a été par la suite libérée et son développement est aujourd'hui assuré par la fondation Apache.

Cassandra est une base de données orientée colonne. Etudiée pour des déploiements massivement distribués (éventuellement sur plusieurs datacenters), Cassandra est l'une des bases les plus performantes dès lors qu'il s'agit de répondre à des problématiques de traitement de données massif. Son architecture complètement décentralisée lui confère par ailleurs une résistance à la panne très importante. Comme la plupart des bases orientées colonnes, elle est par ailleurs particulièrement adaptée aux problématiques décisionnelles.

Cassandra est écrit en Java.


Autres
------

L'univers Big Data / NoSQL est particulièrement dynamique, on peut compléter la liste avec les outils ci-dessous :

- db4o  http://www.db4o.com

- CouchDB http://couchdb.apache.org

- Neo4j http://neo4j.org

- Voldemort http://www.project-voldemort.com