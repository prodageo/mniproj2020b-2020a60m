---
consigne: http://prodageo.insa-rouen.fr/casimono/sujetprojmd/consignes.html 
---
# Monographie - Authentification avec les réseaux sociaux

## Cartouche

 - Code du sujet : 60M
 - Code de l'alliance : 2020A60M
 - Liste des équipes
   - E05
     - Abbassi, Imane (iabbassi)
     - Billoré, Jessica (jbillore)
     - Bouvet, Marie (mbouvet1)

## Suivi des modifications

| Version  | Date     |  Modification(s) apportée(s) |
| -------- | -------- | ------------|
| 1.0     | 05/11/2020 | Monographie partie A (version déposée sur Moodle) |
| 1.1 | 21/11/2020 | Correction partie A (parties A0, A1, A2, A3, A6) selon retour de M.Baucher   |
| 2.0 | 01/12/2020 | Monographie partie B (version déposée sur Moodle)|


## Partie A

### A0. Introduction.

L’authentification avec les réseaux sociaux est une forme d’authentification où les processus d’authentification sont délégués à des services dits de réseaux sociaux tels que Facebook, Google+ ou Twitter. Les informations de connexion existantes d’un utilisateur à un réseau social sont utilisées pour connecter l’utilisateur à un site web tiers. Cette technique permet de simplifier le processus de connexion pour l’utilisateur et de lui éviter d’ouvrir un compte par site. 

Ce type d’authentification est qualifié d’authentification unique ou Single Sign-On (SSO) en anglais. L’authentification unique regroupe toutes les méthodes d’authentification permettant à un utilisateur d’accéder à plusieurs applications informatiques ou sites sécurisés en ne procédant qu’à une seule authentification. Des protocoles de délégation d’authentification et/ou d’autorisation tel que OAuth et SAML sont utilisés. OAuth est un protocole libre qui permet d’autoriser un site web, un logiciel ou une application (dite “consommateur”), d’utiliser l’API sécurisée d’un autre site web (dit “fournisseur”) pour le compte d’un utilisateur. De son côté, le protocole SAML (Security Assertion Markup Language) est un standard ouvert permettant aux fournisseurs d’identité (IdP) de transmettre des données d’identification aux fournisseurs de services. 

Tout comme l’identification, l’autorisation et la gestion des utilisateurs, l’authentification est une des composantes de la Gestion des Identités et des Accès (GIA) ou Identity Access Management (IAM). La GIA est un ensemble de processus qui permet de gérer qui a accès à quelle information à travers le temps. Les contrôles d'accès sont établis à partir de modèle d'habilitation. 

Les modèles RBAC (Role Based Access Control) et IBAC (Identity Based Access Control) sont deux exemples de modèles d'habilitations. Le modèle IBAC permet de donner à l'utilisateur, représenté par son compte applicatif, des droits d'accès au SI en lecture ou écriture. Le modèle RBAC tire son origine du modèle IBAC et permet d'établir, au sein du système d'information d'une entreprise, un contrôle d'accès efficace sur les applications et les services de ce SI. Chaque décision d'accès est basée sur le rôle auquel l'utilisateur est associé. Ce rôle représente le lien entre les utilisateurs et les ressources. Ainsi, le modèle RBAC associe, dans un premier temps, à chaque rôle un ensemble de droits d'accès aux ressources de l'organisation, puis dans un second temps un rôle à chaque utilisateur. 

L'objectif du sujet est de mettre en place l'authentification avec Linkedin afin de permettre à des personnes d'accéder à des ressources gérées par le département ASI. Le but est d'améliorer et de simplifier le processus d'authentification.  


### A1. Glossaire et Mots-clés.

* Réseaux sociaux
* IAM
* Autorisation
* Utilisateur
* Sécurité
* Contrôle d’accès
* Confidentialité
* Déléguer l'authentification
* Compte
* Authentification unique (SSO)


### A2. Webographie

Nous allons maintenant présenter trois sites qualifiés que nous avons utilisé pour réaliser cette monographie.



#### 1. [SSO (Single Sign-On) définition de l’authentification unique.](https://www.lebigdata.fr/single-sign-on-sso-definition) Le Big Data, le magazine I.A., Cloud et Big Data [en ligne]. Bastien L. 11 juillet 2019. Dernière consultation le 01 novembre 2020.

Ce site définit ce qu'est l'authentification unique (SSO) et permet de comprendre son fonctionnement, ses avantages et inconvénients. Ainsi, il nous a permis de mieux comprendre le processus d'authentification que nous étudions dans le cadre de cette monographie.

