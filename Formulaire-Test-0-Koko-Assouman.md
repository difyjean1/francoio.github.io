---
title: "Formulaire de réponse pour le test 0 -- TD-1"
output: pdf_document
---

** **



#### Problème 1 



##### Question 1

* Déterminer la probabilité de l'événement $(N_E > k)$, pour tout $k \geq 1$. Quelle est la loi de $N_E$ ?

###### Réponse : 
Soit  k un entier naturel non  nul

$(N_E>k)= (\bigcup_{i=k+1}^{+\infty} N_E=i)$

$       =\sum_{i=k+1}^{+\infty} (N_E=i)$

$       =\sum_{i=k+1}^{+\infty} 1/6*(5/6)^{i-1}$

$       = (5/6)^k$
La loi de $N_E$
$N_E$ suit une loi géométrique de paramètre $1/6$

##### Question 2
* Calculer la probabilité de l'événement $(N > k)$, pour tout $k \geq 1$. Quelle est la loi de $N$ ?


###### Réponse :

On utilise la formule des probabilités totales,
$(N>k)=\sum_{i=k+1}^{+\infty} (N>k|N_E=i)\times(N_E=i)$

$     =1/102\times(25/42)^k+7/102\times(25/42)^{k+1}$

Loi de $N$

$(N=k)=6/15\times(5/7)^k

##### Question 3

* Quelle est la probabilité pour que Eva gagne ? 


###### Réponse : 
E:"Eva gagne"

$(E)=((N_E=k),(N_R>k))$

$   =1/5\times(5/7)^k$


##### Question 4

* Quelle est la probabilité de match nul ?


###### Réponse : 
On a un match nul si $N_E=N_R$

$(Nul)=1/42\times(5/7)^{k-1}

##### Question 5

* Calculer la probabilité que la partie a duré moins de 3 manches sachant qu'Eva a gagné.


###### Réponse : 


** **

#### Problème 2


  
##### Question 1

*  Calculer la probabilité que la variable aléatoire $W$ soit inférieure ou égale à $1/3$.  

###### Réponse : 

  
##### Question 2

*  Calculer l'espérance de la variable aléatoire $W^2$.  

###### Réponse : 

** **

#### Problème 3 


##### Question 1

*  Calculer l'espérance de la variable aléatoire $Z$.  

###### Réponse : 
