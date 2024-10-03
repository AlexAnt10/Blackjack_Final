Blackjack:


Acest proiect este implemantarea jocul de casino “Blackjack” scris in limbajul de programare C++.Programul urmeaza regulile standard din Blackjack, in care rolul jucatorului este de al invinge pe dealer optinand un punctaj mai mare decat acesta dar in acelasi timp suma cartilor sa nu depaseasca valoarea de 21.


Caracteristici:

-Sistem de autentificare și înregistrare

-Sold de bani virtuali pentru fiecare jucător

-Sistem de pariere

-Amestecarea și distribuirea cărților

-Calcularea valorii totale a mâinii

-Afișarea mâinii jucătorului și a dealerului

-Determinarea câștigului/pierderii în funcție de valorile mâinilor

-Actualizarea soldului jucătorului după fiecare rundă


Structura programului:

Ca sa intelegeti mai bine aces program si implementarea acestuia o sa vorbesc putin despre clasele care fac parte din el si importanta lor:

Clasa Card: 

-reprezinta o carte indivuala si se ocupa de gestionarea si afisarea acesteia

Clasa Deck:
-creeeaza si amesteca pachetul de 52 de carti si gestioneaza distributia lor

Clasa Hand:

-gestioneaza cartile pe care le are un jucator sau dealerul intr o runda

Clasa Player:

-reprezinta jucatorul sau dealerul, permitandu le sa traga carti si sa afiseze mainile lor.

Clasa Game: 

-este responsabila pentru logica generala a jocului, incluzand gestionarea scorurilor, balantei si interactiunea intre jucator si dealer  
