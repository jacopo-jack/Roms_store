# Roms_store
Un tentativo di "porting" di interntet arcade per dispositivi poco potenti e, alcuni datati.
## Dispositivi target
    1.Tim_box versione Android 8.0.0
    2.Huawey Y9
    3.Hp Compaq nx6110
 ### Cosa ho fatto? Problemi generici
    Ho scritto una struttura più snella possibile della home page e delle varie pagine dedicate agli emulatori che girano su Internet Arcade.
    Ho riunito tutti gli elementi di stile in un unico file css esterno e ho creato sia un service worker e una cache in js che, 
    come tutti gli altri script, caricati da file esterni. 
    Nell'inserire le rom ho usato il tag iframe; unico elemento per incorporare un'immagine o un video
    da Internet Archive. 
    Per quanto riguarda i problemi generici:
       1.Pulsante schermo intero non funziona
       2.Alcuni problemi con javascript per direttive deprecate 
 ## Problemi specifici
    1.Codec non supportato da BrowseHere (Tim_box)
    2.Schermata nera quando clicco sul gioco (Huawey Y9)
    3.Messaggio di errore "ia failed to load metadata" (Hp Compaq nx6110 con windows7 a 32bit)
 ## Link al sito
    https://jacopo-jack.github.io/Roms_store/
