# Consegna
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name
- auto

## Table structure

- ID | BIGINT, AUTO_INCREMENT, PRIMARY_KEY (UNIQUE, NOTNULL)
- MARCA | VARCHAR(50), NOTNULL
- MODELLO | VARCHAR(50), NOTNULL
- ANNO | YEAR, NOTNULL
- KILOMETRI | MEDIUMINT, NOTNULL
- PREZZO | MEDIUMINT, NOTNULL
- DESCRIZIONE | TEXT, NULL
- FOTO(url) | TEXT, NULL


```js
const auto = {
    id: 1234567890,
    marca:'Ford',
    modello: 'Fiesta',
    anno: 2019,
    kilometri: 100000,
    prezzo: 14000,
    descrizione: 'auto perfetta per neopatentati e non',
    foto: 'http://example.com',
}
```