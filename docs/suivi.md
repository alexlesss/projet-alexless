---
title: Suivi du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Suivi de projet

## Semaine 1-2 (25 mai - 7 juin)

### Objectifs de la période
- Initialiser le site Web
- Débuter les lectures proposées par Pr. Yu
- Comprendre l'idée générale du projet

### Travail réalisé

!!! abstract "Avancement"
    - Lectures initiales, principalement "An introduction to Mathematical Cryptography" par Hoffstein et al.
        - Grand besoin de comprendre les bases de la cryptographie avant d'explorer des systèmes précis
    - Prise de notes dans un fichier sur Overleaf
    - Création d'un répertoire GitHub pour le site Web

### Difficultés rencontrées

!!! warning "Difficultés"
    - Lourdeur mathématique et quantité de prérequis nécessaires à l'entreprise du projet.
        - Il était nécessaire que je lise une quantité impressionante d'articles mathématique pour comprendre le domaine dans lequel j'allais faire de la recherche cet été. Cependant, plus je lisais, plus il me semblait irréalisable d'arriver à faire une contribution intéressante cet été en environ 150 heures. 

### Décisions et ajustements

!!! info "Décisions"
    - En expliquant mes notes initiales à la Pr. Yu lors de notre rencontre du 8 juin, nous avons réalisé qu'il serait pertinent pour moi de rédiger proprement mes apprentissages. Le fichier Overleaf changea donc de vocation: c'est là que me vint l'idée de rédiger une revue de littérature. 
        - La cryptographie post-quantique basée sur les réseaux n'est pas extrêmement complexe mais nécessite de nombreux prérequis, tel que nous l'avons présenté plus haut. Advenant un échec futur de ma recherche par manque de temps, j'aurais tout de même rédigé une revue d'introduction à la cryptographie basée sur les réseaux. Documenter les apprentissages m'ayant permis de commencer à étudier des systèmes d'encryption pratiques pourrait alors servir à d'autres étudiants au baccalauréat désireux de débuter dans la même voie. 


## Semaine 3-4 (8 - 21 juin)

### Objectifs de la période
- Rédiger la revue de littérature.
- Débuter à entrevoir le lien entre la cryptographie post-quantique et la programmation en nombres entiers.

### Travail réalisé

!!! abstract "Avancement"
    - Rédaction propre des notes des deux premières semaines, mise en place des concepts de cryptographie de base.
        - Attention particulière à la théorie des réseaux euclidiens.
        - Première rédaction de style universitaire à vie! La Pr. Yu m'a particulièrement bien guidé à travers cette exploration.

### Difficultés rencontrées

!!! warning "Difficultés"
    - Kimberly et moi devions nous rencontrer le 22 juin. Cependant, le métro a fermé ses portes à cause de l'incident ayant causé la vie à un policier près de l'autoroute Décarie. Nous avons donc dû reporter notre réunion à la semaine suivante.

## Semaine 5 (22 - 28 juin)

### Objectifs de la période
- Conclusion de la revue de littérature.
- Débuter de la modélisation en programmation en nombres entiers.

### Travail réalisé

!!! abstract "Avancement"
    - Conclusion de la revue de littérature sur un chapitre concernant problème LWE, le problème principal sur lequel nous travaillons dans notre travail.
    - Découverte de l'article de Masaaki Shirase.

### Décisions et ajustements

!!! info "Décisions"
    - Une section "prérequis d'optimisation" a été ajouté a la revue de littérature: elle sera complétée selon ce qui est présenté dans l'article de Shiraase et selon les améliorations apportées plus tard. Il n'est pas nécessaire de faire une très longue ébauche présentant l'optimisation discrète car cela viendrait gruger beaucoup du temps que nous souhaitons porter à son utilisation.

## Semaine 6 (29 juin - 5 juillet)

### Objectifs de la période
- Installer Gurobi et comprendre son utilisation
- Comprendre les algorithmes Branch-and-Bound et Cutting plane
- Implémenter la réduction de Shirase sous Gurobi et exécuter des tests computationnels depuis celle-ci
- Déterminer les limites du modèle de base
- Présenter les réalisations notables actuelles à la mise en commun du 3 juillet
- Kim m'a aussi présenté de nombreuses avenues en terme d'améliorations possibles au modèle de Shirase: la direction était donc libre à moi pour la suite.

### Difficultés rencontrées

!!! warning "Difficultés"
    - J'ai beaucoup manqué de temps pour avancer mon travail cette semaine dû à des événements hors de mon contrôle (et dans mon contrôle aussi: j'ai un peu procrastiné). J'ai donc dû repousser la majorité des tâches planifiées à la semaine suivante. 

### Travail réalisé

