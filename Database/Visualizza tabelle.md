
### Base
```Mysql
Select * from [nome tabella];
```
Se invece avessimo voluto selezionare solo alcuni campi avremmo dovuto specificarli nel select, quindi `Select [nome campo1]`,

```Mysql
Select * from [nome tabella] where [condizione];
```
Penso sia meglio raffigurare un esempio concreto
```Mysql
Select * from patient where id > 10
```
Oltre a questo posso mettere anche altre condizioni tramite `and` ed `or`
```Mysql
Select name, surname, dob from patient where city is not null and (id > 10 or dob < 1996-02-20)
```

**AS**: L’as ci permette di chiamare con un altro nome un campo, oppure di crearne momentaneamente uno con quel nome
```Mysql
Select name as 'Nome' from patient;
```
**Like**: L'operatore LIKE è utilizzato per eseguire una ricerca di stringhe in una colonna di una tabella.
```Mysql
SELECT * FROM MedicalNote WHERE description LIKE '%accin%';
SELECT * FROM MedicalNote WHERE description LIKE('%accini%' or '%tturazioni%');
```
**IN**: Quando vuoi selezionare righe in cui il valore della colonna è uguale a determinati valori puoi usare l’in puoi utilizzare l'operatore IN così
```Mysql
SELECT * FROM patient WHERE city IN ('Napoli', 'Milano');
```
**Between**: Il between ci permette di filtrare tra un valore minimo ed un valore massimo 
```Mysql
SELECT * FROM patient WHERE id BETWEEN 10 AND 15;
```
**year(dob)**: Ci permette di prendere il valore dell’anno di una variabile di tipo date, la stessa cosa funzione funziona per month e per day.
```Mysql
Select year(dob) as ‘Anno di nascita’ from patient where year(dob) < 1996;
```
**CURDATE()**: Ci permette di prendere la data attuale
```Mysql
Select curdate()-year(dob) as 'daysalive' from patient;
```
**CONCAT()**: Ci permette di concatenare 2 o più campi in uno
```Mysql
Select concat (name,' ', surname) as ‘nameandsurname’ from patient;
```