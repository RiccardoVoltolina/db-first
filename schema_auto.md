<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# auto dealer database

## Table name

- cars

## Table columns

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- Auto_Name | VARCHAR(255 ), NOT NULL
- model | VARCHAR(255 ), NOT NULL
- year_production | YEAR, NULL
- price | DOUBLE (8, 2), NULL
- optionals | TEXT, NULL
- Auto_image | VARCHAR(255), NULL
- is_avaible | VARCHAR (3), DEFAULT (YES)
- color | VARCHAR (50), DEFAULT (BLACK)
- displacement | TEXT, DEFAULT ('CONCESSIONARIO MERCEDES BRUZZANO')

<!-- 

attributi: 

not null: non viene passato alcun valore durante il salvataggio
null: puo contenere un valore nullo
default: se non c'è alcun valore assegnato, possiamo dargli noi un valore di default

-->

<!-- 

date:

datetime: memorizza data e ora
date: memorizza la data
time: memorizza l'orario
year: memorizza l'anno
timestamp: ha diversi formati

 -->

 <!-- 
 
 stringhe e database:

 VARCHAR(numero): indica la lunghezza massima della stringa, max 255 caratteri
 text: fino a 65535 caratteri
 mediumtext: fino a 16 mb
 longtext: fino a 4.2gb
 
  -->

  <!-- 
  
  numeri con la virgola: (i= numero di cifre totali d= numeri dopo la ,)

  float (i,d): un numero con la , da 4 bytes
  double (i,d): un numero con la , da 8 bytes
  decimal (i,d): è un double che gestisce gli arrotondamenti
  
   -->


   <!-- 
   
   numeri:

   tinynt: occupa 1 byte da -128 a 127
   small/ medium: occupano rispettivamente 2 e 3 byte
   int: da -2117483648 a 2117483647
   bigint: uguale a int x2
   
    -->


