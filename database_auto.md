**DATABASE AUTO USATE**

| NOME COLONNA            | TIPO DI DATO | ATTRIBUTI | INDICI      |
| ----------------------- | ------------ | --------- | ----------- |
| Id                      |              | NOT NULL  | PRIMARY KEY |
| Marca                   | VARCHAR(20)  | NOT NULL  |             |
| Modello                 | VARCHAR(40)  | NOT NULL  |             |
| Anno                    | YEAR         | NOT NULL  |             |
| Immatricolazione        | DATE         | NOT NULL  |             |
| Km                      | MEDIUMINT    | NOT NULL  |             |
| Carburante              | VARCHAR(15)  | NOT NULL  |             |
| Categoria (es. Berlina) | VARCHAR(20)  | NULL      |             |
| Cambio                  | VARCHAR(20)  | NOT NULL  |             |
| Colore                  | VARCHAR(30)  | NULL      |             |
| Posti                   | TINYINT      | NULL      |             |
| Prezzo_vendita          | FLOAT(8,2)   | NOT NULL  |             |
