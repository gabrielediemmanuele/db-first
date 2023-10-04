| COLONNA             | TIPO        | ATTRIBUTI             |
| ------------------- | ----------- | --------------------- |
| id                  | SMALL       | PRIMARY KEY           |
| marca               | varchar(50) | NOT NULL              |
| modello             | varchar(50) | NOT NULL              |
| carburante          | varchar(50) | NOT NULL              |
| km                  | FLOAT(6,3)  | NULL                  |
| cilindrata          | FLOAT(4,3)  | NULL                  |
| data_produzione     | YEAR        | NOT NULL              |
| data_di_acquisto    | DATE        | NULL                  |
| data_di_vendita     | DATE        | NULL                  |
| condizioni          | TINYINT     | UNSINGNED,DEFAULT(10) |
| luogo_di_produzione | VARCHAR     | NOT NULL              |
| colore              | VARCHAR     | NULL                  |
| tipologia           | VARCHAR     | NULL                  |
| prezzo_vendita      | FLOAT(8,6)  | NULL                  |
| prezzo_netto        | FLOAT(8,6)  | NULL                  |
| prezzo_di_acquisto  | FLOAT(8,6)  | NOT NULL              |
| porte               | TINYINT     | SIG                   |
| posti               | TINYINT     | SIG                   |
| ricondizionata      | TINYINT     | DEFAULT(0),NULL       |
