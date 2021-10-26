# aggiungi-un-video-youtube

### Prerequisiti
- Conoscere come aggiungere degli stili personalizzati [Qui il link alla lezione](../aggiungi-stile-personalizzato)


Per ottenere un video responsive, che sia facilmente visualizzabile anche da mobile, e centrato, dovrai inserire le seguenti classi nello `style`:

```
.videowrapper {
      float: none;
      clear: both;
      width: 100%;
      position: relative;
      padding-bottom: 56.25%;
      padding-top: 25px;
      height: 0;
    }

    .videowrapper iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
```
  
- Ora vai su [Youtube](https://www.youtube.com) e cerca un video da inserire nel tuo sito
- Clicca sul video interessato
- Durante la riproduzione clicca con il tasto destro su **Copia codice per l'incorporamento**
- Inserisci il codice dentro il `div class="videowrapper"`

Ora puoi andare a vedere il bellissimo video sul tuo sito 😍
<kbd>![../assets/youtube-image.png](../../assets/youtube-image.png)</kbd>
