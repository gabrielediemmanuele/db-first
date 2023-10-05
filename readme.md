# Correzzione

| COLONNA             | TIPO        | ATTRIBUTI                 |
| ------------------- | ----------- | ------------------------- |
| id                  | bigInt      | PRIMARY KEY,Autoincrenent |
| marca               | varchar(50) | NOT NULL                  |
| modello             | varchar(50) | NOT NULL                  |
| carburante          | varchar(50) | NOT NULL                  |
| km                  | FLOAT(8,2)  | NULL                      |
| cilindrata          | FLOAT(6,2)  | NULL                      |
| data_produzione     | YEAR        | NOT NULL                  |
| data_di_acquisto    | DATE        | NULL                      |
| data_di_vendita     | DATE        | NULL                      |
| condizioni          | TINYINT     | DEFAULT(10),UNSIGNED      |
| luogo_di_produzione | VARCHAR(20) | NOT NULL                  |
| colore              | VARCHAR(20) | NULL                      |
| tipologia           | VARCHAR(20) | NULL                      |
| prezzo_vendita      | FLOAT(8,3)  | NULL ,UNSIGNED            |
| prezzo_netto        | FLOAT(8,3)  | NULL ,UNSIGNED            |
| prezzo_di_acquisto  | FLOAT(8,3)  | NOT NULL ,UNSIGNED        |
| porte               | TINYINT(1)  | NULL                      |
| posti               | TINYINT(2)  | NULL                      |
| ricondizionata      | TINYINT(1)  | DEFAULT(0)                |

# Versione Precedente

| COLUMN           | TYPE        | ATTRIBUTES            |
| ---------------- | ----------- | --------------------- |
| id               | SMALL       | PRIMARY KEY           |
| brand            | VARCHAR(50) | NOT NULL              |
| model            | VARCHAR(50) | NOT NULL              |
| fuel             | VARCHAR(50) | NOT NULL              |
| km               | FLOAT(6,3)  | NULL                  |
| displacement     | FLOAT(4,3)  | NULL                  |
| date_production  | YEAR        | NOT NULL              |
| purchase_date    | DATE        | NULL                  |
| sale_date        | DATE        | NULL                  |
| condition        | TINYINT     | UNSINGNED,DEFAULT(10) |
| production_place | VARCHAR     | NOT NULL              |
| color            | VARCHAR     | NULL                  |
| typology         | VARCHAR     | NULL                  |
| selling_price    | FLOAT(8,6)  | NULL                  |
| net_price        | FLOAT(8,6)  | NULL                  |
| purchase price   | FLOAT(8,6)  | NOT NULL              |
| doors            | TINYINT     | SIG                   |
| car_seats        | TINYINT     | SIG                   |
| refurbished      | TINYINT     | DEFAULT(0),NULL       |

displacement: cilindrata
