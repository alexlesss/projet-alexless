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
En 1994, Peter Shor publie un article révolutionnaire. Par ce dernier, il argumente via un algorithme portant désormais son nom qu'il est possible de rapidement factoriser un nombre entier naturel en travaillant avec un ordinateur quantique. Advenant le cas de la conception d'un ordinateur de ce type, le système cryptographique RSA, soit l'un des plus utilisé à travers internet, ne serait plus fiable. En effet, RSA dépend de la factorisation d'un tel nombre entier, comme les ordinateurs classiques ne peuvent travailler sur ce problème efficacement. Il est donc impératif de proposer des systèmes de cryptographie alternatifs, que l'on croit résistants aux potentielles technologies quantiques: c'est là qu'est née la cryptographie post-quantique, soit une collection de techniques classiques qui se doivent de sécuriser l'information dans un monde où l'ordinateur quantique existe. Parmis celles-ci, certaines sont décryptables par des programmations en nombres entiers.
</p>


### Problématique
<p style="text-align: justify;">
Il est toujours pertinent de remettre en question des solutions établies, et cela est particulièrement mis de l'avant en cryptographie. Il est nécessaire de réévaluer les méthodes de protection proposées car les failles se situent souvent dans les endroits où l'on cherche le moins. Le monde post-quantique et ses schémas d'encryption basés sur les réseaux n'en font forcément pas exception, justifiant notre travail.
</p>

### Proposition et objectifs
<p style="text-align: justify;">
Notre projet se divise en deux temps. Nous proposons pour commencer une revue de littérature sur le sujet, laquelle se devant de décrire les problèmes cryptographiques à l'étude et leur pertinence tout en énumérant les principales manières de les briser. Une telle mise en commun permettra de mieux saisir l'état de l'art quant à l'attaque de ces problèmes, et servira de référence à quiconque cherchant une nouvelle direction de casse sur laquelle travailler. En second lieu, l'analyse se raffinera sur la capacité de la programmation en nombres entiers sur les problèmes travaillés et terminera par une réflexion quant à des manières d'optimiser son applicabilité. Comme nous nous concentrons sur une sous-catégorie de méthodes d'attaque, il nous est possible d'approfondir notre recherche: Mme. Yu travaillant dans le domaine des programmations linéaires, son expertise pourrait donc directement être appliquée afin de découvrir des potentielles faiblesses. Il est difficile de quantifier la recherche et donc d'offrir des objectifs tangibles, mais servir de point de départ à de la recherche future serait un excellent début! Nous avons comme objectif de fournir une introduction claire, concise et parfois imagée qui simpliferait l'acquisition rapide des connaissances en lien avec notre projet. 
</p>

### Méthodologie
<p style="text-align: justify;">
Il est normal qu'une grande part du projet soit consacrée à de la lecture comme les concepts abdordées dépassent ce qui est enseigné dans les cours du baccalauréat. Des pistes initiales, tant des recommandations d'articles que des noms d'auteurs pertinents, seront poussées par la superviseure. Des rencontres hebdomadaires ou bihebdomadaires seront organisées pour que les lectures continuent d'aller dans la bonne direction. L'étudiant fournira un rapport à la superviseure lors de ces recontres pour qu'elle reste à jour avec l'évolution des concepts mathématique et qu'elle puisse tenir compte de l'acquisition des savoirs de l'étudiant. La superviseure s'assurera que le contenu rédigé et présenté de manière propre à l'académie par l'étudiant et agira comme guide à travers une première exploration de la recherche en mathématique et informatique. Il y aura une phase de transition importante entre la conception de la revue de littérature et entre le début de l'entreprise de travaux de perfectionnement d'algorithme, cette phase se situant juste un peu après la moitié de la période allouée pour le projet. La méthodologie pour la deuxième partie du projet reste à poser! 
</p>

### Validation et Évaluation
<p style="text-align: justify;">
Comme validation finale, il sera pertinent de présenter le projet à un autre expert autant en informatique quantique et théorique qu'en recherche opérationnelle oeuvrant à l'université de Montréal. Ces derniers pourront porter un oeil critique sur le travail qui a été entrepris, autant dans son fond que dans sa forme. Plus tard, le projet sera forcément présenté à la foire aux projets IFT3150 se tenant peu avant le début de la session d'automne. Des retours d'autres étudiants sont donc attendus. 
</p>

## Échéancier

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités                      | Début   |   Fin   | Livrable                            | Statut      |
|--------------------------------|---------|---------|-------------------------------------|-------------|
| Ouverture de projet            | 4 mai   | 15 mai  | Proposition de projet               | ✅ Terminé  |
| Études préliminaires           | 4 mai   | 22 mai  | Document d'analyse                  | 🔄 En cours |
| Présentation + Rapport         | 7 aout  | 14 aout | Présentation + Rapport              | ⏳ À venir  |
