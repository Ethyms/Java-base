### Inner join
Fare i join sulle tabelle considerando la seguente formula
```Mysql
select * from A inner join B on A.id = B.Aid
```
L'operazione di INNER JOIN ti permette di unire due tabelle basandosi su un dato in comune, nel nostro caso la chiave esterna e la chiave primaria. Quando esegui un INNER JOIN, vengono prese solo le righe che hanno lo stesso valore nelle due tabelle.

### Left join
```Mysql
SELECT * FROM A left join B on A.id = B.Aid;
```
L'operazione di LEFT Ti permette di unire due tabelle basandosi su un dato in comune. Ma a differenza dell'INNER JOIN, il LEFT JOIN ti assicura che tutte le persone da una tabella verranno incluse nel risultato finale, anche se alcune di esse non rientrano nel predicato di join