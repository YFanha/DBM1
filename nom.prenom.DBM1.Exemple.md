# DBM1 - Administrer un SGBD SQL Server

Nom Prénom

Classe

## Questionnaire

1. Punico direpto certe abstractum et quidam auctoris abstractum opulentus profectus Argonautarum nomine Anazarbus vocabulum Cydno ?

    *Admodum similiaque Romae cum est.*

2. Celeritate nimia paulisper flexuosas sui ?

    *Romae summatim causas et lecturos ducebatur inplorans suam Cyprii est.*

## Laboratoire

Alii summum decus in carruchis solito altioribus et ambitioso vestium cultu ponentes sudant sub ponderibus lacernarum, quas in collis insertas cingulis ipsis adnectunt nimia subtegminum tenuitate perflabiles, expandentes eas crebris agitationibus maximeque sinistra, ut longiores fimbriae tunicaeque perspicue luceant varietate liciorum effigiatae in species animalium multiformes.

## Exercice 1

### SQL Server Management Studio

Haec ubi latius fama vulgasset missaeque relationes adsiduae Gallum Caesarem permovissent, quoniam magister equitum longius ea tempestate distinebatur, iussus.

- Sed si ille hac tam eximia fortuna propter
- Hac ita persuasione reducti intra moenia
- Post quorum necem nihilo lenius ferociens Gallus
- Orientis vero limes in longum protentus et rectum
- Latius iam disseminata licentia onerosus bonis

<div class="page-break" />

### Transact SQL

    USE master;  
    GO  
    CREATE DATABASE Archive   
    ON  
    PRIMARY    
        (NAME = Arch1,  
        FILENAME = 'D:\SalesData\archdat1.mdf',  
        SIZE = 100MB,  
        MAXSIZE = 200,  
        FILEGROWTH = 20),  
        ( NAME = Arch2,  
        FILENAME = 'D:\SalesData\archdat2.ndf',  
        SIZE = 100MB,  
        MAXSIZE = 200,  
        FILEGROWTH = 20),  
    LOG ON   
       (NAME = Archlog1,  
        FILENAME = 'D:\SalesData\archlog1.ldf',  
        SIZE = 100MB,  
        MAXSIZE = 200,  
        FILEGROWTH = 20),  
       (NAME = Archlog2,  
        FILENAME = 'D:\SalesData\archlog2.ldf',  
        SIZE = 100MB,  
        MAXSIZE = 200,  
        FILEGROWTH = 20) ;  
    GO

## Conclusion

Post quorum necem nihilo lenius ferociens Gallus ut leo cadaveribus pastus multa huius modi scrutabatur. quae singula narrare non refert, me professione modum, quod evitandum est, excedamus.

## Sources

- [Référence Transact-SQL (moteur de base de données)](https://docs.microsoft.com/fr-fr/sql/t-sql/language-reference)
- [CREATE DATABASE (SQL Server Transact-SQL)](https://docs.microsoft.com/en-us/sql/t-sql/statements/create-database-sql-server-transact-sql)
