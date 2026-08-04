---
title: Vue d'ensemble du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Vue d'ensemble du projet

!!! info "Informations générales"
    **Session**: Été 2026  
    **Auteur(s)**: Alexis Lessnick  
    **Thème(s)**: Programmation en nombres entiers, cryptographie post-quantique.  
    **Superviseur(s)**: Kimberly Yu  

## Description du projet
<p style="text-align: justify;">
Ce projet vise à étudier le rôle de la programmation en nombres entiers dans l’analyse et l’attaque de schémas de cryptographie post-quantique, notamment ceux basés sur le problème Learning With Errors (LWE). L’étudiant(e) fera une revue de la littérature sur les méthodes d’attaque existantes, en mettant l’accent sur les approches d’optimisation discrète et leurs liens avec les réseaux (lattices). Le projet consistera à comprendre les modèles mathématiques de base, à examiner comment la programmation en nombres entiers peut être utilisée pour traiter ces problèmes, et à comparer son efficacité avec celle des méthodes classiques. Le projet comprendra également la lecture et la rédaction de preuves mathématiques rigoureuses, ainsi que la programmation d’algorithmes et la réalisation d’expériences numériques.
</p>

### Contexte
<p style="text-align: justify;">
En 1994, Peter Shor publie un article révolutionnaire. Par ce dernier, il argumente via un algorithme portant désormais son nom qu'il est possible de rapidement factoriser un nombre entier naturel en travaillant avec un ordinateur quantique. Advenant le cas de la conception d'un ordinateur de ce type, le système cryptographique RSA, soit l'un des plus utilisé à travers internet, ne serait plus fiable. En effet, RSA dépend de la factorisation d'un tel nombre entier, comme les ordinateurs classiques ne peuvent travailler sur ce problème efficacement. Il est donc impératif de proposer des systèmes de cryptographie alternatifs, que l'on croit résistants aux potentielles technologies quantiques: c'est là qu'est née la cryptographie post-quantique, soit une collection de techniques classiques qui se doivent de sécuriser l'information dans un monde où l'ordinateur quantique existe. Cependant, comme ces techniques sont purement classiques, il est d'actualité d'évaluer leur sécurité face aux ordinateurs actuels. 
</p>


### Problématique
<p style="text-align: justify;">
Les travaux jumelant optimisation et cryptosystèmes basés sur les réseaux sont très rares: de plus, dans les quelques articles existant, le modèle d'optimisation n'en est jamais un de programmation en nombres entiers: il découle souvent du monde quantique et est difficilement exécutable sans une expertise poussée et du matériel spécialisé. 
</p>

### Proposition et objectifs
<p style="text-align: justify;">
Notre projet se divise en deux temps. Nous proposons pour commencer une revue de littérature sur le sujet, laquelle se devant de décrire les problèmes cryptographiques à l'étude, d'analyser leur pertinence et leur origine, tout en présentant l'état de l'art quant à l'attaque de ces problèmes. Une telle mise en commun de ces savoirs permettra de mieux saisir l'état de l'art quant à l'attaque de ces problèmes, et servira de référence à quiconque cherchant à s'initier au sujet: notons que nous visons ici principalement les étudiants au baccalauréat. En second lieu, l'analyse se raffinera sur l'implémentation concrète d'une attaque basée sur la programmation en nombres entiers cherchant à casser Learning With Errors (LWE), soit l'un des cryptosystèmes présentés plus tôt. Celle-ci se terminera par une réflexion quant à des manières d'optimiser son applicabilité. Somme toute, nous avons donc comme objectif de fournir une introduction concise aux cryptosystèmes basés sur les réseaux, ainsi que d'en attaquer un via la programmation en nombres entiers tout en quantifiant ses limites. Ces contributions pourront alors servir de base à de la recherche future sur un sujet n'ayant jamais été directement exploré.
</p>

### Méthodologie
<p style="text-align: justify;">
La première partie du projet sera principalement consacrée à de la lecture: les concepts abordés dépassent ce qui est enseigné dans les cours du baccalauréat, et il sera donc nécessaire de se renseigner d'avatage. Des pistes initiales, tant des recommandations d'articles que des noms d'auteurs pertinents, seront poussées par la superviseure. Des rencontres hebdomadaires ou bihebdomadaires seront organisées pour que les lectures continuent d'aller dans la bonne direction. L'étudiant fournira un rapport à la superviseure lors de ces rencontres pour qu'elle reste à jour avec l'évolution des concepts mathématiques et qu'elle puisse tenir compte de l'acquisition des savoirs de l'étudiant. La superviseure s'assurera ensuite que le contenu rédigé et présenté de manière propre à l'académie et agira comme guide à travers une première exploration de la recherche en mathématique et informatique. Ensuite, un solveur simple sur le cryptosystème Learning With Errors (LWE) sera programmé. Celui-ci implémentera des modélisations variées en programmation en nombres entiers: des tests numériques seront effectués, permettant de quantifier la performance des différents modèles et de l'impact des variations entre ces derniers. Pr. Yu travaillant dans le domaine des programmations linéaires, son expertise pourrait donc directement être appliquée afin de découvrir des potentielles faiblesses. Le modèle de base sera alors amélioré itérativement, tandis que le modèle final sera comparé avec les standards de l'industrie.
</p>

### Validation et Évaluation
<p style="text-align: justify;">
Comme validation finale, il sera pertinent de présenter le projet à un autre expert autant en informatique quantique et théorique qu'en recherche opérationnelle oeuvrant à l'université de Montréal. Ces derniers pourront porter un oeil critique sur le travail qui a été entrepris, autant dans son fond que dans sa forme. Plus tard, le projet sera forcément présenté à la foire aux projets IFT3150 se tenant peu avant le début de la session d'automne. Des retours d'autres étudiants sont donc attendus. Nous comptons aussi faire lire la revue de littérature initiale à des étudiants n'étant pas dans un domaine mathématique: il sera intéressant d'entendre leurs retours et comprendre quels sont les sujets les plus faciles à apprivoiser, et au contraire, lesquels sont un peu plus ardus pour un débutant.
</p>

## Échéancier sommaire

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités                      | Début   |   Fin   | Livrable                            | Statut      |
|--------------------------------|---------|---------|-------------------------------------|-------------|
| Exploration initiale           | 25 mai   | 8 juin  | Proposition de projet             | ✅ Terminé  |
| Lecture approfondie et rédaction           | 8 juin   | 29 juin  | Revue de littérature                  | ✅ Terminé  |
| Modélisation mathématique et implémentation numérique.           | 29 juin   | 13 juillet  | Solveur Gurobi de base, tests numériques initiaux.                  | ✅ Terminé  |
| Exploration d'optimisation possibles          | 13 juillet   | 27 juillet  | Modèle de solveur amélioré.                 | ✅ Terminé  |
| Ajustements et retouches, rédaction finale          | 27 juillet  | 10 aout | Présentation, rapport et modèle final du solveur. Revue de littérature corrigée. Tests numériques finaux.              | ⏳ À venir  |
