# Mon projet Test


Au coeur de débats internationaux, la pollution est un phénomène majeur actuel et représente une réelle barrière pour l'avancée de l'économie.

Aujourd'hui, les grandes questions concernent bien évidemment l'environnement. Il s'agit de trouver des solutions pour lutter contre cette pollution, nocif aux êtres vivants. Ainsi, je me propose d'étudier une des espèces touchée par cette déféctuosité, les Pigeons. Ces derniers recouvrent les rues de Paris et m’accompagne dans ma vie de parisienne.C’est donc sur ce terrain que je mènerai mon étude. 

## English version


The impact of pollution on individuals will be the theme.

At the heart of international debates, pollution is a major current phenomenon and represents a real barrier for the progress of the economy.

Today, of course, the major issues concern the environment. It is about finding solutions to combat this pollution, which is harmful to living beings. Thus, I propose to study one of the species affected by this defect, the Pigeons. They cover the streets of Paris and accompany me in my life as a Parisian. It is on this ground that I will conduct my study.

## Présentation de l'équipe

Sara fernandes Domingues 

## Description synthétique du projet

**Problématique :** Comment la pollution affecte-t'elle la santé des Pigeons au cours du temps ?

**Hypothèse principale :** L’urbanisme Parisiens empiète sur le bon vivre sur la santé des Pigeons.
Il vas même réduire leurs capacité de vole.


**Hypothèses secondaires :** 

**Objectifs :** Comprendre l'adaptation au voles d'un pigeons sains toucher par la polution.

**Critère(s) d'évaluation :** l'expérience du bec ouvert qui prouve que le pigeons aprés sont vole est bien malade 

## Présentation structurée des résultats

Je vais expliquer en détails  chacuns des programmes qui ont été créé durant ces 6 semaines pour vérifier mon hypothèse et ma problématique de départ. 

def monde_separe: 

Cette définition  renvoie la création du monde qui est une liste où les pigeons qui la composent sont rangés dans l’ordre c’est à dire de l'ordre des pigeons sains puis des pigeons malades qui seront chacun classés dans différentes cellules .Juste en bas de la définition il y aura un programme qui permettra la création d’un diagramme circulaire pour la situation avant l’expérience qui vas être lancé .

def vulnérable: 

Elle renvoie l’indice du dernière pigeons sains qui serait situé le plus près d’un pigeons malade on peut le qualifier de sous code permettant de contribuer au code de transmission   


def transmission: 

Elle permet de réaliser la transmission de la pollution des pigeons malades aux pigeons saints aussi influencé par la pollution de l’atmosphère.
Explication (contaminé de droite à gauche) car les pigeon saints sont  gauche et les malade a droite) , 

Ce code ressort une liste de pourcentage de maladie pour chaque pigeon, et pour se faire, il faut rentrer une heure pour obtenir une liste qui ressort ça a un moment donnée  puisque cela évolue car la contamination ne s'arrêtera donc pas  sauf quand toute la populations sera  contaminée ,  ducoup ce code  fait ressortir la liste à un moment pile pendant la transmission  

def asemblage_pigon_transmission: 

Permet de renvoyer l’assemblage de la liste monde_separe qui deviennent des clefs  de la liste transmission. Cette fonction associe les pigeon selon leur statut (0 ou 1) à leur état de maladie.
Elle  corrige aussi le dictionnaire  renvoyé dans la fonction précédente, par exemple on peut avoir des pigeons saints qui sont tombés entièrement malade (100%) donc leur statut passe de 0 à 1.

Permet d'assembler la liste de 0, 1 etc et la liste de la définition transmission qui ressort leur état de santé    ex: {0:34, 0:50, 1:100, 1:100, 1:100}  .Globalement dans  le dictionnaire il ressort  des clés , c’est  le pigeon selon le fait qu’il soit malade(0) ou pas malade (1), et les valeurs pour chaque clé sont  leur état de santé en pourcentage. 

En générale  si on à 3 ps ( pigeons saints) et 2 pm ( pigeons malade) le monde renvoie[0,0,0,1,1] ,cette fonction  va assembler cette liste que je viens de dire juste avant et la liste  ressortie de “transmission” et dans l’ordre des valeurs à l’indice 0 ensemble, ceux à l’indice 1 ensemble, 2 aussi etc.

Par exemple: [‘je’, ‘tu’, ‘il’] c la liste que renvoie monde_separe
et [20, 45, 69] c’est la liste de santé dans l'ordre que renvoie ‘transmission’.
La fonction assemblage va renvoyer: {‘je’:20, ‘tu’:45, ‘il’:69} cela associe les je , tu et il à leurs nombre .  


def division_sante_apres:

C’est un “sous-code” qui sert à rendre le pourcentage de pigeon sain et malade dans un tuple après le temps données  puisque les pigeons saints vont diminuer et les pigeons malade vont augmenter. Ce code permet de créer le diagramme en secteurs pour la situation ‘après expérience’ 
Juste après ce code il y aura un code permettant la création d’un diagramme circulaire après expérience .
	
def vol:

Elle réalise  l'expérience de vol sauf que l’on prend pas on compte la distance mais bien l’ouverture de leur bec. Celle-ci utilise une fonction aléatoire (‘random’) car on peut pas prévoir dans la vrai vie si ils vont ouvrir leur bec ou pas c pour  ça que j'utilise une fonction random qui sera déterminé ,  précisé par son état de santé.   J’utilise son état de santé pour sa probabilité d’ouvrir le bec.

En générale cette fonction tout  d’abord permet de réaliser  une moyenne des états de santé de tous les gens qui sont pas à 100% donc de tous les 0.
Puis, avec la fonction random, les oiseaux saints donc représenté par un seul oiseau sain grâce à la moyenne, auront plus ou moins de chance d’ouvrir le bec.
Cette fonction renvoie un bool qui soit est True ça veut dire que oui les pigeons “saints” pas encore à 100%  peuvent être considéré comme malade ou soit ça renvoie False cela veut dire le contraire, que les pigeons “saints” ne sont pas encore en moyenne bien sûr  touché par cette  pollution.


## Lien vers page de blog : <a href="blog.html"> C'est ici ! </a>

## Bibliographie :

**Carte mentale de vos mots-clés, en utilisant** <a href="https://cdn.discordapp.com/attachments/692016757057126430/701066705471930408/unknown.png">Framindmap </a> 

**Liste de références des cites utilisés:

##La Croix
https://www.la-croix.com/Ethique/Environnement/Quand-l-air-est-pollue-les-pigeons-volent-plus-vite-2016-01-10-1402396

##BFM.TV
https://www.bfmtv.com/planete/une-etude-revele-pourquoi-tant-de-pigeons-parisiens-sont-estropies-1805496.html

##Persée
https://www.persee.fr/doc/linly_1160-6398_1895_num_42_1_4057

##Pigeons_vole.fr
http://pigeon-vole.fr/site/index.php/la-vie-au-pigeonnier

##La Boite à Outils SVT
https://svt.ac-versailles.fr/IMG/archives/bosvt/ir.html

##20 Minutes
https://www.20minutes.fr/paris/2575619-20190802-paris-peu-apprecies-parfois-mutiles-pigeons-paris-reseaux

##Wiquipédia 
https://fr.wikipedia.org/wiki/Pigeon_biset

##Matplotlib
https://www.science-emergence.com/Articles/Simple-diagramme-circulaire-avec-matplotlib/

##Club Francais des Bagadais 
https://club-francais-des-bagadais.jimdofree.com/le-club/la-race-les-standards-les-championnats-les-coupes-visites-d-élevages-etc/les-maladies-du-pigeon/




