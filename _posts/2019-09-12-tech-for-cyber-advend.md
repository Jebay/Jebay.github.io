---
layout: post
title: "Tech for Cyber"
date: 2019-09-12
excerpt: "Compte-rendu Conférence"
tags: [post, images, conférence]
comments: true
feature: https://www.advens.fr/sites/default/files/public/styles/full_event_up/public/events/images/bandeau_tech_for_cyber_v3.1_plan_de_travail_1.png?itok=rVaLVcKa
---

## TL;DR
Une matinée de présentation commercial d'outils de sécurité informatique.
Pour Sam Curry (Chief Product / Security Officer at Cybereason), les SOC seront autonomes à horizon 2025.

Une invitation à un workshop Palo Alto **[PROTÉGEZ VOS WORKLOADS KUBERNETES SUR GOOGLE CLOUD PLATFORM](https://register.paloaltonetworks.com/googlehowparis?utm_source=outlook&utm_medium=email&utm_campaign=%7B%7Bprogram.Name%7D%7D-%7B%7Bsystem.dateTime%7D%7D)**


# Planning de la journée :
-   9h00 : Café d’accueil
-   9h30 : Ouverture par  Advens  avec intervention du Ministère des Armées
-   9h45 – 10h30 : Atelier Vectra & Proofpoint
-   10h40 – 11h25 : Atelier Palo Alto & Alsid
-   11h25 – 11h55 : Pause Networking
-   12h00 – 12h30 : Keynote Cyberason
-   12h40 – 13h00 : Intervention Thomas Ruyant (skipper)
-   13h00 : Cocktail / Déjeuner

## Ouverture de l'événement par [David Buhan](https://www.linkedin.com/in/davidbuhan/) ( CEO Advens)
David Buhan présente l'événement comme un endroit pour réfléchir sur la manière dont les nouvelles technologies peuvent nous aider à répondre aux menaces informatiques.
Le nom de l'événement "Tech for Cyber" en est la preuve : "la technologie au service de la sécurité".

## Intervention de [Dominique Luzeaux](https://www.linkedin.com/in/dominique-luzeaux-1aa0245/) Ingénieur Général de l’Armement et Directeur Adjoint de la DIRISI au sein du Ministères des Armées
Selon lui, pour faire face aux nouvelles menaces, nous devons revoir notre modèle de penser la sécurité informatique. Il faut arrêter le temps ou chacun garder précieusement les informations qu'il détenait et qu'il faut maintenant accepter de partager à la "communauté" afin d'aider à obtenir un meilleur niveau de sécurité.

Face à la pénurie de profil IT et sécurité en France, les entreprises (PME, TPE, ...) ont, selon Dominique Luzeaux, intêret à collaborer ensemble, rassembler les talents de chacun pour proposer des produits, des solutions qui aient du poids au niveau de l'Europe. Dominique Luzeaux aimerait voir émerger une compétence française Cyber pour le marché européen.

## Atelier ProofPoint ([Gaetan Gesret](https://www.linkedin.com/in/gaetangesret/)) - Vectra ([Christophe Jolly](https://www.linkedin.com/in/christophe-jolly-02994b/))
**Problématique :** *On a pleins d'outils différents de sécurité et pourtant on reste toujours sujet aux nouvelles menaces informatiques.*

Positionnement Vectra : Déléguer à une machine la detection des menaces pour se concentrer sur la résolution des alertes.
 - [Solution Cognito](http://www.vectra.ai/ndr) : *Intelligent, AI-driven  threat detection and response for native and hybrid clouds*

Positionnement ProofPoint: Protéger l'humain avant tout (email, awareness, ...) car c'est souvent d'un mauvais comportement (volontaire ou non) que les menaces arrivent.
- [ProofPoint Sécurity Awareness & Training](https://www.proofpoint.com/us/product-family/security-awareness-training) : *Turn your end users into a strong last line of defense against phishing and other cyberattacks*

## Atelier Alsid ([Sylvain Cortes](https://www.linkedin.com/in/sylvaincortes/)) - Palo Alto ([Arnaud Besnard](https://www.linkedin.com/in/arnaud-besnard-0a64b12/))
**Problématique :** *"Comment détecter les menaces à l’intérieur et à l’extérieur à l’heure du multi-cloud ?"*

**Philosophie du Zero Trust:** La confiance est une vulnérabilité. Il ne faut faire confiance à personne et à aucun outil. Toute attaque vient d'un élément de confiance de notre SI.
On part du principe qu'on est infecté et on vas voir comment on peut faire pour sécuriser son SI.
[Article Global Security Mag sur le sujet.](https://www.globalsecuritymag.fr/Pourquoi-le-modele-Zero-Trust-va,20190517,87152.html)

> On peut dire que Lénine est un précurseur du Zero Trust "***La confiance n**'**exclut pas le contrôle**"*

Le but du Zero Trust est bien évidement de protéger les données des entreprises.

Positionnement Palo Alto : Sécurisation du cloud en portant sur les principaux fournisseurs (GCP et AWS) leurs produits (switch et firewall).

Positionnement de Alsid : Sécurisation de l'AD.
Presque toutes les entreprises possèdent un Active Directory qui, souvent, a été déployé il y a quelques années. Alsid propose un outil qui va, avec un simple accés utilisateur à l'AD, ressortir des KPI sécurité sur la configuration de ce dernier. Leur produit propose également des playbooks de remédiation aux mauvais indicateurs remontés.

## Cybereason : The Next Generation of SOC ([Sam Curry](https://www.linkedin.com/in/currysam/))
Sam Curry aime à dire que les SOC sont pour lui l'outils qu'il aime le plus à désaimer. Selon lui, cet outil a été vendu comme un produit magique, que beaucoup se vantent d'avoir. Et malheureusement, peu de SOC ont été correctement configuré, peu d'entreprise ont une équipe qui gère cet outil, et encore moins nombreuses sont les entreprises qui ont une équipe en charge de la réponse à incident et investigation des événements remonté par le SOC.

Les problèmes rencontrés aujourd'hui sont multiples :

 - Il y a de plus en plus de données à analyser (plus de endpoints, plus de stockage et d'analyses dans le cloud, les heures de travail augmente avec la mobilité, la rapidité du réseau augmente, de plus en plus de collaborateurs)
 - Un manque de personnes qualifiées (En 2020 il y aura 3,5M de postes non pourvus)
 - La surface d'attaque ne fait qu'augmenter 
 
 Pour le futur, le SOC devra être autonome afin de pouvoir répondre aux nouvelles menaces. Sam Curry parle d'*Autonomous SOC* ou *AuSOC*. Ce New Generation SOC sera drivé par les datas, devra être capable de générer lui même des nouvelles alertes en fonction des données qu'il collecte pour laisser le temps aux équipes de faire l'investigation.

## Intervention de clôture par Thomas Ruyant
Blabla ... je suis un skipper ... je fais de la gestion de risque à mon niveau ... blabla
