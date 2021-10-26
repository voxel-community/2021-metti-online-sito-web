# Bottone per tornare a inizio pagina

## Obiettivo: 

Creare un bottone per tornare velocemente ad inizio pagina.

## Step:

1. Aggiungi un bottone in fondo al documento, prima della chiusura del tag `</body>`

2. Aggiungi un attributo `id` al bottone con valore "myBtn"
3. Aggiungi gli stili per rendere il bottone sempre visibile e fisso in basso a destra. L'importante è che ci siano le proprietà

- `position: fixed` per manterlo fisso
- `bottom: 20px;` e `right: 30px;`
  Per mantere una certa distanza dal basso e da destra
- `z-index: 99;` per mantere il bottone al di sopra di tutti gli altri elementi della pagina.

4. Crea una funzione che si attiva cliccando il bottone.
Questa funzione ti farà andare a inizio pagina.
Aggiungi la funzione prima della chiusura del tag `</body>`

``` javascript
<script>
  function topFunction() {
    document.body.scrollTop = 0;
    document.documentElement.scrollTop = 0;
  }
</script>
```

1. Per collegare la funzione aggiungi al bottone `onclick="topFunction()"`

``` javascript
<button class="button" onclick="topFunction()" id="myBtn">Top ↑</button>
```

[Link di riferimento su W3S](https://www.w3schools.com/HOWTO/howto_js_scroll_to_top.asp)