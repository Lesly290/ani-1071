    *ANALYSONS LA PREMIERE ERREUR 
Lors de l'écriture de mon programme il était correct .Mais , après avoir retiré les points virgules(;) sur les lignes 4,5 et 6, j'ai effectué la compilation de mon programme et j'ai reçu une alerte de 3 erreurs . Ils s'agit de : 
c1-exo3_main.cpp:6:9: error: expected ';' after return statement 6 | return 0 | ^ | ; 3 errors generated. 
Qui nous indique clairement qu'il y'a bien et bel des soucis lors de l'exécution de notre devoir.


    * ANALYSONS LA DEUXIEME ERREUR
Afin de mieux expliquer le 2ème volet de cette question, nous avons remplacé la commande printf par Printf . Et les erreurs suivantes ont été affichés :
| ^~~~~~ | printf C:/msys64C/ucrt64/include/stdio.h:300:5: note: 'printf' declared here 300 | int printf (const char *__format, ...) | ^ 2 errors generated. 
Ainsi , nous voyons bien ses 2 erreurs .
   
   
    *ANALYSONS LA TROISIEME ERREUR
Le but du 3ème volet de ce devoir consiste à retirer la ligne #include . De ce fait , nous avons analysé les erreurs qui suivent :
printf("LESLY CHEBOU\n"); | ^~~~~~ c1-exo3_main.cpp:5:1: error: use of undeclared identifier 'printf' 5 | printf("YAOUNDE\n"); | ^~~~~~ 2 errors generated. 
De ce fait, nous pouvons bien voir qu'en exécutant le programme tout en retirant la ligne comportant #include , nous retrouvons les erreurs consignées ci déçu.
