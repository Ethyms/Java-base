## If:
1. Le condizioni sono utilizzate per controllare il flusso di un programma e per eseguire istruzioni basate su condizioni specifiche.
2. Le condizioni valutano un'espressione o una relazione tra valori e restituiscono un valore booleano (vero o falso).
3. Le condizioni sono spesso utilizzate in istruzioni condizionali, come "if", "else if" e "else", per decidere quali istruzioni eseguire.
```java
int numero = 10;

if (numero > 5)
{
    System.out.println("Il numero è maggiore di 5.");
} else
{
    System.out.println("Il numero non è maggiore di 5.");
}
```
## Ternario:
1. L'operatore condizionale ternario è un operatore condizionale in Java che consente di eseguire un'operazione condizionale in una singola riga di codice.
2. È spesso utilizzato per assegnare un valore a una variabile in base a una condizione specifica.
3. Ha la seguente sintassi: `condizione ? valore_se_vera : valore_se_falsa`.
4. Se la "condizione" è vera, il risultato sarà "valore_se_vera"; altrimenti, sarà "valore_se_falsa".
```java
int punteggio = 80;

String messaggio = (punteggio >= 70) ? "Hai superato il test." : "Devi migliorare il tuo punteggio.";

System.out.println(messaggio);
```