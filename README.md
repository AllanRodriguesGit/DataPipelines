# DataPipelines
Creating some DataPipelines projects (ETL, ELT, BigData) and different tools and languages. 

## For the project MUSIC_ETL please create your database environent using the script below.
-- I am using SQL SERVER DATABASE.
CREATE DATABASE Music_ETL <br/>
GO <br/>

USE Music_ETL <br/>
GO <br/>

CREATE TABLE dbo.SessionHistory <br/>
( <br/>
  ID           BIGINT IDENTITY(1,1) <br/>
, Artista      VARCHAR(500) <br/>
, PrimeiroNome VARCHAR(500) <br/>
, UltimoNome   VARCHAR(500) <br/>
, Genero       CHAR(01)     <br/>
, Localidade   VARCHAR(500) <br/>
, Musica       VARCHAR(500) <br/>
);<br/>


