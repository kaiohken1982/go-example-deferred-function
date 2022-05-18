## Deferred function

Si usano le deferred quando è necessario effettuare operazioni di chiusura, 
come ad esempio chiudere un file aperto, sbloccare un mutex.
È utile per evitare di ripetere linee di codice dove l'operazione di chiusura deve essere 
effettuata anche in caso di errore.
La funzione deferred viene lanciata in automatico al termine dell'esecuzione della funzione dove 
il defer è usato.

# Utilizzo

Compila 

```
go build .
```

Lancia

```
./deferred https://it.wiktionary.org/wiki/ciao
```

# Argomenti trattati

- Deferred function
- Best practice per chiusura risorsa