#### 2. [What is IAM? Identity and access management explained.](https://www.csoonline.com/article/2120384/what-is-iam-identity-and-access-management-explained.html) CSO Magazine [en ligne]. James A. Martin et John K. Waters. 9 octobre 2018. Dernière consultation le 01 novembre 2020.

Ce site définit ce qu'est un IAM, introduit et définit un grand nombre d'outils et de termes relatifs au sujet. Il nous a donc permis de bien comprendre les termes liés à notre sujet. De plus, il présente notamment plusieurs acteurs dans le domaine ce qui nous a été utile pour la partie A4.

#### 3. [Social Login : faire d’un rêve une réalité (1/2)](https://www.riskinsight-wavestone.com/2018/03/social-login-reve-realite-12/) Wavestone [en ligne]. Pascal Vidal et Jérémy Pageaux. 28/03/2018. Dernière consultation le 05 novembre 2020. 

Ce site explique l'origine, les cas d'usage, les étapes ainsi que les avantages de l'authentification avec les réseaux sociaux. Cela met en lumière l'utilité et l'importance de notre sujet.


### A3. Bibliographie

Dans cette partie, nous réaliserons la bibliographie de trois livres avec la mise en exergue des sections qui nous semblent pertinentes dans la table des matières.

#### 1. Ric Shreves. Social Media Optimization for Dummies. John Wiley & Sons, Inc. 2015. 329p.

Ce livre comporte une partie qui explique comment implémenter l'authentification avec les réseaux, notamment avec Facebook, Twitter et Google+.

**Section pertinente :** Partie III : Leveraging Social Media with Your Website, Implementing Social Login (Facebook Login, Twitter Login, Google+ Login, Other Login alternatives) p.103-107.

#### 2. Maryline Laurent, Samia Bouzefrane, La gestion des identités numériques. Collection Systèmes d’information, web et informatique ubiquitaire. ISTE Group. 2015. 284p. 

Cet ouvrage propose un état des lieux des réflexions et des travaux sur la gestion des identités numériques dans divers contextes, comme les réseaux sociaux. Il définit les protocoles de délégation d’authentification et/ou d’autorisation SAML 2.0 et OAuth 2.0 ainsi que les différents systèmes d'authentification. Ce livre couvre ainsi plusieurs aspects de notre sujet.

**Sections pertinentes :**
* Chapitre 2 : La gestion d’identités par la fédération. 2.4. SAML 2.0 et OAuth 2.0  standards de fait de la fédération d’identités, p. 125-138
* Chapitre 3 : Système d’authentification. p.139

#### 3. Omondi Orondo, Identity & Access Management: A Systems Engineering Approach, 2016. 337p. 

Ce livre présente l'IAM en utilisant des concepts établis de l'ingénierie des systèmes et des représentations de systèmes pour ses principaux processus comme l'authentification et l'autorisation. L'ouvrage évoque également les problèmes de l'IAM, tels que la propagation des risques et les processus d'authentification. Il résume donc dans les grandes lignes plusieurs aspects de notre projet. 


**Sections pertinentes :**
* Chapter 3 : IAM Authorization Modeling
* Chapter 5 : Trust Models in Identity and Access Management
* Chapter 8 : Functional IAM : Principles, Requirements, Processes, Policies and Standards 

### A4. Acteurs

Nous allons maintenant présenter trois grandes organisations et grand acteurs dans le secteur de cette technique.

Premièrement, **OneLogin** est un des fournisseurs de SSO cloud les plus réputés. Il a été nommé leader dans le rapport G2 Summer 2020 Grid sur la base d’avis clients. Leur portail d’identification unique permet aux utilisateurs d’accéder à un ensemble d’applications Web en saisissant un unique jeu d’identifiants. Leur catalogue propose plus de 5000 applications pré-intégrées pour faciliter l’authentification unique. On peut citer Office 365, Slack ou encore Github en exemple. OneLogin a plus de 2500 clients dans le monde qui lui font confiance. L’authentification sur la plateforme OneLogin peut se faire grâce aux identifiants de réseaux sociaux tels que Facebook, Google+, LinkedIn et Twitter. 

