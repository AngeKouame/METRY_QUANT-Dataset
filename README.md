Test Technique Quantmetry
Objectif
Cet exercice a pour objectif d’evaluer vos competences en data science, `a travers votre
connaissance des statistiques, de l’apprentissage automatique, et vos capacit´es en programmation.
Votre rendu comportera :
I Un document de r´eponse aux questions d’une longueur de 6 pages au maximum
(format PDF ou Word).
I Un dossier zipp´e contenant votre code R ou Python (pr´ecisez la version utilis´ee).
Votre code devra pouvoir ˆetre rejou´e facilement. N’h´esitez pas `a inclure un README.
Enonc´e
Le jeu de donn´ees contenu dans data.csv d´ecrit des candidatures au poste de chercheur
d’or chez OrF´ee. Votre objectif consiste `a pr´edire le succ`es ou l’´echec d’une candidature.
Le jeu de donn´ees comporte 11 colonnes :
♦ date – date de la candidature
♦ age – ˆage du candidat
♦ diplome – plus haut diplˆome obtenu (bac, licence, master, doctorat)
♦ specialite – sp´ecialit´e du diplˆome (g´eologie, forage, d´etective, arch´eologie, . . . )
♦ salaire – salaire demand´e
♦ dispo – oui : disponibilit´e imm´ediate, non : pas disponible imm´ediatement
♦ sexe – f´eminin (F) ou masculin (M)
♦ exp – nombre d’ann´ees d’exp´erience
♦ cheveux – couleur des cheveux (chˆatain, brun, blond, roux)
♦ note – note (sur 100) obtenue `a l’exercice de recherche d’or
♦ embauche – le candidat a-t-il ´et´e embauch´e ? (0 : non, 1 : oui)
1. Statistiques descriptives
1. D´ecrivez le jeu de donn´ees. Pr´esentez seulement les analyses et ´eventuels retraitements qui vous paraissent les plus pertinents et faites une premi`ere conclusion sur
les variables `a s´electionner en vue de la pr´ediction du succ`es ou de l’´echec d’une
candidature.
2. Y a-t-il une d´ependance statistiquement significative entre :
(a) La specialite et le sexe ?
(b) La couleur de cheveux et le salaire demand´e ?
(c) Le nombre d’annees d’exp´erience et la note `a l’exercice ?
2. Machine Learning
1. Concevez un mod`ele permettant de pr´edire la variable embauche et expliquez votre
choix d’algorithme. Si votre mod`ele comporte des sp´ecificit´es de param´etrage, justifiez ´egalement vos choix de param`etres.
2. Quelles sont les variables les plus importantes de votre mod`ele? Commentez.
3. D´ecrivez et justifiez le crit`ere de performance utilis´e.
4. Proposez deux `a trois pistes d’am´elioration de votre mod`ele.
2
