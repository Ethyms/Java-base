
| Vettori | Liste | Set | Maps |
| ---------- | --------- | ---- | ---- |
| Dimensione fissa. |  Dimensione variabile. | Dimensione variabile. | Dimensione variabile. |
| Contenere duplicati | Contenere duplicati | Non contenere duplicati | Non contenere duplicati |
| Iterati, insieme Ordinato | Iterati, insieme Ordinato | Non ordinata | Non ordinata, ma con rapporto chiave-valore |
|Tipi primitivi e oggetti | Oggetti | Oggetti | Oggetti |

## Vettori (Arrays):
1. I vettori sono una collezione di elementi dello stesso tipo con dimensione fissa.
2. La dimensione di un vettore viene specificata al momento della creazione e non può essere modificata successivamente.
3. Gli elementi di un vettore possono essere acceduti direttamente utilizzando l'indice.
4. I vettori possono contenere tipi di dati primitivi e oggetti.

```java
int[] array = new int[5];
```
## Liste:
1. Le liste sono una collezione ordinata di elementi con dimensione dinamica.
2. Le liste possono contenere duplicati e consentono l'inserimento, la rimozione e l'accesso agli elementi in base all'indice.
3. Le liste offrono molte operazioni utili come l'aggiunta di elementi, la ricerca e la rimozione di elementi.
```java
List<String> lista = new ArrayList<String>();
```
## Set:
1. I set sono una collezione non ordinata di elementi unici.
2. I set non consentono duplicati, quindi ogni elemento è presente al massimo una volta nel set.
3. I set consentono di verificare la presenza di un elemento e di aggiungere o rimuovere elementi.

```java
Set<Integer> set = new HashSet<Integer>();
```

## Mappe:
1. Le mappe sono una collezione di coppie chiave-valore, dove ogni chiave è unica.
2. Le mappe non consentono duplicati delle chiavi, ma gli stessi valori possono essere associati a chiavi diverse.
3. Le mappe consentono di recuperare il valore associato a una chiave specifica e di verificare la presenza di una chiave.

```java
Map<String, Integer> mappa = new HashMap<String, Integer>();
```
