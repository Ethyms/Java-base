### Crea database
Questa query permetterà di creare un database
```Mysql
create database [nome database];
```
### Seleziona database da usare
Mentre questa permette di usarlo, questa query è fondamentale per poi poter utilizzare tutte le query successive, quindi, ricorda sempre di usarla appena avvii MySQL.
```Mysql
use [nome database];
```
### Elimina un database
La prossima permetterà di cancellare un database
```Mysql
DROP DATABASE [nome database];
```
### Crea tabella
Una cosa importantissima dei database sono le tabelle, quindi di seguito vedremo come lanciare le query principali
```Mysql
create table Patient ([colonna1], [colonna2], [colonna3], ...);
```

### Inserisci riga nella tabella
```Mysql
insert into patient ([colonna1], [colonna2], [colonna3], ...),
values
([valore1], [valore2], [valore3], ...),
([valore1], [valore2], [valore3], ...),
([valore1], [valore2], [valore3], ...),
...;
```

