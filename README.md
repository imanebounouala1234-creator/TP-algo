# TP-algo
TP 1 :
Exercice 1
Algorithme code pin
   constante pin= 0692
    variables
               i , code , tenta :  entier
Debut
   Tenta(0
     ecrire(“entrez un nombre comprit 4 chiffres : “)
     lire(code)
            pour i de 1 à 3 pas 1 faire
                 tenta( tenta +i
                   si ( 3 < tenta )
                    ecrire(“Blocage“)
 	si (code=pin)
                         ecrire(“succés“)
                           sinon
                             ecrire(“Erreur“)
                         fin si
                    fin si
                fin pour
fin
exercice 2 
Algorithme echange
  Variables 
      echange , a , b
Début
     Ecrire(“donnez un nombre :“)
      Lire(a)
      a( echange
    ecrire(“donnez un nombre :“)
    lire(b)
     b( a
      b( echange
fin
exercice 3
Algorithme pgcd
   variables  a , b : entier
Debut
    Ecrire(“donnez un nombre“)
    Lire(a)
     Ecrire(“donnez un nombre“)
     Lire(b)
       Repeter
           Si(b=0) alors
                Ecrire(“pgcd=“,a)
                  Sinon
                    b( a
                      b( mod a\b
                        ecrire(“pgcd“,a,b,“=“,b)
                   fin si
        jusqu’à( b=0)
fin
Algorithme pgcd
  Variables a,b : entier
    Fonction pgcd(x : entier , y : entier) : entier
      Si y=0 alors
       Retourne x
       Sinon
           y( x
        Retourne pgcd(mod x \ y)
        Y( mod x\y
      Fin fonction
Debut
    Ecrire(“donnez deux nombres :“)
      Lire(a,b)
        Ecrire(“pgcd“,a,b“=“,pgcd(a,b))
Fin
Exercice 4
Algorithme diviseurs
   Variables i, n : entier
Debut
     Pour i de 1 à n pas 1 faire
        Si ( mod n\i = 0) alors
          Ecrire(i “,“)
            Sinon
              Ecrire(i , “n’est pas d’un diviseur“)
           Fin si 
      Fin pour
Fin
Exercice 5
Algorithme game
  Variables i ,  n : entire
                 reponse  : booleen
   function aleatoire( 1,100) : entir
Debut	
  Tant que (reponse = oui)
     Ecrire(“donnez un nombre entre 1 et 100 : “)
      Lire(n)
        Pour i de 1 à 5 pas 1 faire
           Si (n=aleatoire(1,100) alors
             Ecrire(“félicitations“)
                Si (n> aleatoire) alors
                    Ecrire(“très grand “)
                        Sinon 
                           Ecrire(“très petite“)
                                 Si (i > 5) alors
                                    Ecrire( “le nombre secret est : “, aleatoire(1,100)
                                         Sinon 
                                              Ecrire( “est-ce-que tu peux continue the game ? : “)
                                                  Lire(reponse)
                                            Fin si
                                  Fin si
                           Fin si 
                   Fin pour
               Fin tant que
Fin
Exercice 6
Algorithme triangle floyd
  Variables n , d : entier 
    Procedure floyd (a : entier)
     i , j : entier
       pour i de 1 à a pas 1 faire
            pour j de 1 à i pas 1 faire
               ecrire(“  “)
              fin pour
       ecrire(floyd (a))
      fin pour
Debut 
 Ecrire(“entrez un nombre : “)
    Lire(n)
D( floyd(n) +1
 Ecrire(d)
Fin
Exercice 7
   Methode 1 
Algorithme somme
    Variables i , n ,s : entier
Debut
    Ecrire(“donnez un nombre : “)
      Lire(n)
          S( 0
            Pour i de 1 à n pas 1 faire
                 S( i + 1
               Fin pour
    Ecrire(“la somme des entiers est : “, s)
Fin
Methode 2
Algorithme somme 
   Variable n : entier
      Fonction somme (x : entier) : entier
          Si (x= 1)
            Retourne 1
             Sinon 
               Retourne somme (x+1)
               Fin si
    Fin fonction
Debut
   Ecrire (“donnez un nombre :“)
     Lire(n)
      Ecrire(“la somme est :“, somme(n))
fin
