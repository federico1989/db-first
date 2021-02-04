db-first

<!-- Creare un file di testo per descrivere un database di un negozio di videogiochi. -->

# database name : GameStop
# nome tabelle: Videogiochi

- id BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT UNIQUE
- titolo stringa VARCHAR(30) NOTNULL
- descrizione stringa TEXT NULL
- piattaforma stringa VARCHAR (30) NULL
- origine_paese stringa VARCHAR(15) NOTNULL
- genere stringa VARCHAR(10) NOTNULL
- editore stringa VARCHAR(20) NOTNULL
- fascia_d'età number SMALLINT NOTNULL
- barcode number SMALLINT NOTNULL UNIQUE
- requisiti_di_sistema stringa (50) NULL
- data_di_pubblicazione date DATE NOTNULL
- prezzo number FLOAT (6,2) NULL
- immagine_di_copertina stringa VARCHAR() NULL
- copie number TINYINT DEFAULT(0) NULL



