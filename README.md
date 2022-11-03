# Compilateur-Python 
Un mini compilateur python conçu avec Lex et Yacc // une partie pratique destinée au 1er année cycle d'ingénieurs pour la matière "Théorie de la compilation"
#### Remarque : Les noms des fichiers lex et du fichier yacc doivent être identiques 

### Voici les étapes à suivre.
* installer lex en utilisant la commande : sudo apt-get install lex
* installer yacc en utilisant la commande : sudo apt-get install bison
* lex lexer.l
* yacc lexer.y
* gcc y.tab.c -ll -ly
* ./a.out [nom du fichier]  


#### En exécutant la commande ' ./a.out [nom-du fichier] ' nous pouvons savoir si notre code est syntaxiquement correct ou pas.
