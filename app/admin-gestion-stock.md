---
title: Gestion des Stocks
description: 
published: true
date: 2026-03-14T09:09:42.192Z
tags: 
editor: markdown
dateCreated: 2023-07-21T07:16:21.869Z
---

# Gestion des stocks

Pour les producteurs de produits stockés, CAMAP propose 4 solutions pour gérer les stocks en fonction du type de contrat (Classique ou variable)

![](/documentation_camap_stock.png)

# Vidéo pour comprendre la gestion des stocks

# **Gestion des Stocks**

La gestion des stocks permet de limiter le nombre maximum de produits commandés par date de distribution tout en laissant vos utilisateurs saisir leurs commandes.  
Pour utiliser la gestion des stocks, il faut l'activer dans les paramètres du “catalogue” concerné en utilisant le sous-menu “Modifier le catalogue” 

puis en cochant la case “Gestion des stocks”

![](/gestion_des_stocks_1.jpeg)

Vous pouvez ensuite pour chaque produit définir un stock disponible de 2 manières soit **“global”** soit **“par distribution”**

La valeur du stock peut être modifiée pendant toute la durée du catalogue.   
**_Attention_** la valeur du stock peut être modifiée à la baisse mais ne peut pas être fixée à une valeur inférieure aux commandes en cours. Dans un tel cas, vous devrez d'abord annuler des commandes avant de pouvoir baisser le stock.  
  
Il y a deux options de gestion des stocks, une gestion globale et une gestion par distribution.  
Dans le cas d'une gestion globale, le stock est unique et partagé pour _toutes_ les dates de distribution du catalogue.  
Dans le cas d'une gestion par distribution, le stock que je renseigne est un stock disponible à _chaque_ date de distribution du catalogue  
Des options sont possible dans le cas d'une gestion par distribution, permettant de définir une fréquence de disponibilité du produit (1 distribution sur 2 par exemple) ou des périodes de disponibilité du produit (de date à date)

## Suivi “Global” des stocks

La valeur saisie correspond à un stock global disponible pour l'ensemble des dates de distribution du “catalogue”. Cela correspond à un produit stocké comme par exemple le miel:  
Côté “ producteur” ou “coordinateur”, l'interface de saisie est la suivante:  
 

![](/gestion_des_stocks_2b.jpeg)

*En tant que producteur je dispose _d'un stock de 100 pots_ de miel d'acacia que je mets dans mon catalogue pour _l'ensemble des dates de distribution_.*

Côté “membre” l'écran de saisie de la commande est le suivant:

![](/gestion_des_stocks_3.jpeg)

*En tant que membre je visualise le niveau du stock global de manière dynamique: en saisissant ma commande de 8 pots de miel d'acacia sur les 4 dates de distribution, le niveau du stock global du producteur descend à 92 (100 - 8)*

## Suivi des stocks “Par distribution”

### Stock identique à chaque distribution

La valeur saisie correspond à un stock disponible identique pour chaque date de distribution du “catalogue”.   
Côté “ producteur” ou “coordinateur”, l'interface de saisie est la suivante:

![](/gestion_des_stocks_4.jpeg)

*En tant que producteur je dispose d'un stock de 100 pots de miel d'acacia que je mets à disposition dans mon catalogue pour _l'ensemble des 4 dates de distribution_, mais la quantité pour chacune des 4 dates de distribution sera _une constante de 25 pots_*

Côté “membre” l'écran de saisie de la commande est le suivant:

![](/gestion_des_stocks_5.jpeg)

*En tant que membre _je commande 8 pots de miel_ en quantité variable sur les 4 dates de distribution, en visualisant en dynamique le niveau des stocks restants par date de distribution.*

### Stock disponible à fréquence régulière

La valeur saisie correspond à un stock disponible identique à une fréquence régulière en fonction des dates de distribution du “catalogue”.   
Côté “ producteur” ou “coordinateur”, l'interface de saisie est la suivante:

![](/gestion_des_stocks_6.jpeg)

*En tant que producteur je dispose d'un stock de 100 pots de miel d'acacia que je mets à disposition dans mon catalogue _1 distribution (à laquelle je participe) sur 2_ à partir _du 04 septembre_, la quantité de mon stock disponible pour chacune de ces distributions sera _une constante de 50 pots_.*

Côté “membre” l'écran de saisie de la commande est le suivant:

![](/gestion_des_stocks_7.jpeg)

*En tant que membre _je commande mes 8 pots_ de miel quand le produit est disponible (1 fois sur 2) en visualisant en dynamique le niveau des stocks restants.*

## Stock disponible par période 

La valeur saisie correspond à un stock disponible pour les distributions auxquelles je participe d'une ou plusieurs périodes de temps (intervalle de dates).  Pour les autres dates de distribution du catalogue auxquelles je participe, le produit n'est pas disponible.  
Côté “ producteur” ou “coordinateur”, l'interface de saisie est la suivante:

![](/gestion_des_stocks_8.jpeg)

*En tant que producteur je dispose d'un stock de 100 pots de miel d'acacia que je mets à disposition dans mon catalogue sur la période du 2 septembre au 4 septembre. Sur cette période où je ne participe qu'à 2 dates de distribution ( le _04 septembre et le 04 décembre_ ) la quantité de mon stock disponible à chaque distribution est _une constante de 50 pots_. Pour les autres dates (les 2 dernières dates) mon produit n'est pas disponible.*

Côté “membre” l'écran de saisie de la commande est le suivant:

![](/gestion_des_stocks_9b.jpeg)

*En tant que membre _je commande 8 pots de miel_ pour les 2 premières dates de disponibilité du produit en visualisant en dynamique le niveau des stocks restants. Pour les autres dates de distribution le produit est indisponible.*

## *Visualisation globale du niveau des commandes/stocks par produit et par date de distribution*

Pour cela, dans le sous-menu “**Stock”** de la gestion de catalogue, vous pouvez visualiser de manière globale le niveau des commandes et des stocks par date de distribution et par produit.

![](/gestion_des_stocks_10_bis.jpeg)

---

![](/by-nc-sa.png)

 [Licence Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/")