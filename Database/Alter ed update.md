### Alter

**Aggiungere colonna**
```Mysql
ALTER TABLE [nome tabella] ADD COLUMN [nome campo] INT;
ALTER TABLE [nome tabella] ADD COLUMN [nome campo] varchar (255);
ALTER TABLE [nome tabella] ADD COLUMN [nome campo] date;
```
**Delete**
```Mysql
ALTER TABLE [nome tabella] DROP COLUMN [nome campo];
```
**Rinominare**
```Mysql
ALTER TABLE [nome tabella] RENAME COLUMN [vecchio nome campo] TO [nuovo nome campo];
```
**Cambiare tipo ad un campo**
```Mysql
ALTER TABLE [nome tabella] MODIFY COLUMN [nome campo] [nuovo tipo dato];
```

### Update
```Mysql
update [nome tabella] set [valore da cambiare] where [a chi devo cambiarlo];
```
Ecco un esempio pratico
```Mysql
update patient set city=’Napoli’ where id = (2);
```