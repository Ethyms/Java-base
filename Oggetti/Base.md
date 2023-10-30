## Programmazione object oriented:

1. La object oriented è un paradigma di programmazione che si basa sul concetto di "oggetti".
2. Un oggetto è un'istanza di una classe e rappresenta un'entità del mondo reale con attributi (dati) e metodi (comportamenti).
3. Le classi definiscono il modello da cui vengono creati gli oggetti.
4. Gli oggetti possono interagire tra loro scambiando messaggi.
##### Classe
```java
public class Auto
{

	private String marca;
	private int anno;
	
	public Auto(){}
	
	public Auto(String marca, int anno)
	{
		this.marca = marca;
		this.anno = anno;
	}
	
	public int getAnno()
	{
		return anno;
	}
	
	public void setAnno()
	{
		this.anno = anno;
	}
	
	public String getMarca()
	{
		return marca;
	}
	
	public String setMarca()
	{
		this.anno = anno;
	}
```
##### Main
```java
Auto miaAuto = new Auto("Toyota", 2020);

// oppure

Auto miaAuto2 = new Auto();

miaAuto2.setAnno(2015);
miaAuto2.setMarca("Tesla");
```

