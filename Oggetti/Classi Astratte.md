## Classi Astratte:

1. **Definizione**: Le classi astratte sono classi speciali in Java che non possono essere istanziate direttamente, cioè non è possibile creare oggetti direttamente da una classe astratta. Sono utilizzate come modelli o superclassi per altre classi derivate.
2. **Obiettivo**: Le classi astratte forniscono un'astrazione di base per altre classi. Contengono attributi e metodi comuni che le classi derivate ereditano e possono sovrascrivere.
3. **Attributi e Metodi**: Una classe astratta può contenere attributi e metodi, alcuni dei quali possono essere implementati e altri possono essere dichiarati come "astratti" (senza implementazione). Le classi derivate devono fornire l'implementazione per i metodi astratti.
```java
abstract class Forma
{
	int x, y;
}
```

4. **Ereditarietà**: Le classi derivate (sottoclassi) estendono una classe astratta e devono fornire un'implementazione per tutti i metodi astratti ereditati. Le classi astratte promuovono il concetto di ereditarietà, consentendo di creare una gerarchia di classi.
```java
class Cerchio extends Forma
{
	int raggio;
}
```

5. **Utilità**: Le classi astratte sono utili quando si vuole definire un comportamento comune o una struttura di base per un gruppo di classi correlate. Forniscono un modo per garantire che le classi derivate rispettino una certa interfaccia o implementino comportamenti specifici.