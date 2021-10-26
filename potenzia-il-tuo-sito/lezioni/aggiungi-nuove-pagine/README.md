# Aggiungi-nuove-pagine

## Obiettivo: 
Creare un menù che permetta di accedere alle altre pagine del tuo sito.


## Step:

1. Crea un nuovo file che abbia l'estensione `.html`.
  * Questo file corrisponderà alla tua nuova pagina.
  * Ad esempio puoi creare una pagina `about.html`
  * Nel tuo file `.html` appena creato, copia il contenuto del file `index.html` creato precedentemente nel workshop.
   
2. Ora puoi andare su [Bulma](https://bulma.io) e cercare il componente **Navbar menu**

3. Copialo e incolla la struttura come primo elemento del tag `body`

4. Dentro il `div class="navbar-menu"` inserisci un `div class="navbar-end"`
  > Il navbar-end ti permette di avere il tuo menù a destra

5. All'interno di quest'ultimo inserisci un `div class="navbar-item"` per ogni diversa pagina che desideri avere sul tuo sito.

6. Dentro a questo _navbar-item_ inserisci un tag `a`, che servirà a creare un collegamento alla tua nuova pagina: 
  ```
    <a href="about.html">
      <h3>About</h3>
    </a>
  ```
  * All'interno di `href=""` inserisci il nome del file, inclusa l'estensione, che corrisponderà alla tua nuova pagina



Adesso puoi iniziare a personalizzare il contenuto della tua nuova pagina 😍