Ensuite, **Evidian** appartient au groupe Atos et propose une suite logicielle de gestion des identités et des accès. Il est l’un des leader européen des logiciels de gestion des identités et des accès grâce notamment aux produits d’IAM et de SSO qu’il commerciale. Evidian propose une offre complète de gestion des identités numériques et des accès et s’adapte aux besoins des organisations de tous les secteurs en facilitant le processus d’authentification. Leurs solutions de gestion des identités et des accès sont utilisées par plus de 5 000 000 d’utilisateurs dans plus de 900 organisations dans le monde entier. Le groupe propose également un grand nombre de livret blanc en particulier sur l’authentification unique (SSO) et les solutions d’IAM. 

Enfin, **IBM** (International Business Machine Corporation) est une société multinationale américaine présente dans les domaines du matériel informatique, du logiciel et des services informatiques. Elle était autrefois très centrée sur la conception et la commercialisation de matériels informatiques et en particulier d'ordinateurs centraux. Or, désormais les services représentent un peu plus de la moitié du chiffre d’affaires. Ceci témoigne de la profonde transformation opérée par IBM. De plus, IBM a défini EIM (Entreprise Identity Mapping), une architecture qui permet la mise en correspondance de différentes identités sur diverses plateformes et applications en une seule identité. Elle permet ainsi l’authentification unique et elle peut être utilisée avec d’autres mécanismes d’authentification afin de sécuriser la transmission des informations d’utilisateur à une autre plateforme ou application.

### A5. Facteurs qualité

Cette techniques répond à différents facteurs qualité. Parmi la liste des 21 sous-caractéristiques de ISO9126 (McCall) on peut retenir les trois suivants :

* **Sécurité :** l’accès aux données doit être surveillé, recensé, protégé et contrôlé. 
* **Interopérabilité :** avoir le même système d’identification pour différentes application permet de faciliter l'interconnexion entre ces dernières.
* **Efficacité en temps :** le même compte est utilisé pour différentes applications, cela représente un gain de temps en création de compte et authentification.

### A6. Indicateurs qualité

Deux indicateurs de base :
* Indicateur d'efficacité : Nombre d’authentification qu’on peut traiter dans un délai défini.
* Indicateur de fiabilité : Nombre d'authentifications ayant réussi / Nombre d'authentification ayant échoué (alors que les informations étaient correctes)

Indicateur dérivé pour chaque facteur :
* Sécurité ⇒ Indicateur dérivé : Nombre authentifications ayant fait fuité des informations personnelles / Nombre  authentifications totales. 
* Interopérabilité ⇒ Indicateur dérivé : Mesurer le temps et les ressources pour faire interagir l’application et le réseau social.
* Efficacité en temps ⇒ Indicateur dérivé : Comparer le temps de création d’un compte au temps d’authentification unique.

### A7. Références théoriques

Microsoft patterns & practices propose un ensemble de patterns en adéquation avec notre sujet : **[Authentication Patterns](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff647374(v=pandp.10))**.

L’authentification est le processus d’identification d’un individu en utilisant des facteurs d’authentification (en général un identifiant et un mot de passe). Elle permet d’assurer la sécurité des services web. Les Authentication Patterns se décompose en deux architectural pattern : **[Direct Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff647715(v=pandp.10)?redirectedfrom=MSDN)** et **[Brokered Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff650014(v=pandp.10)?redirectedfrom=MSDN)**. Ces deux patterns se concentrent sur la relation qui existe entre un client et un service  web.  

Le **Direct Authentication Pattern** est utilisé lorsque le client et le service partage une relation de confiance leur permettant d’échanger des facteurs d’authentification comme des mots de passes par exemple. 

Dans le cas contraire, le **Brokered Authentication Pattern** est utilisé. Ce pattern introduit une troisième entité, l’Authentication Broker, qui va réaliser l’authentification du client et émettre un token qui va être envoyé au service. Brokered Authentication Pattern se divise en trois design patterns qui sont Security Token Service, X.509 PKI et Kerberos. Ces trois design patterns  correspondent au trois security tokens fourni par le WSE (Web Service Enhancements).

