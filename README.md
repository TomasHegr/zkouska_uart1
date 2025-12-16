Uart1 project
===========================

Účel/Zadání/Funkce
-----------------------

Pomocí klávesnice ovládám rychlost blikání LED. Číslice 1,2,3,4,5,7,8,9 mění rychlost blikání.
 0 blikání zastaví. 
Další zkouška ve škole

 takhle se dělá odkaz [odkaz](https://wwww.spseol.cz/)


 Vygenerování ssh klíče:
-----------------------
 * ssh-keygen
 * enter
 * enter
 * pasphrase nebo enter
 * cat ~/.ssh/...něco.pub (pomocí tabulátoru)
* označit myší od začátku do konce
* na profilu github, gitlab:  nastavení -> ssh key -> new key -> vložit -> v gitlabu dát expiraci na never
* jít zpěto do  prázdneho projeku na githubu
* zde jsou instrukce a nejdůležitejěí ->  git remote add origin..........( vložit do terminalu)
*

Schema zapojení
-----------------------

 schéma zatím bude takto....potom se změní
![schema zapojení](./docs/schema.png)

Popis funkce
-----------------------

1. Rozblikám LED, rychlost blikání je uložena v proměnné
2.  zapnu přerušení od UART1
3. v rutině přerušení měním proměnnou, která určuje rychlost blikání
4. nevim nevim nevim



ToDo
-----------------------

* tohle

