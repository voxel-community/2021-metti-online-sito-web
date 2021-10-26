# Personalizzare sito

Per poter modificare lo stile della pagina devi inserire nel tag `head` un tag `style`.

Il tag `style` è il contenitore di tutti gli stili, per modificare ad esempio:
* grandezza, colore, stile dei font
* colore di sfondo
* animazioni
* e moltre altre cose
  

Il linguaggio utilizzato nel tag style è chiamato **CSS**

## Modificare il font
* Vai su [fonts.google.com](fonts.google.com) che è una raccolta di font gratuiti che puoi utilizzare sul tuo sito.
* Clicca sul `+` in basso apparirà una tab `Family selected` con il font scelto
* Apri la tab e copia tutto il `link-href`
* Incollato nel tag `head`
* Crea un tag `style` all'interno del tag `head`. Inserisci il selettore desiderato, ad esempio `body`, questo farà in modo che le modifiche vengano applicate solo a quest'ultimo.
  
Ad esempio, prova ad applicarlo a tutto il documento scrivendo:

```
<style>
    body  {
        font-family: 'Cardo', serif;
    }
</style>
```

Ecco un link dei altri possibili selettori https://www.w3schools.com/cssref/css_selectors.asp

* Ora puoi provare a sostituire a `body` il tag `h1`, come vedrai, solo il titolo avrà un font diverso


## Modifica lo sfondo

Per modificare solamente determinate sezioni invece che tutti gli **elementi** `section` puoi creare una tua **classe** personale.

Ora definisci come deve essere `mio-sfondo-verde`  dentro il tag `style`, ad esempio:

```
<style>
    .mio-sfondo-verde  {
        background-color: lightseagreen;
    }
</style>
```
* Attenzione, per poter far capire al CSS che quella che stai creando è una classe, dovrai mettere il punto davanti al nome della classe.
* Possono essere inseriti anche colori nelle codifiche **HEX** _#000000_ e **rgb** _rgb(0,0,0)_



Aggiungi questa classe all'interno di una section in questo modo: 

`<section class="section mio-sfondo-verde >`




Puoi sperimentare con molte altre proprietà che puoi trovare qui https://cssreference.io/ 😍