![Schéma Authentication Patterns](https://i.imgur.com/DF4SMvb.gif)



## Partie B

### B1. Approche technique

#### [Direct Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff647715(v=pandp.10)?redirectedfrom=MSDN)

Ce pattern est utilisé lorsque le service web exige que l’utilisateur présente des identifiants pour s'authentifier. Ainsi, ce pattern permet de valider ces identifiants afin de mettre en place des contrôles supplémentaires tels que l’autorisation.

L’authentification directe implique les participants suivants : 
* **Le client :** il accède au service web et fournit les informations d’identification pour l’authentification.
* **Le service :** il est le service web qui exige l’authentification du client avant de lui permettre d’accéder au service.
* **L'identity store :** il stocke les identifiants d’un client pour un domaine d’identité particulier.

La figure ci-dessous résume les interactions entre les trois participants et illustre les différentes étapes de l'authentification directe :
![Schéma Direct Authentication](https://i.imgur.com/85yfUDi.gif)

Les trois étapes suivantes, illustrées par la figure ci-dessus, décrivent le processus d'authentification directe :
1. Le client envoie une demande au service web, en joignant des informations d’identification à cette demande.
2. Le service web valide les informations d’identité par rapport à un identity store et prend des décisions d’autorisations concernant le client. 
3. Le service web renvoie un message au client.

Il existe plusieurs implémentations possibles du pattern Direct Authentication, nous allons en détailler deux :

1. **Implémentation avec un UsernameToken dans WSE 3.0 :** L'authentification directe est implémentée pour une application en ligne qui consomme un service web utilisant le Web Service Enhancements (WSE) 3.0. L'authentification de la couche message (message layer authentication) est utilisé. Les données d'identification utilisées pour prouver l'identité du client sont validées par un service d'authentification.
2. **Implémentation de la sécurité de la couche transport (Transport Layer Security) en utilisant HTTP Basic sur HTTPS :** Cette implémentation permet la mise en oeuvre de l'authentification directe à l'aide de HTTP Basic sur HTTPS sur la couche transport. Elle utilise un type d'authentification directe bien établi et largement pris en charge dans un environnement web, ce qui la rend facile à mettre en place. Cependant, aucune capacité de protection des messages n'est fournie par cette implémentation. En effet, les informations d'identification du client sont transmises en texte clair lors du transit.
---

#### [Brokered Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff650014(v=pandp.10)?redirectedfrom=MSDN)
Ce pattern est utilisé lorsque l’authentification à un service web nécessite la présentation d’une demande de justificatifs d’identité afin de mettre en place des contrôles supplémentaires. Une interaction directe entre le client et le service web n’est pas nécessaire, un troisième acteur, l’authentication broker, fait le lien entre les deux. Le client et le service web font confiance au broker.

Quatre participants sont impliqués dans ce type d'authentification : 
* **Le client :** Il accède au service web et fournit les informations d'identification nécessaires à l'authentification lors de l'envoi de la requête au service web.
* **Le service :** Il s'agit du service web qui exige l'authentification du client avant de l'autoriser.
* **L'authentication broker :** Il authentifie les clients et exerce un contrôle sur les jetons de sécurité. Il se porte également garant du client en lui délivrant un jeton de sécurité.
* **L'identity store :** Il stocke les informations d'identification d'un client pour un domaine d'identité particulier.

![Schéma Brokered Authentication](https://i.imgur.com/DJg4w7u.gif)


La figure ci-dessus permet de visualiser les étapes de ce processus d’authentification. 
1. Le client soumet une demande d’authentification auprès de l’authentification broker.
2. L’authentification broker contacte l’identity store pour valider les références du client.
3. L’authentification broker envoie le token d’authentification au client si l’authentification est réussie. Ce dernier lui permettra de se connecter aux services pendant une période prédéfinie.
4. Un message de requête est envoyé au service avec le token d’authentification.
5. Le token est vérifié par le service.
6. Le service retourne une réponse au client.

Trois design patterns sont liés au Brokered Authentication Pattern, chacun décrit un authentication broker différent :

1. **Brokered Authentication Pattern: X.509 PKI :** l’authentication broker est basé sur le standard X.509 PKI, c’est-à-dire que des certificats X.509 sont émis par une autorité de certification (certificate authority - CA) dans une infrastructure à clés public (Public Key infrastructure - PKI) pour vérifier les justificatifs d’identités présentés par le client.
2. **Brokered Authentication Pattern: Kerberos :** l'authentification broker est basé sur le protocole d’authentification Kerberos. D’après Wikipédia, Kerberos est un protocole d'authentification réseau qui repose sur un mécanisme de clés secrètes (chiffrement symétrique) et l'utilisation de tickets, et non de mots de passe en clair, évitant ainsi le risque d'interception frauduleuse des mots de passe des utilisateurs. 
3. **Brokered Authentication Pattern: Security Token Service :** l'authentification broker est sous la forme d’un service d’émission de jetons de sécurité (Security Token Service - STS).


### B2. Solutions technologiques concurrentes

Nous allons maintenant lister différentes technologies concurrentes.

1. **Central Authentication Service (CAS) :** D'après [Wikipédia](https://fr.wikipedia.org/wiki/Central_Authentication_Service), le CAS est un système d'authentification unique (SSO) pour le web. L'utilisateur s'authentifie sur un site Web qui utilise un serveur CAS et il est alors authentifié automatiquement sur tous les autres sites web utilisant le même serveur CAS. Il évite donc de s'authentifier à chaque fois qu'on accède à une application en mettant en place un système de ticket. Ce système d'authentification est utilisé par un grand nombre d'universités et d'écoles dont l'INSA de Rouen.
2. **LemonLDAP::NG :** Solution d'authentification unique distribuée avec gestion centralisée des drous sous licence GPL, mise en place par la Gendarmerie Nationale Française. LemonLDAP::NG est un logiciel opensource fonctionnant avec des serveurs web Apache et Nginx. (source [Wikipédia](https://fr.wikipedia.org/wiki/LemonLDAP::NG))
3. **Liberty Alliance :** Il s'agit d'un système mettant en place l'authentification unique fédérée basée entre autre sur la norme SAML. Liberty Alliance permet à un utilisateur d'accéder, après s'être identifié à l'aide d'un compte unique, à des services proposés par différents fournisseurs appartenant à un même "cercle de confiance" ("Circle of Trust"). (source [Wikipédia](https://fr.wikipedia.org/wiki/Liberty_Alliance))
4. **OpenID :** Système d'authentification décentralisé permettant l'authentification unique ainsi que le partage d'attributs. 
5. **Security Assertion Markup Language (SAML) :** Il s'agit d'un standard informatique qui propose l'authentification unique sur le web. De cette manière, un utilisateur peut naviguer sur plusieurs sites différents en ne s'authentifiant qu'une seule fois, sans pour autant que ces sites aient accès à des informations trop confidentielles. (source [Wikipédia](https://fr.wikipedia.org/wiki/Security_assertion_markup_language))
6. **NT Lan Manager (NTLM) :** Protocole d'authentification utilisé dans diverses implémentations des protocoles réseau de Microsoft et pris en charge par le NTLMSSP (Fournisseur de support de sécurité NTLM). Il est aussi utilisé partout dans les systèmes de Microsoft comme un mécanisme d'authentification unique. (source [Wikipédia](https://fr.wikipedia.org/wiki/NT_Lan_Manager))


### B3. Solutions retenues

Le **protocole CAS (Central Authentication Service)** étant utilisé à l'INSA nous l'avons retenu pour mieux comprendre son fonctionnement.

CAS utilise un protocole HTTP standard. Il se base sur un principe d'échange de tickets 'opaque handles" ne transportant aucune information. On distingue quatre types de tickets : deux nécessaires au fonctionnement de base et deux dans le cas d'utilisation de proxy CAS.

* **Ticket-Granting Cookie (TGC) :** cookie de session transmis au navigateur du client lors de la phase de login (par le serveur CAS). Si le navigateur n'accepte pas de cookie, le client doit s'authentifier de nouveau à chaque appel au serveur CAS.
* **Service Ticket (ST) :** ticket authentifiant une personne pour une application web donnée. Le serveur CAS l'envoie après que le client se soit authentifié et le transporte dans l'URL. Ce ticket concerne une personne, pour un service, et utilisable une seule fois. 
* **Proxy-Granting-Ticket (PGT) :** ticket envoyé par le serveur CAS à une application web proxy CAS disposant d'un ST valide. Il confère au proxy CAS la possibilité de demander au serveur CAS de générer un Proxy Ticket (PT) pour une application tierce et une personne donnée.
* **Proxy-Ticket (PT) :** ticket généré par le serveur CAS à la demande d'un proxy CAS. Il permet d'authentifier l'utilisateur pour un service distant, avec lequel le client web n'a pas d'accès direct. Le service distant l'utilisera comme le ST.

[(Source : Wikipédia)](https://fr.wikipedia.org/wiki/Central_Authentication_Service#Principe_de_fonctionnement)


### B4. Liste de métriques

* Indicateur d'efficacité : Nombre d’authentification qu’on peut traiter dans un délai défini.
* Indicateur de fiabilité : Nombre d'authentifications ayant réussi / Nombre d'authentification ayant échoué (alors que les informations étaient correctes)
* Efficacité en temps ⇒ Indicateur dérivé : Comparer le temps de création d’un compte au temps d’authentification unique.

### B5. Découpage (WBS) pour réalisation des prototypes

![](https://i.imgur.com/alZOeGZ.png)

## Partie C

### C1. Architecture solution W

### C2. Architecture solution X

### C3. Architecture solution Y

### C4. Architecture solution Z