!!! abstract "Avancement"
    - Installation et activation de Gurobi
    - Correction des coquilles pointés par Kimberly
    - Présentation à la mise en commun
        - Ça fait pas beaucoup par rapport à ce qui était prévu... Le reste est reporté à la semaine suivante.


## Semaine 7 (6 - 12 juillet)

### Objectifs de la période
- Présenter la réduction de Shirase dans mon rapport.
- Implémenter la réduction de Shirase sous Gurobi et exécuter des tests computationnels depuis celle-ci
- Déterminer les limites du modèle de base

### Travail réalisé

!!! abstract "Avancement"
    - Rédaction française et paufinement de la réduction de Shirase.
    - Élaboration de l'architecture iniitale du package de solveur. Mise en place d'un répertoire GitHub.
    - Implémentation Python du solveur de Shirase.
    - Génération de benchmarks sommaires de notre modèle de base. 
    - Correction du texte rédigé jusqu'à présent.


## Semaine 8 (13 - 19 juillet)

### Objectifs de la période
- Début de rédaction de prérequis d'optimisation. Lecture plus poussée de méthodes d'amélioration d'un modèle de programmation en nombres entiers.
- Démonstration de la performance de notre solveur face aux cryptosystèmes actuels. 

### Travail réalisé

!!! abstract "Avancement"
    - Réduction du problème Module-LWE au problème Search-LWE, soit le problème sur lequel fonctionne notre solveur.
    - Début de rédaction de prérequis d'optimisation. Transfert de cette section dans la la revue de littérature.
    - Tests sur des modèles alternatifs.
    - Téléchargement de la bibliothèque FPyLLL et WSL, un sous-sytème windows pour Linux.


### Décisions et ajustements

!!! info "Décisions"
    - L'état de l'art pour la résolution de LWE passe toujours par un algorithme de réduction de réseau quelconque (soit LLL soit BKZ). Nous avons donc cherché à initialement réduire le réseau correspondant au problème d'une manière ou d'une autre.

### Difficultés rencontrées

!!! warning "Difficultés"
    - La bibliothèque FYpLLL nécessite une machine Linux pour s'exécuter. Il a donc fallut entièrement télécharger WSL, ce qui pris un temps considérable


## Semaine 9 (20 - 26 juillet)

### Objectifs de la période
- Implémenter correctement la réduction LLL sur le réseau correspondant à une instance de LWE.
- Tester des solveurs alternatifs.
- Préparation du diaporama pour la mise en commun.

### Travail réalisé

!!! abstract "Avancement"
    - Amélioration du code, fusion des générateurs. 
    - Transformation des fonctions de benchmark, ajout de médiane et de manipulation plus simple des logs.
    - Remplacement des fonctions de génération aléatoires par des fonctions purement déterministes (ce qui permet la reproductabilité des benchmarks).
    - Incorporation de l'article de Shuxian Jiang et présentation du résultat principal de ce dernier.
    - Codage de trois solveurs différents et test de ceux-ci. 


### Décisions et ajustements

!!! info "Décisions"
    - L'algorithme LLL fut beaucoup trop puissant et intéressant quant à la résolution de notre projet. Les petites optimisation de PLNE furent donc mises de côté, le focus étant sur la quantification plus juste du modèle avec réduction LLL.


## Semaine 10 (27 juillet - 2 août)

### Objectifs de la période
- Tests plus poussés de notre nouveau modèle.
- Preuve théorique d'exactitude entre le modèle de Shirase et le modèle de Jiang.
- Présentation à la foire aux projets.
- Rédaction de la conclusion et mise à jour des priorités concernant le projet.
- Début du rapport final (pas eu le temps finalement)

### Travail réalisé

!!! abstract "Avancement"
    - Fin de la rédaction de prérequis d'optimisation, rédaction de la conclusion au travail.
    - Rédaction de la preuve théorique d'exactitude entre Shirase et Jiang.
    - Correction et mise en page finale de la revue de littérature. 


## Semaine 11 (3 - 10 août)

### Objectifs de la période
- Rédiger le rapport en se basant sur ce qui est déjà fait, tant la revue de littérature que le rapport actuel d'évolution des solveurs.
- Meilleure quantification des limites des solveurs avec lesquels nous travaillons. 
- Présentation finale et préparation du diaporama associé à celle-ci.
- Remise du rapport final, de la revue de littérature et push final associé au projet sur GitHub.
- Terminer le site Web.

### Travail réalisé

!!! abstract "Avancement"





## À venir...
- Rédaction d'un article officialisant nous trouvailles
- Exécution de tests numériques plus exhaustifs.
- Publication de celui-ci et de la revue de littérature rédigée.
- Correction et formatage de ce qui a été fait.