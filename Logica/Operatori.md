## Operatori Aritmetici:

1. Gli operatori aritmetici vengono utilizzati per eseguire operazioni matematiche su numeri.
2. Gli operatori aritmetici principali includono l'addizione `+`, la sottrazione `-`, la moltiplicazione `*`, la divisione `/`, e il modulo `%`.
3. L'addizione `+` somma due numeri.
4. La sottrazione `-` sottrae un numero da un altro.
5. La moltiplicazione `*` moltiplica due numeri.
6. La divisione `/` divide un numero per un altro.
7. Il modulo `%` restituisce il resto di una divisione.
```java
int a = 10;
int b = 3;

int somma = a + b; // 13
int differenza = a - b; // 7
int prodotto = a * b; // 30
int divisione = a / b; // 3
int resto = a % b; // 1
```
## Operatori di Assegnazione:

1. Gli operatori di assegnazione vengono utilizzati per assegnare un valore a una variabile.
2. L'operatore di assegnazione più comune è `=`, che assegna il valore a sinistra alla variabile a destra.
3. Gli operatori di assegnazione combinati, come `+=`, `-=`, `*=`, ecc., eseguono un'operazione e assegnano il risultato alla variabile.
```java
int x = 5;
x = 10; // Assegna il valore 10 a x

int y = 7;
y += 3; // Equivale a y = y + 3, quindi y diventa 10
```
## Operatori di Confronto:

1. Gli operatori di confronto vengono utilizzati per confrontare due valori e restituiscono un valore booleano (true o false) che indica se la condizione è vera o falsa.
2. Gli operatori di confronto principali includono l'uguaglianza `==`, la non uguaglianza `!=`, il maggiore `>`, il minore `<`, il maggiore o uguale `>=` e il minore o uguale `<=`.
3. L'operatore `==` verifica se due valori sono uguali.
4. L'operatore `!=` verifica se due valori non sono uguali.
5. Gli operatori `<`, `>`, `<=`, e `>=` confrontano i valori in base all'ordine.
```java
int m = 5; int n = 7;
boolean uguaglianza = (m == n); // false
boolean nonUguaglianza = (m != n); // true
boolean maggiore = (m > n); // false
boolean minore = (m < n); // true
boolean maggioreOuguale = (m >= n); // false
boolean minoreOuguale = (m <= n); // true
```
## Operatori logici

1. Gli operatori logici in Java sono utilizzati per eseguire operazioni logiche su valori booleani.
2. Gli operatori logici principali includono NOT (`!`), AND (`&&`), e OR (`||`).
3. L'operatore NOT inverte un valore booleano. Ad esempio, `!true` restituirà `false`.
4. L'operatore AND restituisce `true` solo se entrambe le condizioni sono vere. Ad esempio, `condizione1 && condizione2` restituirà `true` solo se sia `condizione1` che `condizione2` sono vere.
5. L'operatore OR restituisce `true` se almeno una delle condizioni è vera. Ad esempio, `condizione1 || condizione2` restituirà `true` se almeno una tra `condizione1` e `condizione2` è vera.
```java
boolean condizione1 = true;
boolean condizione2 = false;
boolean risultatoAND = condizione1 && condizione2; // Restituisce false
boolean risultatoOR = condizione1 || condizione2; // Restituisce true
boolean risultatoNOT = !condizione1; // Restituisce false
```