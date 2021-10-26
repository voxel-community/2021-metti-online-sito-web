# Aggiungi-menu

In questa lezione creeremo un menu con il quale potrai andare alle sezioni desiderate


- Vai su [Bulma](bulma.io) e cerca il componente **navbar menu**.
- Mettilo come primo elemento del `body`

- Dentro il `div class="navbar-menu"` inserisci un `div class="navbar-end"`


- Inserisci all'interno di quest'ultimo inserisci un numero di `div class="navbar-item"` pari al numero di elementi che vorresti avere nel tuo menù.

- Dentro a questo inserisci un tag `<a>`:
```
<a href="#bio">
    <h3>About</h3>
</a>
``` 

- Per far funzionare lo scroll fino alla sezione **bio**, inserisci dentro la section contente la bio un `<section class="section" id="bio">`

- Per mantenere sempre visibile e in alto la navbar puoi fissarla utilizzando la classe di bulma `is-fixed-top`

`<nav class="navbar is-fixed-top">`