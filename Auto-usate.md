# Tabella auto usate

-id BIGINT NOTNULL PRIMARYKEY (UNIQUE AUTOI_NCREMENT)
-marca VARCHAR(50) NOTNULL INDEX
-modello VARCHAR(70) NOTNULL INDEX
-prezzo INT NOTNULL INDEX
-chilometri INT NOTNULL INDEX
-data immatricolazione DATE NOTNULL INDEX
-potenza_in_hp SMALLINT NULL
-potenza_in_Kw SMALLINT NULL
-cilindrata SMALLINT NULL
-trazione VARCHAR(20) NULL
-tipo_di_cambio VARCHAR(20) NULL
-tipo_di_alimentazione VARCHAR(20) NULL INDEX
-porte TINYINT NULL
-posti_a_sedere TINYINT NULL
-foto VARCHAR(255) NULL
-comfort TEXT NULL

- note NULL
