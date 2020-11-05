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

## Partie A

### A0 : Introduction.

L’authentification avec les réseaux sociaux est une forme d’authentification où les processus d’authentification est délégué à des services dits de réseaux sociaux tels que Facebook, Google+ ou Twitter. Les informations de connexion existantes d’un utilisateur à un réseau social sont utilisées pour connecter l’utilisateur à un site web tiers. Cette technique permet de simplifier le processus de connexion pour l’utilisateur et de lui éviter d’ouvrir un compte par site. Ce type d’authentification est qualifié d’authentification unique ou Single Sign-On (SSO) en anglais. L’authentification unique regroupe toutes les méthodes d’authentification permettant à un utilisateur d’accéder à plusieurs applications informatiques ou sites sécurisés en ne procédant qu’à une seule authentification. Des protocoles de délégation d’authentification et/ou d’autorisation tel que OAuth et SAML sont utilisés. OAuth est un protocole libre qui permet d’autoriser un site web, un logiciel ou une application (dite “consommateur”), d’utiliser l’API sécurisée d’un autre site web (dit “fournisseur”) pour le compte d’un utilisateur. De son côté, le protocole SAML (Security Assertion Markup Language) est un standard ouvert permettant aux fournisseurs d’identité (IdP) de transmettre des données d’identification aux fournisseurs de services. Tout comme l’identification, l’autorisation et la gestion des utilisateurs, l’authentification est une des composantes de la Gestion des Identités et des Accès (GIA) ou Identity Access Management (IAM). La GIA est un ensemble de processus qui permet de gérer qui a accès à quelle information à travers le temps.

L'objectif du sujet est de mettre en place l'authentification avec Linkedin afin de permettre à des personnes d'accéder à des ressources gérées par le département ASI. Le but est d'améliorer et de simplifier le processus d'authentification.  

### A1. Glossaire et Mots-clés.

* Réseaux sociaux
* Identification
* Autorisation
* Utilisateur
* Sécurité
* Contrôle d’accès
* Confidentialité
* Déléguer l'authentification
* Compte
* Authentification unique

### A2. Webographie

Nous allons maintenant présenter trois sites qualifiés que nous avons utilisé pour réaliser cette monographie.

1. [SSO (Single Sign-On) définition de l’authentification unique.](https://www.lebigdata.fr/single-sign-on-sso-definition) Le Big Data, le magazine I.A., Cloud et Big Data [en ligne]. Bastien L. 11 juillet 2019. Dernière consultation le 01 novembre 2020.
2. [What is IAM? Identity and access management explained.](https://www.csoonline.com/article/2120384/what-is-iam-identity-and-access-management-explained.html) CSO Magazine [en ligne]. James A. Martin et John K. Waters. 9 octobre 2018. Dernière consultation le 01 novembre 2020.
3. [Social Login : faire d’un rêve une réalité (1/2)](https://www.riskinsight-wavestone.com/2018/03/social-login-reve-realite-12/) Wavestone [en ligne]. Pascal Vidal et Jérémy Pageaux. 28/03/2018. Dernière consultation le 05 novembre 2020. 


### A3. Bibliographie

Dans cette partie, nous réaliserons la bibliographie de trois livres avec la mise en exergue des sections qui nous semblent pertinentes dans la table des matières.

1. Ric Shreves. Social Media Optimization for Dummies. John Wiley & Sons, Inc. 2015. 329p.
* Section pertinente : 
    * Partie III : Leveraging Social Media with Your Website, Implementing Social Login (Facebook Login, Twitter Login, Google+ Login, Other Login alternatives) p.103-107.
2. Maryline Laurent, Samia Bouzefrane, La gestion des identités numériques. Collection Systèmes d’information, web et informatique ubiquitaire. ISTE Group. 2015. 284p. 
* Sections pertinentes :
    * Chapitre 2 : La gestion d’identités par la fédération. 2.4. SAML 2.0 et OAuth 2.0  standards de fait de la fédération d’identités, p. 125-138
    * Chapitre 3 : Système d’authentification. p.139
3. Omondi Orondo, Identity & Access Management: A Systems Engineering Approach, 2016. 337p. 
* Sections pertinentes :
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
* Indicateur d'efficacité : le nombre d’authentification qu’on peut traiter dans un délai défini.
* Indicateur de fiabilité : la bonne association des comptes et le succès de l’authentification.


Indicateur dérivé pour chaque facteur :
* Sécurité ⇒ Indicateur dérivé : est-ce que les identifiants de l’utilisateur ont bien été protégé durant l’authentification ? 
* Interopérabilité ⇒ Indicateur dérivé : mesurer le temps et les ressources pour faire interagir l’application et le réseau social.
* Efficacité en temps ⇒ Indicateur dérivé : comparer le temps de création d’un compte au temps d’authentification unique.

### A7. Références théoriques

Microsoft patterns & practices propose un ensemble de patterns en adéquation avec notre sujet : **[Authentication Patterns](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff647374(v=pandp.10))**.

L’authentification est le processus d’identification d’un individu en utilisant des facteurs d’authentification (en général un identifiant et un mot de passe). Elle permet d’assurer la sécurité des services web. Les Authentication Patterns se décompose en deux architectural pattern : **[Direct Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff647715(v=pandp.10)?redirectedfrom=MSDN)** et **[Brokered Authentication](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ff650014(v=pandp.10)?redirectedfrom=MSDN)**. Ces deux patterns se concentrent sur la relation qui existe entre un client et un service  web.  

Le **Direct Authentication Pattern** est utilisé lorsque le client et le service partage une relation de confiance leur permettant d’échanger des facteurs d’authentification comme des mots de passes par exemple. 

Dans le cas contraire, le **Brokered Authentication Pattern** est utilisé. Ce pattern introduit une troisième entité, l’Authentication Broker, qui va réaliser l’authentification du client et émettre un token qui va être envoyé au service. Brokered Authentication Pattern se divise en trois design patterns qui sont Security Token Service, X.509 PKI et Kerberos. Ces trois design patterns  correspondent au trois security tokens fourni par le WSE (Web Service Enhancements).

![Schéma Authentication Patterns](https://i.imgur.com/DF4SMvb.gif)

## Partie B

### B1. Approche technique

### B2. Solutions technologiques concurrentes

### B3. Solutions retenues

### B4. Liste de métriques

### B5. Découpage (WBS) pour réalisation des prototypes

## Partie C

### C1. Architecture solution W

### C2. Architecture solution X

### C3. Architecture solution Y

### C4. Architecture solution Z
