#algo
git status statut des fichiers 
git add.  add les nouvelles notes de obsidian 
git commit -a -m "message" sauvegarde + message 
git push (duplication et envoie sur GitHub du coffre )

Types de donnée 

Entier int 
 négatif a positif sans virgule 

 
 décimaux (float)
 . pas une virgule 

Chaines de caractère 
(string str) toujours ""

Booléen (Bool)
True or False 

## LES OPERATIONS 

### Entiers et Décimaux
 
 addition ,multiplication,  soustraction ,division entière et la puissance **

## String 

concaténation 'salut' +"ça va'  = "salut ça va "

multiplication (python seulement)

"A *4"  = AAAA 

## Booléen 

and --> et 
or --> ou        Opérateurs logiques   
not --> non        

Algèbre de Boole 



## Boucles 

for 
permet de repeter n fois une action demander 

for i in range (start,end)
     instruction
 for i in range (0,5)
     print("hello")



while (tant que)

boucle conditionnel 

mot.lower
mot.upper 
h = mot [0]
l = len (mot)---> 5
d = mot [:-1]


## LISTE 

permet de contenir plusieurs valeurs 

chats = ["bibou","tartuffe","frimousse"]
divers = ["a",12,True,3.14]

l= [1,2,3,4]
print (l[2]) # affiche 3 
print (len(l)) affiche taille de la liste 
last index = len(l) -1

fruits = ["pomme","fraise","banane"]

for i in range (0,len(fruits)):
print (fruits[i])


## Fonction 

def somme (a,b) :
     print("la somme de {a} +{b}={a+b}")
 somme (5,2)
 somme (3,3)
         (PROCEDURE)

def somme (a,b):
     return  a+b 
 resultat = somme (5,2)  